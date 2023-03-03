# honeypot

## Description
We publish the IoCs collected by our honeypots as CSV.  
This list will be updated daily.

## File contents
### IP list
We aggregated requests exploiting known vulnerabilities and listed the attacking IPs.  
The list contains the following information.  
* first_seen: Date of first observation of IP
* ip: Attacker IP
* cve_id: Exploited CVE

### URL list
We aggregated the logs of attackers' attempts to acquire files externally, such as wget and curl, and listed the URLs accessed.  
If you access the link destination, you may be infected with malware, so please handle it with care.  
The list contains the following information.  
* first_seen: Date of first observation of URL
* url: Download destination URL

## Contact
Follow us on Twitter: 
[@cgj_yatagarasu](https://twitter.com/cgj_yatagarasu)
  
About: 
[Next Generation Security Technology Laboratory of LAC Co., Ltd.](https://www.lac.co.jp/corporate/unit/cyber_grid_japan.html)
