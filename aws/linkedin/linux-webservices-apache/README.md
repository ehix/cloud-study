# Linux Webservices (Apache)

[Course](https://www.linkedin.com/learning/linux-web-services)

[Apache vs. Node](https://dev.to/emiliosp/nodejs-vs-apache-performance-battle-for-the-conquest-of-my-5c4n#:~:text=In%20few%20words%2C%20Apache%20manages,thread%20called%20the%20event%20loop.)

# Contents

# Serve Web Content with Apache

## How a web server works
WS SW:
- Apache 
- nginx 
- Microsoft IIS
- App servers and frameworks (Tomcat/Java, Node/JS, Sinatra/Ruby, etc)
- Listens on a port (80/TCP or 443/TCP - TSL/SSL configured) on an IP address
- Management is about determining access, and how requests are routed, and demand managed.

## Ensure network connectivity
Tips:
- Ping the server
- Reliable network connection
- Static IP - people are services won't find it consistently
  - Change DNS record for the site, etc, instead Dynamic DNS
- Port 80 and 443 are open and unobstructed
- Make sure system is always available
