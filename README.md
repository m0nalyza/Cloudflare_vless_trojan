# Cloudflare-workers/pages proxy script

Support workers deployment, implement vless+ws+tls、trojan+ws+tls、vless+ws、trojan+ws proxy node

Support pages deployment, implement vless+ws+tls、trojan+ws+tls proxy node

--------------------------------

## ：CF Vless node can be customized content

#### Can modify Vless_workers_pages file_worker.js file

1.UUID must be customized (line 7)

2. If you cannot access CF websites or ChatGPT, it means that the ProxyIP is invalid. You can replace the ProxyIP and customize it (line 9)

3. The disguised web page is currently left blank and displays the 400 Bad Request interface, which can be customized (line 10)

#### You can also use variable settings in the CF-workers/pages interface. Note: The variable setting results will overwrite the local modification results.
| Variable function | Variable name | Variable value requirements | Variable default value |
| :--- | :--- | :--- | :--- |
| 1. Necessary uuid | uuid | Comply with uuid specified format | Ten thousand people ride uuid: 77a571fb-4fd2-4b37-8596-1b7d9728bb5c|
| 2. Can access CF websites | proxyip |ipv4 address, domain name, [ipv6 address]|proxyip domain name: cdn.xn--b6gac.eu.org|

----------------------------------

## 2: Customizable content of CF Trojan node

#### The _worker.js file under the Trojan_workers_pages file can be modified

1. The password must be customized (line 4)

2. If you cannot access CF websites or ChatGPT, it means that the ProxyIP is invalid. You can replace the ProxyIP and customize it (line 5)

3. The disguised webpage is currently left blank and displays the 400 Bad Request interface, which can be customized (line 6)

#### You can also use variable settings in the CF-workers/pages interface. Note: The variable setting results will overwrite the local modification results.
| Variable function | Variable name | Variable value requirements | Variable default value |
| :--- | :--- | :--- | :--- |
| 1. Necessary password | pswd | Any character | Thousands of people riding password: trojan |
| 2. Can access CF websites | proxyip |ipv4 address, domain name, [ipv6 address]|proxyip domain name: cdn.xn--b6gac.eu.org|

----------------------------------
## Three: View related sharing links (single node, non-subscription)
#### CF Vless share link, enter on the webpage: https:// workers domain name or pages domain name or custom domain name/custom uuid
#### CF Trojan share link, enter on the webpage: https:// workers domain name or pages domain name or custom domain name/custom password

#### Notice: 

Because the workers domain name has been blocked by TLS across the entire network, and the pages domain name has been blocked by China Mobile TLS (the proxy client can be immune to blocking by turning on the slicing function)

Therefore, you need to use a custom domain name or be in a proxy environment to view the shared link.

If you watch the tutorial, you can create countless preferred IP nodes without buying domain names or sharing links.

When the client does not support the slicing function, it is recommended to use a TLS-enabled node or a custom domain node for the worker domain name node.

### For related instructions and points of attention, please check [Yongge’s blog and video tutorial](https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html)

### Video tutorial:

[CF Workers Permanent Free Vless Node Building Tutorial (1): The first demonstration of the IP jumping phenomenon on the entire network, decrypting the usage skills of the two major nodes, and explaining the advantages and disadvantages of preferred IP and preferred domain names] (https://youtu.be/9V9CQxmfwoA)

[CF workers permanent free vless node construction tutorial (2): One-click script release of preferred anti-generation IP, pages deployment tutorial, multi-platform client setting instructions, exclusive discussion of sensitive security issues of CF free agent] (https://youtu.be /McdRoLZeTqg)

[CF Workers Permanent Free Trojan Node Building Tutorial (3): No need to customize domain names, workers and pages are two options to deploy preferred IP nodes; Comparison summary between CF Trojan and CF Vless; How to treat Trojan being recognized](https://youtu.be /lmhhL8M1k0I)

[Live broadcast selection review: Four major features of CF workers vless free nodes, the problem of nodes being blocked] (https://youtu.be/9OHGpWlfdJ0)

[ClouDNS permanent free domain name final tutorial (3): CF pages vless custom domain name direct deployment] (https://youtu.be/PN0BLANXh4I)

----------------------------------
----------------------------------
----------------------------------
----------------------------------
# Preferred domain name, preferred official IP + reverse IP one-click script:

### CF-CDN prefers domain name scripts from major public manufacturers, specifically for Apple Android phones and tablets (please refer to the tutorial to run in a local network environment):
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/CFcdnym.sh -o CFcdnym.sh && chmod +x CFcdnym.sh && bash CFcdnym.sh
```
-------------------------------------------------- -----------------------
### CF-Preferred official IP + reverse IP two-in-one script, dedicated to Apple Android phones and tablets (please refer to the tutorial to run in the local network environment):
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/cfip.sh -o cfip.sh && chmod +x cfip.sh && bash cfip.sh
```

-------------------------------------------------- ----------

### Communication platform: [Brother Yong’s blog address](https://ygkkk.blogspot.com), [Brother Yong’s YouTube channel](https://www.youtube.com/@ygkkk), [Brother Yong’s TG telegram Group](https://t.me/+jZHc6-A-1QQ5ZGVl), [Yongge TG Telegram Channel](https://t.me/+DkC9ZZUgEFQzMTZl)

-------------------------------------------------- ----------
### Thank you for the star in the upper right corner🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/Cloudflare-workers-pages-vless.svg)](https://starchart.cc/yonggekkk/Cloudflare-workers-pages-vless)
-------------------------------------------------- -----------------------
### Code source: [ca110us](https://github.com/ca110us/epeius), [emn178](https://github.com/emn178/js-sha256/blob/master/src/sha256.js ), [3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel), [badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest), [XIU2](https://github. com/XIU2/CloudflareSpeedTest)

### Statement: All codes come from the Github community and are integrated through ChatGPT
