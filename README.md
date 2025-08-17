# VPS-Bug-Bounty-Tools

Script that automates the installation of the main tools used for web application penetration testing and Bug Bounty.

## Usage:
```bash
sudo -s
wget https://go.dev/dl/go1.25.0.linux-amd64.tar.gz ~/Downloads/
cd ~/Downloads/
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.25.0.linux-amd64.tar.gz

cd /tmp && git clone https://github.com/roarnyg/VPS-Bug-Bounty-Tools
cd VPS-Bug-Bounty-Tools
chmod +x Tools-BugBounty-installer.sh
apt install dos2unix
apt install pip3
dos2unix Tools-BugBounty-installer.sh 
./Tools-BugBounty-installer.sh
```

 Installing Python,Ruby and some packages
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Package python is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source
However the following packages replace it:
  python-is-python3

Package python-setuptools is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source


Package python-pip is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source
However the following packages replace it:
  python3-pip
  

Package python-dev is not available, but is referred to by another package.
This may mean that the package is missing, has been obsoleted, or
is only available from another source
However the following packages replace it:
  python-dev-is-python3
  

E: Package 'python' has no installation candidate
E: Package 'python-pip' has no installation candidate
E: Unable to locate package python-dnspython
E: Package 'python-dev' has no installation candidate
E: Package 'python-setuptools' has no installation candidate

## Example during installation:
![Main Logo](images/tool.PNG 'Example')

# List of tools inserted:
## Network scanner:

- [Nmap](https://nmap.org/)
- [Masscan](https://github.com/robertdavidgraham/masscan)
- [Naabu](https://github.com/projectdiscovery/naabu)

## Subdomain Enumeration and DNS Resolver:

- [Massdns](https://github.com/blechschmidt/massdns)
- [Subfinder](https://github.com/projectdiscovery/subfinder/)
- [Knock](https://github.com/guelfoweb/knock.git)
- [Lazyrecon](https://github.com/nahamsec/lazyrecon.git)
- [Github-subdomains](https://github.com/gwen001/github-subdomains)
- [Sublist3r](https://github.com/aboul3la/Sublist3r.git)
- [Crtndstry](https://github.com/nahamsec/crtndstry.git)
- [Assetfinder](https://github.com/tomnomnom/assetfinder)
- [Dnsx](https://github.com/projectdiscovery/dnsx)
- [Dnsgen](https://github.com/ProjectAnte/dnsgen)

## Subdomain Takeovers:

- [SubOver](https://github.com/Ice3man543/SubOver)

## Web Fuzzer:

- [Dirsearch](https://github.com/maurosoria/dirsearch)
- [Ffuf](https://github.com/ffuf/ffuf)

## Wordlists:

- [SecLists](https://github.com/danielmiessler/SecLists.git)

## Scanner CMS:

- [Wpscan](https://github.com/wpscanteam/wpscan)
- [Droopescan](https://github.com/droope/droopescan)

## Vuln SQL:

- [SQLmap](https://sqlmap.org/)
- [NoSQLmap](https://github.com/codingo/NoSQLMap.git)
- [Jeeves](https://github.com/ferreiraklet/Jeeves)

## Enumeration Javascript:

- [LinkFinder](https://github.com/GerbenJavado/LinkFinder.git)
- [SecretFinder](https://github.com/m4ll0k/SecretFinder.git)
- [JSParser](https://github.com/nahamsec/JSParser.git)

## Visual Recon:

- [Aquatone](https://github.com/michenriksen/aquatone/releases/download/v1.7.0/aquatone_linux_amd64_1.7.0.zip)

## Crawling Web:

- [GoSpider](https://github.com/jaeles-project/gospider)
- [Hakrawler](https://github.com/hakluke/hakrawler)
- [Katana](https://github.com/projectdiscovery/katana)

## Vuln XSS:

- [XSStrike](https://github.com/s0md3v/XSStrike)
- [XSS-Loader](https://github.com/capture0x/XSS-LOADER/)
- [Freq](https://github.com/takshal/freq)
- [Gxss](https://github.com/KathanP19/Gxss)
- [Dalfox](https://github.com/hahwul/dalfox)

## Vuln SSRF:

- [SSRFmap](https://github.com/swisskyrepo/SSRFmap)
- [Gopherus](https://github.com/tarunkant/Gopherus.git)

## Vulnerability Scanner:

- [Nuclei](https://github.com/projectdiscovery/nuclei)

## Virtual Host Discovery:

- [Virtual host scanner](https://github.com/jobertabma/virtual-host-discovery.git)

## Useful Tools:

- [Anew](https://github.com/tomnomnom/anew)
- [Unew](https://github.com/dwisiswant0/unew)
- [Gf](https://github.com/tomnomnom/gf)
- [Httprobe](https://github.com/tomnomnom/httprobe)
- [Httpx](https://github.com/projectdiscovery/httpx/)
- [Waybackurls](https://github.com/tomnomnom/waybackurls)
- [Arjun](https://github.com/s0md3v/Arjun)
- [Gau](https://github.com/lc/gau)
- [GauPlus](https://github.com/bp0lr/gauplus)
- [Uro](https://github.com/s0md3v/uro)
- [Qsreplace](https://github.com/tomnomnom/qsreplace)
- [SocialHunter](https://github.com/utkusen/socialhunter)

# Update - Time Line:
- 28 September 2021: Inserted into the script the XSS-Loader tool.
- 10 November 2021: Inserted into the script the waybackurls tool.
- 22 November 2021: Inserted into the script the gau tool.
- 03 February 2022: Inserted into the script the unew,gf and SubOver tools.
- 19 March 2022: Inserted into the script the freq,qsreplace and uro tools.
- 10 April 2022: Inserted into the script the hakrawler and Jeeves.
- 20 April 2022: Inserted into the script the naabu tool.
- 15 November 2022: Inserted into the script the katana tool.
- 26 November 2022: Inserted into the script the Gxss and Dalfox tools
- 19 January 2023: Inserted into the script the socialhunter tool.
- 29 March 2024: Inserted into the script the gauplus tool.


