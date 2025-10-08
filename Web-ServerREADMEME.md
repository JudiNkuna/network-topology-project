# Part II: Basic Web Server Configuration

# Objective
Configure and demonstrate a fully functional web server with multiple pages, DNS integration, and access control.

## Server Configuration

# Network Details
| Parameter | Value |
|-----------|-------|
| Server Name | HTTP-Server |
| IPv4 Address | 192.168.30.10/24 |
| IPv6 Address | 2001:db8:30::10/64 |
| Default Gateway | 192.168.30.1 |
| DNS Server | 192.168.30.11 |
| VLAN | 30 (Server VLAN) |
| Services | HTTP, DNS |

# DNS Configuration
| DNS Name | IP Address |
|----------|------------|
| mywebsite.com | 192.168.30.10 |
| www.mywebsite.com | 192.168.30.10 |

---

## 📄 Web Pages Created

# 1. index.html (Homepage)
- **Purpose:** Main landing page
- **Features:** 
  - Responsive design
  - Network statistics
  - Server information
  - Navigation menu

# 2. about.html
- **Purpose:** Project information
- **Features:**
  - Project overview
  - Learning objectives
  - Technologies used

# 3. topology.html
- **Purpose:** Network diagram
- **Features:**
  - Visual topology representation
  - Layer breakdown
  - Network summary

# 4. contact.html
- **Purpose:** Contact information
- **Features:**
  - Student details
  - Server details
  - Project information

---

#  Security Implementation

# Access Control List (ACL 100)
```cisco
access-list 100 permit tcp 192.168.10.0 0.0.0.255 host 192.168.30.10 eq 80
access-list 100 permit tcp 192.168.10.0 0.0.0.255 host 192.168.30.10 eq 443
access-list 100 permit icmp any any
access-list 100 deny ip any host 192.168.30.10
access-list 100 permit ip any any
