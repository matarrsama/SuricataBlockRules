# Suricata Social Media Block Rules

This repository contains Suricata rules to block access to various social media platforms. These rules are designed to prevent access via DNS, TLS SNI, HTTP host headers, and IP ranges associated with the respective services.

## Blocked Platforms
- Facebook
- Instagram
- Messenger
- YouTube
- TikTok
- Snapchat
- Likee

## Features
- Blocks domains using TLS SNI (for HTTPS traffic)
- Blocks domains using HTTP host headers
- Blocks IP ranges associated with social media services
- Blocks DNS requests to social media domains
- Prevents bypassing via public DNS-over-HTTPS (DoH) servers

## Usage
1. Upload the provided rule file to a location accessible by Suricata.
2. Add the URL to the rules list in Suricata.
3. Restart Suricata to apply the new rules.

## Disclaimer
These rules may need periodic updates as services change their domain structures and IP ranges. It is recommended to monitor logs and make adjustments accordingly.

