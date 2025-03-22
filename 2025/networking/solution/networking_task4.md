# Networking Commands Cheat Sheet

## 1. `ping` - Check Network Connectivity
**Purpose:** Sends ICMP echo requests to a host to check if it's reachable and measure response times.  
**Usage:**  
```sh
ping <hostname or IP>
```
**Example:**  
```sh
ping google.com
```

---

## 2. `traceroute` / `tracert` - Trace Packet Routes
**Purpose:** Displays the route packets take to reach a destination. Useful for identifying network latency and routing issues.  
**Usage:**  
- **Linux/macOS:**
```sh
traceroute <hostname or IP>
```
- **Windows:**
```sh
tracert <hostname or IP>
```
**Example:**  
```sh
traceroute google.com
```

---

## 3. `netstat` - Display Network Statistics
**Purpose:** Shows active connections, listening ports, and network statistics.  
**Usage:**  
```sh
netstat [options]
```
**Example:**  
```sh
netstat -an  # Show all connections and listening ports
```

---

## 4. `curl` - Make HTTP Requests
**Purpose:** Fetches web pages, interacts with APIs, and transfers data over HTTP/HTTPS.  
**Usage:**  
```sh
curl [options] <URL>
```
**Examples:**  
- Get headers of a webpage:
```sh
curl -I https://example.com
```
- Download a file:
```sh
curl -O https://example.com/file.txt
```

---

## 5. `dig` / `nslookup` - DNS Lookup
**Purpose:** Queries DNS records to find IP addresses, MX records, and more.  
**Usage:**  
- **Linux/macOS (`dig`):**
```sh
dig <domain>
```
- **Windows/macOS (`nslookup`):**
```sh
nslookup <domain>
```
**Example:**  
```sh
dig google.com
nslookup google.com
```

---

This cheat sheet provides a quick reference for essential networking commands. Perfect for troubleshooting and network diagnostics!

