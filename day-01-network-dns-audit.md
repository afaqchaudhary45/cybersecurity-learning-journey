# Day 1 — Windows Network and DNS Audit

## Objective
Test basic network configuration, DNS resolution, and IP connectivity using Windows Command Prompt.

## Tools
- `ipconfig`
- `ipconfig /all`
- `nslookup`
- `ping`

## Tests and Results

### 1. Network Configuration
**Command:** `ipconfig`

**Result:**
- Wi-Fi adapter was connected.
- An IPv4 address and default gateway were present.
- Other listed adapters showed media disconnected.

### 2. DNS Configuration
**Command:** `ipconfig /all`

**Result:**
- A DNS Servers entry was present.
- Private network details have been omitted for privacy.

### 3. DNS Resolution
**Command:** `nslookup google.com`

**Result:**
- DNS returned IPv4 and IPv6 addresses for `google.com`.
- A non-authoritative answer was returned.
- DNS resolution succeeded.

### 4. IPv4 Connectivity
**Command:** `ping 1.1.1.1`

**Result:**
- Packets sent: 4
- Packets received: 4
- Packet loss: 0%
- Average round-trip time: 36 ms

### 5. Google Connectivity Using IPv6
**Command:** `ping google.com`

**Result:**
- Google resolved to an IPv6 address for this test.
- Packets sent: 4
- Packets received: 4
- Packet loss: 0%
- Average round-trip time: 64 ms

## Conclusion
DNS resolution and both tested IP connectivity paths succeeded during this session. No packet loss was observed in either four-packet ping test. These short tests do not guarantee continuous connectivity or availability of every website or service.

## Privacy
Actual local IP addresses, gateway details, DNS server addresses, and personal device information have been omitted from this public report.

## Skills Practiced
- Reading Windows IP configuration
- Identifying DNS server configuration
- Testing DNS resolution
- Comparing IPv4 and IPv6 connectivity
- Interpreting packet loss and latency
