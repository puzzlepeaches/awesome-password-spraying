<h1 align="center">Awesome Password Spraying</h1>



<p align="center">
  View the README in Fullscreen for the best experience!
</p>
<p align="center">
  <a href="https://github.com/puzzlepeaches/awesome-password-spraying/blob/main/README.md">
    <img src="https://img.shields.io/badge/View-README-blue" alt="View README Fullscreen">
  </a>
</p>

A curated list of password spraying tools, projects, and resources. 

Note that this project primarily focuses on password-spraying tools and resources for Microsoft Office 365 and Azure Entra environments. Please help organize these resources so that they are easy for newcomers to find and understand. PRs are welcome and encouraged!

**Not all of the code in these frameworks has been audited for security or opsec. Use at your own risk. Always read code before you run it!**

---

<br>
<br>

## Cloud Enumeration

| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [Outsider_Recon](https://github.com/blacklanternsecurity/offensive-azure/tree/dev/offensive_azure/Outsider_Recon) | This module, a port of various cmdlets from AADInternals, requires only a domain to successfully enumerate information such as Tenant OpenID configuration, domain login information, domain details, Tenant ID, and other domains under the shared tenant. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/blacklanternsecurity/offensive-azure?style=for-the-badge&color=informational) |
| [succ](https://github.com/puzzlepeaches/succ) | succ is a simple command line tool that queries Microsoft for a list of domains associated with an Office 365 tenant. Find more domains to spray! | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/puzzlepeaches/succ?style=for-the-badge&color=informational) |
| [Invoke-AADIntReconAsOutsider](https://github.com/Gerenios/AADInternals/blob/master/KillChain.ps1) | A specific script from AADInternals for public enumeration. AADInternals is a collection of PowerShell scripts that can be used to perform reconnaissance and post-exploitation activities on Azure AD environments. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/Gerenios/AADInternals?style=for-the-badge&color=informational) |

<br>
<br>

## Username Enumeration

| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [linkedin2username](https://github.com/initstring/linkedin2username) | Generate username lists from LinkedIn. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/initstring/linkedin2username?style=for-the-badge&color=informational) |
| [o365enum](https://github.com/gremwell/o365enum) | Enumerate valid usernames from Office 365 using ActiveSync, Autodiscover, or office.com login page. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/gremwell/o365enum?style=for-the-badge&color=informational) |
| [onedrive_user_enum](https://github.com/nyxgeek/onedrive_user_enum) | enumerate valid onedrive users without authentication attempts | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/nyxgeek/onedrive_user_enum?style=for-the-badge&color=informational) |
| [TeamsUserEnum](https://github.com/immunIT/TeamsUserEnum) | Teams exposes a feature allowing to look for external users. It can be abused to enumerate internal users of the organization. | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/immunIT/TeamsUserEnum?style=for-the-badge&color=informational) |
| [Oh365UserFinder](https://github.com/dievus/Oh365UserFinder) | Oh365UserFinder is used for identifying valid o365 accounts and domains without the risk of account lockouts. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dievus/oh365userfinder?style=for-the-badge&color=informational) |

<br>
<br>

## Password Generation
| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [weakpasswords.net](https://weakpasswords.net/) | Automatically generated weak password API for password spraying. Built by nyxgeek. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/nyxgeek/weakpass_generator?style=for-the-badge&color=informational) |
| [pypassgen](https://github.com/puzzlepeaches/pypassgen) | A simple password generator CLI tool for password spraying. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/puzzlepeaches/pypassgen?style=for-the-badge&color=informational) |


<br>
<br>

### Spraying Tools

| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [spraycharles](https://github.com/Tw1sm/spraycharles) | Low and slow password spraying tool, designed to spray on an interval over a long period of time. Extensible with a plugin based framework that utilizes change instead of static indicators. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/Tw1sm/spraycharles?style=for-the-badge&color=informational) |
| [TeamFiltration](https://github.com/Flangvik/TeamFiltration) | TeamFiltration is a cross-platform framework for enumerating, spraying, exfiltrating, and backdooring O365 AAD accounts. Tons of features, could be in every catagory here really. | C# | ![GitHub Last Commit](https://img.shields.io/github/last-commit/Flangvik/TeamFiltration?style=for-the-badge&color=informational) |
| [CredMaster](https://github.com/knavesec/CredMaster) | Launch a password spray / brute force attach via Amazon AWS passthrough proxies, shifting the requesting IP address for every authentication attempt. This dynamically creates FireProx APIs for more evasive password sprays. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/knavesec/CredMaster?style=for-the-badge&color=informational) |
| [TREVORspray](https://github.com/blacklanternsecurity/TREVORspray) | TREVORspray is a modular password sprayer with threading, SSH proxying, loot modules, and more! One of the most fully featured tools on the market. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/blacklanternsecurity/TREVORspray?style=for-the-badge&color=informational) |
| [git-rotate](https://github.com/dunderhay/git-rotate) | Leveraging GitHub Actions for IP Rotation and O365 password spraying. Very unique technique with a complex setup. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dunderhay/git-rotate?style=for-the-badge&color=informational) |
| [Go365](https://github.com/optiv/Go365) | Go365 is a tool designed to perform user enumeration* and password guessing attacks on organizations that use Office365 (now/soon Microsoft365). Go365 uses a unique SOAP API endpoint on login.microsoftonline.com that most other tools do not use. | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/optiv/Go365?style=for-the-badge&color=informational) |
| [Spray365](https://github.com/MarkoH17/Spray365) | Spray365 is a password spraying tool designed for Microsoft accounts (Office 365/Azure AD) that distinguishes itself by using an "execution plan." Several evasion featuresand uses the adal library under the hood.  | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/MarkoH17/Spray365?style=for-the-badge&color=informational) |
| [RagingRotator](https://github.com/nickzer0/RagingRotator) | A tool for carrying out brute force attacks against Office 365, with built in IP rotation use AWS gateways. | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/nickzer0/RagingRotator?style=for-the-badge&color=informational) |
| [MSOLSpray](https://github.com/dafthack/MSOLSpray/) | MSOLSpray is a password spraying tool for Microsoft Online accounts (Azure/O365). One of the OG spraying tools. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dafthack/MSOLSpray?style=for-the-badge&color=informational) |
| [MSOLSpray.py](https://github.com/MartinIngesen/MSOLSpray) | MSOLSpray is a password spraying tool for Microsoft Online accounts (Azure/O365). Python port of dafthack's PowerShell MSOLSpray. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/MartinIngesen/MSOLSpray?style=for-the-badge&color=informational) |
| [Omnispray](https://github.com/0xZDH/Omnispray) | Omnispray aims to replace tools such as o365spray and provide a modular framework to expand enumeration and spraying beyond just a single target/application. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/0xZDH/Omnispray?style=for-the-badge&color=informational) |
| [Trident](https://github.com/praetorian-inc/trident) | Google cloud based password spraying tool for multiple IdPs. Such a great idea and architecure, but has since been archived. | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/praetorian-inc/trident?style=for-the-badge&color=informational) |
| [GoMapEnum](https://github.com/nodauf/GoMapEnum) | Another all in one framework for password spraying, enumeration, and more. | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/nodauf/GoMapEnum?style=for-the-badge&color=informational) |
| [SprayCannon](https://github.com/CausticKirbyZ/SprayCannon) | A really interesting and obscure password spraying framework written in...Crystal? | Crystal | ![GitHub Last Commit](https://img.shields.io/github/last-commit/CausticKirbyZ/SprayCannon?style=for-the-badge&color=informational) |
| [SprayingToolkit](https://github.com/byt3bl33d3r/SprayingToolkit) | A set of Python scripts/utilities that tries to make password spraying attacks against Lync/S4B & OWA a lot quicker, less painful and more efficient. (ARCHIVED) | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/byt3bl33d3r/SprayingToolkit?style=for-the-badge&color=informational) |
| [AzurePasswordSprayer](https://github.com/boringthegod/AzurePasswordSprayer) | Tool written in Rust to perform Password Spraying attacks against Azure/Office 365 accounts. It is multi threaded and makes no connection attempts. | Rust | ![GitHub Last Commit](https://img.shields.io/github/last-commit/boringthegod/AzurePasswordSprayer?style=for-the-badge&color=informational) |
| [SSOh-No](https://github.com/optionalCTF/SSOh-No) | This tool is designed to enumerate users, password spray and perform brute force attacks against any organisation that utilises Azure AD or O365.| Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/optionalCTF/SSOh-No?style=for-the-badge&color=informational) |


<br>
<br>


## Credential Abuse

| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [ROADTools](https://github.com/dirkjanm/ROADtools) | ROADtools is a framework to interact with Azure AD. It consists of a library (roadlib) with common components, the ROADrecon Azure AD exploration tool and the ROADtools Token eXchange (roadtx) tool. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dirkjanm/ROADtools?style=for-the-badge&color=informational) |
| [Azure-AD-Password-Checker](https://github.com/quahac/Azure-AD-Password-Checker) | Enumerate MFA configuration and other insecure accounts using a Roadrecon database. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/quahac/Azure-AD-Password-Checker?style=for-the-badge&color=informational) |
| [msspray](https://github.com/SecurityRiskAdvisors/msspray) | Enumerate where a user can log in without MFA. Sort of loud, but effective. I don't know why they archived this, it's great! | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/SecurityRiskAdvisors/msspray?style=for-the-badge&color=informational) |
| [TeamSniper](https://github.com/xRET2pwn/Teamsniper) | Teamsniper is a tool for fetching keywords in a Microsoft Teams such as (passwords, emails, database, etc.). | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/xRET2pwn/Teamsniper?style=for-the-badge&color=informational) |
| [MailSniper](https://github.com/dafthack/MailSniper) | MailSniper is a penetration testing tool for searching through email in a Microsoft Exchange and O365 environment for specific terms (passwords, insider intel, etc.). OG | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dafthack/MailSniper?style=for-the-badge&color=informational) |
| [MFade](https://github.com/ibaiC/MFade) | A python port of @dafthack's MFAsweep with some added OPSEC functionality. MFAde can be used to find single-factor authentication failure points in Mircrosoft Services.  | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/ibaiC/MFade?style=for-the-badge&color=informational) |
| [MFASweep](https://github.com/dafthack/MFASweep) | MFASweep is a PowerShell script that attempts to log in to various Microsoft services using a provided set of credentials and will attempt to identify if MFA is enabled. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dafthack/MFASweep?style=for-the-badge&color=informational) |
| [AzureHound](https://github.com/BloodHoundAD/AzureHound) | The BloodHound data collector for Microsoft Azure | Go | ![GitHub Last Commit](https://img.shields.io/github/last-commit/BloodHoundAD/AzureHound?style=for-the-badge&color=informational) |
| [BARK](https://github.com/BloodHoundAD/BARK) | BARK stands for BloodHound Attack Research Kit. It is a PowerShell script built to assist the BloodHound Enterprise team with researching and continuously validating abuse primitives. BARK currently focuses on Microsoft's Azure suite of products and services. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/BloodHoundAD/BARK?style=for-the-badge&color=informational) |
| [GraphRunner](https://github.com/dafthack/GraphRunner) | GraphRunner is a post-exploitation toolset for interacting with the Microsoft Graph API. It provides various tools for performing reconnaissance, persistence, and pillaging of data from a Microsoft Entra ID (Azure AD) account. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/dafthack/GraphRunner?style=for-the-badge&color=informational) |
| [offensive-azure](https://github.com/blacklanternsecurity/offensive-azure) | Collection of offensive tools targeting Microsoft Azure written in Python to be platform agnostic. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/blacklanternsecurity/offensive-azure?style=for-the-badge&color=informational) |
| [TokenTacticsV2](https://github.com/f-bader/TokenTacticsV2) | This is an updated version of TokenTactics originally written by Stephan Borosh @rvrsh3ll & Bobby Cooke @0xBoku. | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/f-bader/TokenTacticsV2?style=for-the-badge&color=informational) |
| [TokenTactics](https://github.com/rvrsh3ll/TokenTactics) | Azure JSON Web Token ("JWT") Manipulation Toolset | PowerShell | ![GitHub Last Commit](https://img.shields.io/github/last-commit/rvrsh3ll/TokenTactics?style=for-the-badge&color=informational) |
| [GraphSpy](https://github.com/RedByte1337/GraphSpy) | Very similar to GraphRunner, but written in Python with a few more features. Very awesome architecture with support for multiple databases. | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/RedByte1337/GraphSpy?style=for-the-badge&color=informational) |


<br>
<br>

## Resources
| Name | Description | Programming Language | Last Commit |
| --- | --- | --- | --- |
| [family-of-client-ids-research](https://github.com/secureworks/family-of-client-ids-research) | Research on undocumented functionality in Azure Active Directory allows a group of Microsoft OAuth client applications to obtain special “family refresh tokens,” which can be redeemed for bearer tokens as any other client in the family. i | Python | ![GitHub Last Commit](https://img.shields.io/github/last-commit/secureworks/family-of-client-ids-research?style=for-the-badge&color=informational) |
| [saas-attacks](https://github.com/pushsecurity/saas-attacks) | A collection of tools and resources for attacking SaaS platforms. | N/A | ![GitHub Last Commit](https://img.shields.io/github/last-commit/pushsecurity/saas-attacks?style=for-the-badge&color=informational) |
| [AAD Kill chain](https://aadinternals.com/aadkillchain/) | The Azure AD and Microsoft 365 kill chain is a collection of recon techniques and hacking tools discovered and documented by @DrAzureAD | N/A | N/A | 
| [Bypassing Conditional Access](https://aadinternals.com/post/mdm/) | A post by @DrAzureAD on bypassing conditional access policies in Azure AD by faking device compliance. | N/A | N/A |
| [dirkjanm.io](https://dirkjanm.io/) | Dirk-jan's blog with a ton of great resources on Azure AD and Microsoft 365. | N/A | N/A |
| [Okta for Red Teamers — Perimeter Edition](https://medium.com/nickvangilder/okta-for-red-teamers-perimeter-edition-c60cb8d53f23) | A blog post by @nickvangilder on attacking Okta. | N/A | N/A |
| [Hacking Cloud Tokens 2.0](https://www.trustedsec.com/blog/hacking-your-cloud-tokens-edition-2-0) | Using TokenTacticsV2 to attack Microsoft environments. | N/A | N/A |

