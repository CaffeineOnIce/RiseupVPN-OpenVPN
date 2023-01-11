# RiseupVPN - OpenVPN

Bash script to generate OpenVPN config file for [RiseupVPN](https://riseup.net/en/vpn)

## Usage

```bash
# Generate new conf and client certs
./generate.sh

# Connect to RiseupVPN
sudo openvpn --config riseup.ovpn.conf

# Check your ip address
curl ipinfo.io
```

## What is RiseupVPN ?

A free (funded through donations) and privacy oriented VPN.

> <https://riseup.net/en/vpn>

```text
>> Riseup offers Personal VPN service for censorship circumvention, location anonymization and traffic encryption.

>> Unlike most other VPN providers, Riseup does not log your IP address.

>> The RiseupVPN service is entirely funded through donations from users.
```

> <https://riseup.net/en/privacy-policy>

```text
>> No IP addresses of any user for any service are retained.
```

> <https://riseup.net/en/about-us/policy/government-faq>

```text
>> We are not working with any government agency. We have never simply handed over information when requested, and for years have had a no logging policy. We have fought and won every time anyone has tried to get us to give up information. We have never turned over any user data to any third party, fourth party, fifth party or any party.

>> This (take Riseup's servers) usually happens when they (law enforcement) want logs, we tell them that we don’t have any and then they come and take the machine because they don’t believe us and want to see for themselves. However, all of our servers use full disk encryption, which means they cannot see or do anything with the data on the disks without the keys. Nevertheless, we do not keep IP identifying logs, and store as little data as possible on our users.
```

## References

- <https://riseup.net/en/vpn>
- <https://riseup.net/en/privacy-policy>
- <https://riseup.net/en/about-us/policy/government-faq>
- <https://gist.github.com/crass/7952d79b596a89e067292ea68e3f0754>
- <https://openvpn.net/community-resources/reference-manual-for-openvpn-2-4/>
