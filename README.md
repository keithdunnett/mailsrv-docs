# mailsrv-docs
Documentation and notes for Debian 9 mail system 

## Roadmap

### Target: networking preliminaries

- disabled IPv6 in `/etc/sysctl.d/disableipv6.conf` as IPv6 is not required
- set up SSH access to allow root login by public key authentication only

### Target: mail can be read
- migrate mail dirs from pluto
- migrate PostfixAdmin database from pluto
- set up Dovecot as IMAP server, authentication server

### Target: mail can be sent
- set up Postfix
- set up dovecot-auth

### Target: mail can be delivered locally

### Target: mail accounts can be managed
- LAMP stack
- PostfixAdmin 
### Target: mail can be read using webmail

