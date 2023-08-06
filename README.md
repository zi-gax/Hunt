<h1 align="center">
<a href="https://github.com/zi-gax/Hunt"><img src="https://github.com/zi-gax/zi-gax/assets/67065043/8c87a9a9-2d8d-442d-b5db-3e2dc607e046" width="300" height="100" alt="Hunt" /></a>
</h1>
<a href="https://github.com/zi-gax/Hunt">
<h3 align="center"> Smart Setup Bug Bounty Tools</h2></a></br>

<p align="center">With these tools you can install the bug bounty tools and checking updating</br> In all the linux distributions shown
</p>

<p align="center">
  <a href="https://github.com/zi-gax/Hunt">
    <img src="https://img.shields.io/badge/Arch-000000?style=for-the-badge&logo=archlinux&logoColor=1793D1" alt="Arch Linux">
  </a>
   <a href="https://github.com/zi-gax/Hunt">
    <img src="https://img.shields.io/badge/debian-000000?style=for-the-badge&logo=debian&logoColor=A81D33" alt="Debian">
  </a>
  <a href="https://github.com/zi-gax/Hunt">
      <img src="https://img.shields.io/badge/ubuntu-000000?style=for-the-badge&logo=ubuntu&logoColor=E95420" alt="Ubuntu">
  </a>
  <a href="https://github.com/zi-gax/Hunt">
      <img src="https://img.shields.io/badge/fedora-000000?style=for-the-badge&logo=fedora&logoColor=#51A2DA" alt="Fedora">
  </a>
</p>


## Installation 

<p>1-1 Run code as sudo</p>

```
bash <(curl -Ls https://raw.githubusercontent.com/zi-gax/Hunt/main/Setup/setup)
```
<p>OR</br></br>2-1 Clone this repo</p>

```
git clone https://github.com/zi-gax/Hunt.git
```
<p>2-2 Go to <b>Setup</b> directory and run setup</p>

```
cd Hunt/Setup && chmod +x setup && sudo ./setup
```
### Discord Webhook
<p>Send notification to discord when stup finished.</p>
<p>you can change webhook url in .webhook file in this path :</p>

```
Hunt/Setup/.webhook
```

## Setup tools list

### Subdomain Discovery

- [Subfinder](https://github.com/projectdiscovery/subfinder)
- [Amass](https://github.com/OWASP/Amass)
- [httpx](https://github.com/projectdiscovery/httpx)
- [Findomain](https://github.com/Findomain/Findomain)

### Network scanner

- [Naabu](https://github.com/projectdiscovery/naabu)
- [Masscan](https://github.com/robertdavidgraham/masscan)
- [Nmap](https://nmap.org/)</s>

### Content Discovery

- [ffuf](https://github.com/ffuf/ffuf)
- [Gospider](https://github.com/jaeles-project/gospider)
- [Katana](https://github.com/projectdiscovery/katana)
- [waybackurls](https://github.com/tomnomnom/waybackurls)
- [Kiterunner + API routes](https://github.com/assetnote/kiterunner)

### DNS Discovery

- [dnsx](https://github.com/projectdiscovery/dnsx)
- [MassDNS](https://github.com/blechschmidt/massdns)
- [PureDNS](https://github.com/d3mondev/puredns)
- [ShuffleDNS](https://github.com/projectdiscovery/shuffledns)
  
### Params Discovery

- [ParamSpider](https://github.com/devanshbatham/ParamSpider)
- [x8](https://github.com/jaeles-project/gospider)


### Bug Discovery

- [Nuclei](https://github.com/projectdiscovery/nuclei)
- <s>[SQLMap](https://github.com/sqlmapproject/sqlmap)</s> (soon)
- <s>[Dalfox](https://github.com/hahwul/dalfox)</s> (soon)
- <s>[WPscan](https://github.com/wpscanteam/wpscan)</s> (soon)

### CDN Discovery

- [Cut-CDN](https://github.com/ImAyrix/cut-cdn)

### Wordlists

- [SecLists](https://github.com/danielmiessler/SecLists)
- [Resolvers](https://github.com/trickest/resolvers)

### Useful tools

- [jq](https://github.com/stedolan/jq) 
- [Tmux](https://github.com/tmux/tmux)
- <s>[unfurl](https://github.com/tomnomnom/unfurl)</s> (soon)
