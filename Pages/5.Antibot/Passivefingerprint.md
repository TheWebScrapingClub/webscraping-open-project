# Passive Fingerprinting

## What is Passive Fingerprinting?
Passive fingerprinting refers to the passive collection of attributes from a network-connecting client or server. In other words, the attributes sent when connecting to the target website determine a fingerprint. When this is compared to a database of "plausible" fingerprints, the target server can determine if the connection is trustworthy or not.
The difference between passive fingerprinting and active fingerprinting is that active fingerprinting sends data to "query" the client connecting while passive does not.

There are several layers of attributes that can be checked and for each one, there's a different technique:
- [TCP/IP Fingerprint](https://github.com/TheWebScrapingClub/webscraping-from-0-to-hero/blob/main/Pages/5.Antibot/TcpFingerprint.md)
- [TLS fingerprint](https://github.com/TheWebScrapingClub/webscraping-from-0-to-hero/blob/main/Pages/5.Antibot/TLSFingerprint.md)
- [HTTP Fingerprint](https://github.com/TheWebScrapingClub/webscraping-from-0-to-hero/blob/main/Pages/5.Antibot/HttpFingerprint.md)

## Possible solutions
Generally speaking, the passive fingerprinting techniques block the configuration "outliers", so using a plausible and real world setting in the scraper is the best way to avoid blocks.

### Reference and interesting links
[Akamai Whitepaper on passive fingerprinting](https://github.com/TheWebScrapingClub/webscraping-from-0-to-hero/blob/main/Pages/5.Antibot/Akamai_WP_Passive_Fingerprinting.pdf)

