# nmap Links
Source: https://hakin9.org/nmap-a-hacker-tool-for-security-professionals/

# t_security
Source: https://justhackerthings.com/post/using-tor-from-the-command-line/
#### Installation
* sudo apt-get install tor
* edit /etc/tor/torrc
* uncomment #ControlPort 9051
* uncomment #CookieAuthentication 1 and set it to 0
* sudo /etc/init.d/tor restart
* curl ifconfig.me
* torify curl ifconfig.me 2>/dev/null
+ new IP Adress: echo -e 'AUTHENTICATE ""\r\nsignal NEWNYM\r\nQUIT' | nc 127.0.0.1 9051
