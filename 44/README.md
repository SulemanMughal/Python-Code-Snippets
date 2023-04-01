# Extended IP address info

View extended info about your public IP address from the terminal.


The python script runs `curl` with the following parameters

    curl -H "Accept: application/json" [https://ipinfo.io/json] (https://ipinfo.io/json)



#### Libraries Required

-   pycurl
-   certifi
-   io



#### Output


```
{
    "ip": "xxx.xxx.xxx.xxx",
    "city": "A_city",
    "hostname": "host.isp-website.com",
    "region": "A_region",
    "country": "Country code",
    "loc": "coordinates",
    "org": "AS-number ISP-name",
    "postal": "postal-code",
    "timezone": "Europe/City",
    "readme": "https://ipinfo.io/missingauth"
}
```