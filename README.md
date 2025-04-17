# Common Network Ports Grouped by Protocol

## **File Transfer Protocols**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 20       | FTP Data     | File Transfer Protocol (data transfer) |
| 21       | FTP Control  | File Transfer Protocol (commands) |
| 69       | TFTP         | Trivial File Transfer Protocol (file transfer) |
| 514      | Syslog       | System logging service (used in file systems) |

## **Email Protocols**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 25       | SMTP         | Simple Mail Transfer Protocol (sending email) |
| 110      | POP3         | Post Office Protocol (retrieving email) |
| 143      | IMAP         | Internet Message Access Protocol (email access) |
| 587      | SMTP (Submission) | Secure SMTP (sending email with encryption) |
| 993      | IMAPS        | Secure IMAP (encrypted email access) |
| 995      | POP3S        | Secure POP3 (encrypted email retrieval) |

## **Web Traffic**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 80       | HTTP         | HyperText Transfer Protocol (web traffic) |
| 443      | HTTPS        | Secure HyperText Transfer Protocol (encrypted web traffic) |
| 8080     | HTTP (alt)   | Alternative HTTP port (used for web servers, proxies) |
| 8081     | HTTP (alt)   | Another alternative HTTP port (used by web apps) |

## **Remote Access Protocols**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 22       | SSH          | Secure Shell (remote login) |
| 23       | Telnet       | Remote login (unsecure) |
| 3389     | RDP          | Remote Desktop Protocol (Windows remote access) |
| 5900     | VNC          | Virtual Network Computing (remote desktop) |

## **Database Services**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 3306     | MySQL        | MySQL database service |
| 1433     | MS SQL Server| Microsoft SQL Server service |
| 1521     | Oracle DB    | Oracle Database service |
| 27017    | MongoDB      | MongoDB database service |

## **Network Management & Services**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 53       | DNS          | Domain Name System (name resolution) |
| 161-162  | SNMP         | Simple Network Management Protocol |
| 123      | NTP          | Network Time Protocol (time synchronization) |
| 2049     | NFS          | Network File System (file sharing) |

## **Miscellaneous Protocols**

| **Port** | **Protocol** | **Description** |
|----------|--------------|-----------------|
| 1        | TCPMUX       | TCP Port Service Multiplexer |
| 631      | IPP          | Internet Printing Protocol |
| 11211    | Memcached    | Distributed memory caching service |
| 9200     | Elasticsearch| Elasticsearch service |
| 9300     | Elasticsearch (Cluster) | Elasticsearch cluster communication |
