# Xiaomi DNS Blocklist

In this repository you'll get updated blocklists and allowlists to minimize the collected data via DNS-Filtering (Tracking, Bloatware, (Personalized) Ads, Telemetry etc. and Allowlists for certain Apps or Firmware-Updates) on Xiaomi devices, including Redmi and POCO.

# Getting Started 
## PiHole

Simply add the raw list(s) in PiHole Settings/Blocklists and click save and update.

## NextDNS

Add the Native Tracking Protection Blocklist for Xiaomi under the Privacy Tab.
Add the Domains, listed under "Denylist" and "Allowlist" from [xiaomi-dns-blocklist/Xiaomi_NextDNS.txt](https://github.com/smokedzn/xiaomi-dns-blocklist/blob/master/Xiaomi_NextDNS.txt)

# Prerequisites
[NextDNS Setup](https://my.nextdns.io)

or

[PiHole Installation](https://docs.pi-hole.net/main/basic-install/)

# Lists

## `xiaomi_dns_block.lst`

Manually collected DNS entries from Xiaomi with the help of the community.

## `xiaomi_dns_whitelist.lst`

Manually collected DNS Whitelist entries from Xiaomi with the help of the community to improve compability. 

## `Xiaomi_NextDNS.txt`

Manually collected DNS entries for NextDNS (Allowlist and Denylist) 

# Whitelist

A collection of domains for the whitelist. These should be set manually as needed in NextDNS or PiHole. You can also just import the list `xiaomi_dns_whitelist.lst` **(PiHole only)**

## Xiaomi account management

```html
account.xiaomi.com
```

## System app updater

```html
global.market.xiaomi.com
```

## Find my Device

```html
us.find.api.micloud.xiaomi.net
account.xiaomi.com
find.api.micloud.xiaomi.net
```

## Updates of the Firmware

```html
update.miui.com
update.intl.miui.com
api.io.mi.com
```

## Mi Fitness (Compability for Mi Band Firmware and Watchfaces/Band Displays)
```html
mcc.intl.inf.miui.com
cdn.awsde0-fusion.fds.api.mi-img.com
```

# Built With

- With much love and manual collection of the DNS entries  ;)

# Authors

1. **unknownFalleN** - *Initial work and updates* - [unknownFalleN](https://github.com/unknownFalleN)
2. **smokedzn** - *Bugfixes and extended Updates* - [.smokedzn](https://github.com/smokedzn)

# License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/unknownFalleN/xiaomi-dns-blocklist/blob/master/LICENSE) file for details.

# Advice

No liability is assumed for completeness and/or correctness.
