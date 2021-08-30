

# OSINT Encyclopedia
#### Credit: [Cham423](https://github.com/cham423) 

This checklist is designed to increase the success of your open-source intelligence (OSINT) operations by collecting a comprehensive list of information about your target. Understanding the fundamentals of OSINT is a prerequisite to using this checklist, as detailed technical operations will not be captured here. This list will be a working document that is driven by the community and maintained by Optiv.


## OSINT Checklist for ALL Engagements

- [ ]  Social Media
    - [ ]  Corporate/Busniess Controlled Content
        - [ ]  LinkedIn
        - [ ]  Facebook
        - [ ]  Instagram
    - [ ]  Employee Controlled Content
        - [ ]  Instagram facility analysis
        - [ ]  Instagram hashtag review
- [ ]  Office 365
    - [ ]  getuserrealm.srf
- [ ]  DNS
    - [ ]  dnsdumpster
    - [ ]  amass
    - [ ]  horizontal (other domains owned by the same entity) and vertical (subdomain) domain enumeration
        - [ ]  viewdns
        - [ ]  whoisxmlapi domain research suite
        - [ ]  riskiq
- [ ]  Host Enumeration
    - [ ]  WHOIS
    - [ ]  shodan
    - [ ]  censys
    - [ ]  spyse
- [ ]  Domain flyovers
    - [ ]  aquatone
- [ ]  Document Metadata Analysis
    - [ ]  pull large sites from google/aquatone report
    - [ ]  pymeta
    - [ ]  pull down manually



## Meta Sites

The following links are additional lists and frameworks that can assist while performing OSINT.

- [https://osintframework.com/](https://osintframework.com/)
    - Provides an interactive chart of actions with links for each action
    - Links to tools and third party sites


## Mail Blacklist Check

The following services allow you to check whether a  domain or IP address is present on several blacklists. Additionally, this can help troubleshoot email delivery issues while performing phishing campaigns.

- [https://mxtoolbox.com/blacklists.aspx](https://mxtoolbox.com/blacklists.aspx)

## WHOIS

[https://whois.arin.net/ui/advanced.jsp](https://whois.arin.net/ui/advanced.jsp)

- Primary source
- Manual web browsing

https://viewdns.info/

- Multiple tools

[https://domainbigdata.com/](https://domainbigdata.com/)

- Allows host correlation based on site registrant
- Third-party

[https://whoisology.com/#advanced](https://whoisology.com/#advanced)

- Reverse WHOIS search based on multiple parameters
- Third-party

[https://whoisfreaks.com/pricing/whois-database.html](https://whoisfreaks.com/pricing/whois-database.html)

[https://www.whoisxmlapi.com/](https://www.whoisxmlapi.com/)

- Largest dataset available (800M+ domains)
- $24,000 per year for full access to current and historical WHOIS data (for commercial license)
- Has an API with many functions that is more affordable than the commercial license
- Free license allows for 500 queries per month

## Domains

[https://domains-monitor.com/](https://domains-monitor.com/)

- Allows downloading a raw list of all registered domains in all zones
- Updates quarterly with updated/deleted domains
- Provides list of registration emails
- $90 per year for access

[https://networksdb.io/](https://networksdb.io/)

[https://www.expireddomains.net/](https://www.expireddomains.net/)

- Monitors and lists domains that are expiring
- Includes alexa rank and [archive.org](http://archive.org) details for domains, allowing users to select valuable domains
- Free to signup

## DNS


https://dnsdumpster.com/

[https://www.robtex.com/](https://www.robtex.com/dns-lookup/optiv.com)

## Website Lookup

- [https://website.informer.com/](https://website.informer.com/optiv.com)
    - Gives generalized information about a website and a screenshot of the homepage. daily visitors, hosting info, alexa ranking
    - Paywall: no
    - Bot Detection: unknown
- [https://archive.ph/](https://archive.ph/)
    - Allows snapshotting of a webpage by providing a URL. also allows retrieving screenshots and text data from previously archived sites
    - Similar to wayback machine
    - Paywall: no
    - Bot Detection: unknown
- [https://www.page2images.com/URL-Live-Website-Screenshot-Generator](https://www.page2images.com/URL-Live-Website-Screenshot-Generator)
    - Generates screenshots of urls, 15 seconds or more per url
    - No cost solution
    - Bot detection: unknown

## Phishing Site Lookup

- [https://www.phishtank.com/](https://www.phishtank.com/)
    - Crowdsourced link submission and verification allows the community to determine phish validity 
    - Limited reliability and visibility into anything more than the URL of a potential phishing site
    - Indicates whether site is online or offline
    - No cost solutions
    - API: yes, email verification required. commercial use allowed, has per hour request limit
    - Bot detection: hCaptcha (website)
- [https://openphish.com/](https://openphish.com/)
    - Raw feed of phishing urls
        - Free version updates every 12 hours, in text file format
        - Paid version updates more quickly and allows multiple formats (CSV or JSON)
    - Has IP address listing of recent phishing site
    - Provides global statistics of phishing attacks
        - What brands are being spoofed
        - What ASNs are most commonly hosting phishing attacks

    ## Twitter

    [https://tinfoleak.com/](https://tinfoleak.com/)

    - Shows devices, locations, etc. for a given Twitter handle
    - Requires email registration
    - Slow and requires capcha submitted for each request
    - No bulk capabilities

    ## Phone Number Validation

    [https://phonevalidator.com/phone-validator-api.aspx](https://phonevalidator.com/phone-validator-api.aspx)

    - Shows phone number type (CELL PHONE, LANDLINE, VOIP, TOLL-FREE or UNKNOWN)
    - 0.004 per number pricing ($4 per 1000 phone numbers)
    - Useful for smishing to confirm that you can text a phone number

    ## Corporate Databases

    [https://opencorporates.com/](https://opencorporates.com/)

    - Registration/incorporation articles for corporate entities
    - Shows registered trademarks, logos, and historical data
    - Shows branch locations
    - Can search by officer (person) as well to expand based on company involvement

    ## Github

    [https://github.com/BishopFox/GitGot](https://github.com/BishopFox/GitGot)

    - Searches github for potentially sensitive info
    - Semi-interactive, prompts user to manually review then enumerates based on feedback
    - Python, last commit Sep 2020

    ## Mobile Emulators

    [https://www.genymotion.com/](https://www.genymotion.com/)

    - SaaS based mobile emulator
    - Pay as you go
    - Focused around app testing

## Paywalled

- http://www.domaincrawler.com/


## Search engines:

- Yandex - Russian google
- Baidu - Chinese google
- Goo - Japanese google
- 2lingual.com - Can query search engines in two languages at a time, results are displayed side-by-side

