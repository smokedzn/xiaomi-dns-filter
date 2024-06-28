# Xiaomi DNS Blocklist/Whitelist

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

## `xiaomi_pihole_block.lst`

Manually collected DNS entries, in _combination_ with parts of the following Blocklists: 
- __[HaGeZi's - Multi PRO++ Blocklist](https://github.com/hagezi/dns-blocklists#proplus)__
- __[unknownFalleN's Xiaomi DNS Blocklist](https://github.com/unknownFalleN/xiaomi-dns-blocklist)__

## `xiaomi_pihole_allow.lst`

Self-tested collected DNS Whitelist entries to improve compability. 

## `Xiaomi_NextDNS.txt`
### Consider using [HaGeZi's - Multi PRO++](https://github.com/hagezi/dns-blocklists#proplus) and [unknownFalleN's Xiaomi DNS Blocklist](https://github.com/unknownFalleN/xiaomi-dns-blocklist) in combination with my Denylist/Allowlist instead of adding only all manual picked domains. For more information, [take a look](https://github.com/smokedzn/xiaomi-dns-blocklist/blob/master/Xiaomi_NextDNS.txt) at the Denylist.
Manually collected DNS entries, in _combination_ with parts of the following Blocklists: 
- __[HaGeZi's - Multi PRO++ Blocklist](https://github.com/hagezi/dns-blocklists#proplus)__
- __[unknownFalleN's Xiaomi DNS Blocklist](https://github.com/unknownFalleN/xiaomi-dns-blocklist)__

# Whitelist (Semi-Outdated)

A collection of domains for the whitelist. These should be set manually as needed in NextDNS or PiHole. You can also just import the list `xiaomi_pihole_allow.lst` **(PiHole only)**

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

# Special thanks to:

- [unknownFalleN](https://github.com/unknownFalleN)
- [HaGeZi](https://github.com/hagezi/)

# Authors

1. **unknownFalleN** - *Initial work and updates* - [unknownFalleN](https://github.com/unknownFalleN)
2. **smokedzn** - *Bugfixes and extended Updates* - [.smokedzn](https://github.com/smokedzn)

# License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/unknownFalleN/xiaomi-dns-blocklist/blob/master/LICENSE) file for details.

# Advice

No liability is assumed for completeness and/or correctness.
