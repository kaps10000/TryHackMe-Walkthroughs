# <div align="center">[DNS in Detail](https://tryhackme.com/room/dnsindetail)</div>
<div align="center">Learn how DNS works and how it helps you access internet services.</div>

## Task 1. What is DNS?

DNS (Domain Name System) provides a simple way for us to communicate with devices on the internet without remembering complex numbers. Much like every house has a unique address for sending mail directly to it, every computer on the internet has its own unique address to communicate with it. This is known as an IP address. An IP address looks like the following: 104.26.10.229. These aren't exactly easy to remember, which is where DNS can help.

### What does DNS stand for?
```
Domain Name System
```

## Task 2. Domain Hierarchy

### What is the maximum length of a subdomain?
```
63
```
### Which of the following characters cannot be used in a subdomain (3 b _ -)?
```
_
```
### What is the maximum length of a domain name?
```
253
```
### What type of TLD is .co.uk?
```
ccTLD
```

## Task 3. Record Types

DNS isn't just for websites though, and multiple types of DNS record exist. Some of the most common ones are:

- **A Record** — These records resolve to IPv4 addresses.
- **AAAA Record** — These records resolve to IPv6 addresses.
- **CNAME Record** — These records resolve to another domain name.
- **MX Record** — These records resolve to the address of the servers that handle the email for the domain.
- **TXT Record** — These records are free text fields where any text-based data can be stored.

### What type of record is used to advise where to send email?
```
MX
```
### What type of record handles IPv6 addresses?
```
AAAA
```

## Task 4. Making A Request

### What field specifies how long a DNS record should be cached for?
```
TTL
```
### What type of DNS server is usually provided by your ISP?
```
recursive
```
### What type of server holds all the records for a domain?
```
authoritative
```

## Task 5. Practical

### What is the CNAME of shop.website.thm?
```
shops.myshopify.com
```
### What is the value of the TXT record of website.thm?
```
THM{7012BBA60997F35A9516C2E16D2944FF}
```
### What is the numerical priority value for the MX record?
```
30
```
### What is the IP address for the A record of www.website.thm?
```
10.10.10.10
```
