# toriptables2
Tor Iptables script is an anonymizer that sets up iptables and tor to route all services and traffic including DNS through the tor network.

####Dependencies:
tor

####Usage:
```python
toriptables2.py -h
```
####To test:
* [What is my IP address](http://whatismyipaddress.com)
* [Check Tor Project](https://check.torproject.org)
* [Witch proxy checker](http://witch.valdikss.org.ru)
* [IP leak test](http://www.doileak.com/)
* [DNS leak test](http://dnsleaktest.com)
* [What every Browser knows about you](http://webkay.robinlinus.com/)


####To change IP w/o reload:
#####Refresh Check Tor project webpage
```bash
sudo kill -HUP $(pidof tor)
```

#### Screenshots:
* [BackBox Linux](https://drive.google.com/open?id=0B79r4wTVj-CZQ1ZBeG0xdHFiN0k)

* [Parrot Security OS](http://bit.ly/2b6IjNP)

* [Kali Linux, Rolling Edition](http://bit.ly/1otCXOn)

* [Tor IPTables rules loaded](http://bit.ly/1NjmDLn)

---
##[toriptables2g for GUI Desktop with notification](https://bitbucket.org/ruped24/toriptables2g/src)
####Dependencies:
tor python-notify

#### Screenshot:
* [Tor Iptables2G with desktop notification](http://bit.ly/2bJO9WA)


###Distro Specific Fix:
* [Parrot Security OS 3.1.1 Anonsurf](https://www.inforge.net/xi/threads/parrot-security-os-3-1-1-anonsurf-fix-tor-by-vap0r.457379/) *Note: Translation needed*
