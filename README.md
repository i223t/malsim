# malsim
A script to simulate different kind of malicious network activity, like communication with well known malicious C2 servers, DNS-tunneling, etc.

How to run:
```
python3 malsim.py -m dnz_zone_transfer -r 192.168.0.167 -d hpbank.local
```

Available modules:
* cobaltstrike_dns_tunneling_staging
* cobaltstrike_dns_tunneling_beaconing
* kraken_dga
* kraken_ddns
* well_known_malicious_domains
* sinholed_domains
* dnz_zone_transfer

![Alt text](malsim.png?raw=true "malsim")
