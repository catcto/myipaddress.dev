# myipaddress-web
The best tool to find your own IP address, and information about it.

## Usage

```
$ curl myipaddress.dev 
127.0.0.1

$ curl myipaddress.dev/country
United States

$ curl myipaddress.dev/country-iso
Mountain View

$ curl myipaddress.dev/city
Bornyasherk

$ curl myipaddress.dev/asn
AS15169

$ curl myipaddress.dev/json
{
  "ip": "8.8.8.8",
  "ip_decimal": 134744072,
  "country": "United States",
  "country_iso": "US",
  "country_eu": false,
  "latitude": 37.751,
  "longitude": -97.822,
  "time_zone": "America/Chicago",
  "asn": "AS15169",
  "asn_org": "GOOGLE",
  "hostname": "dns.google",
  "user_agent": {
    "product": "curl",
    "version": "7.79.1",
    "raw_value": "curl/7.79.1"
  }
}
```
