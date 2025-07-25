# Supporting Network Services

## Key Concepts
*	Understand common network services: DHCP, DNS, file/print servers
*	Recognize protocols related to network services (SMB, FTP, SMTP, IMAP, POP3)
*	Understand virtual networks: VLANs and VPNs
*	Understand how DNS queries and records work (A, AAAA, CNAME, MX, SPF, DKIM, DMARC)
*	Describe the role of directory and authentication services (LDAP, AAA)
*	Understand remote access technologies (SSH, RDP, Telnet)

## Homelab

1. Open Command Prompt
2. Use Commands:
   * ```nslookup google.com``` (A record)
   * ```nslookup -query=AAAA google.com``` (IPv6)
   * ```nslookup -query=CNAME www.microsoft.com```
3. Note IP addresses and aliases
4. Look up MX records for a domain: ```nslookup -query=MX gmail.com```
5. Use online tools (MXToolbox) to check SPF, DKIM, DMARC for popular domains

# Alternate Lab

1. On Windows:
   * Create a shared folder (Right Click &rarr; Properties &rarr; Sharing)
   * Access it from another device on the same network
2. Use FTP server software (FileZilla Server)
   * Set up a local FTP server
   * Connect to it with an FTP client (FileZilla CLient) from another device
