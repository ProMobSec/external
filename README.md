# subdomain enumeration
#### hackertarget
> Domain Profiler
#### shodan.io
> search org:"***[ORG NAME]***"  
> search domain:"***[TARGET DOMAIN]***
#### assetfinder
> assetfinder ***[TARGET DOMAIN]***  
#### dnsenum
> dnsenum ***[TARGET DOMAIN]***  
#### sublist3r
> python3 sublist3r.py -d ***[TARGET DOMAIN]***
#### censys.io
> search.censys.io
# org mapping
#### crosslinked
> python3 crosslinked.py -f '{first}.{last}@domain.com' ***[ORG NAME]***
#### dorks
> site:"linkedin.com" "***[ORG NAME]***"  
#### leaks
> dehashed  
> snusbase  
# vuln scanning
#### nessus
#### hackertarget
> OpenVAS
# password attacks
#### trevorspray
trevorspray -u ***bob@evilcorp.com*** -p ***'Welcome123'*** --delay ***5***
#### hydra
hydra -L users.txt -P ***wordlist.txt*** ssh://***target host***
# infrastructure
### hosting/services
> digital ocean  
> amazon  
> mailgun  
### servers
> evilnginx2  
> gophish  
