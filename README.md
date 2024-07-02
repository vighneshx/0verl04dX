# DNS Amplification DDoS Attack Tool
  **Handle with Extreme Caution** 
  <br>
  Advanced DNS amplification DDoS weapon.  
 ------------------------------------------------------------
* vighneshx 
 ------------------------------------------------------------
### Briefing:

Project 0verl04dX represents a strategic tool in my offensive cyber arsenal, designed to achieve mission success through precision, efficiency, and operational discretion. Execute with utmost caution and adhere strictly to operational guidelines to ensure mission success and operational security.

 * [RFC1700: NUMBERS](https://datatracker.ietf.org/doc/html/rfc1700)
 * [RFC1035: DNS](https://datatracker.ietf.org/doc/html/rfc1035)
 * [RFC1071: CHECKSUM](https://datatracker.ietf.org/doc/html/rfc1071)
 * [RFC768: UDP](https://www.rfc-editor.org/rfc/rfc768.html)
 * [RFC760: IP](https://www.rfc-editor.org/rfc/rfc760)
 ------------------------------------------------------------
 * Deploy: `sudo ./0verl04dX -t <target> -p <port> -m <magnitude>`
 * Compile: `(vighneshx㉿rs)-$ gcc 0verl04dX.c -o 0verl04dX`
 * Execute: `(vighneshx㉿rs)-$ sudo ./0verl04dX -t 127.0.0.1 -p 80 -m 1337`
  ------------------------------------------------------------
 * Options:
 * `[-x]` - Display packet headers in hexadecimal format
 * `[-d]` - Activate debug mode: simulate without transmitting packets
 * `[-r list]` - Use specified resolv list; bypass automatic fetching
 ------------------------------------------------------------
 
 **Overview: DNS Amplification Assault**
 * High-impact DDoS maneuver leveraging compromised DNS servers.
 * Initiate DNS queries with falsified source data aimed at target IP.
 * Redirect DNS responses, triggering overwhelming influx of data. 
 ------------------------------------------------------------
### Execution 
1. `gcc 0verl04dX.c -o 0verl04dX`.
2. `sudo ./0verl04dX -t <target> -p <port> -m <magnitude>`.

### Operations
- **Hexdump Analysis**: Visualize intricate packet headers with `-x`.
- **Stealth Mode**: Test operational readiness discreetly with `-d`.
- **Custom Resolv Integration**: Optimize mission parameters with `-r list`.

### Amplification Tactics
Leverage adversary assets against their own infrastructure. <br> By exploiting vulnerable DNS servers, spoofed queries overwhelm targets with a deluge of data. 
