<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=200&section=header&text=OFFA&fontSize=80&fontColor=00ff41&animation=fadeIn&fontAlignY=38&desc=Bug%20Bounty%20Hunter%20%7C%20Recon%20Specialist&descAlignY=60&descColor=36bcf5" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=22&pause=1000&color=00FF41&center=true&vCenter=true&multiline=false&repeat=true&width=600&lines=whoami+%3D%3D+Bug+Bounty+Hunter+%F0%9F%90%9B;grep+-r+%22vulnerabilities%22+%2Ftargets%2F;nmap+-sV+--script+vuln+target.com;ffuf+-w+wordlist.txt+-u+https%3A%2F%2FFUZZ.target.com" alt="Typing SVG" />
</a>

<br/>

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/)
[![HackerOne](https://img.shields.io/badge/HackerOne-%23494649.svg?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-%23F26822.svg?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/)

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> `cat /etc/offa/status.conf`

<img align="right" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzVlNmwxdDJ3MWcxeG9ocTIyczV2aG5tNW54eWwxM2psbzkxYTk4YiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Cfiid6I8YDKqrCxAaY/giphy.gif" width="220" />

```bash
$ ./offa --info

[+] Role      : Bug Bounty Hunter
[+] Focus     : Wide Scope Recon & Automation
[+] Hunting   : XSS | LFI | SSRF | IDOR | Misconfigs
[+] Platforms : HackerOne | Bugcrowd | Intigriti
[+] Goal      : Critical Findings & Full Attack Surface
[+] Status    : 🟢 ACTIVELY HUNTING

[*] "The wider the scope, the bigger the reward."
```

<br clear="right"/>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28"> `ls /skills/`

<div align="center">

### 💻 Languages
![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### 🖥️ Systems & Platforms
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### 🛠️ Daily Arsenal
![Nuclei](https://img.shields.io/badge/Nuclei-00d26a?style=for-the-badge&logo=buffer&logoColor=white)
![ffuf](https://img.shields.io/badge/ffuf-red?style=for-the-badge&logo=files&logoColor=white)
![Amass](https://img.shields.io/badge/Amass-blueviolet?style=for-the-badge&logo=amazon&logoColor=white)
![Shodan](https://img.shields.io/badge/Shodan-%23FF0000.svg?style=for-the-badge&logo=shodan&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)
![Subfinder](https://img.shields.io/badge/Subfinder-orange?style=for-the-badge&logo=search&logoColor=white)
![httpx](https://img.shields.io/badge/httpx-0075A2?style=for-the-badge&logo=go&logoColor=white)

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🎯 `cat /recon/methodology.txt`

```
┌──────────────────────────────────────────────────────┐
│              RECON WORKFLOW v2.0                      │
├──────────────────────────────────────────────────────┤
│  [1] Subdomain Enum    →  amass + subfinder + dnsx   │
│  [2] Port Scanning     →  naabu + nmap               │
│  [3] Web Probing       →  httpx + whatweb            │
│  [4] Fuzzing           →  ffuf + dirsearch           │
│  [5] Vuln Scanning     →  nuclei templates           │
│  [6] Manual Testing    →  Burp Suite + custom payloads│
│  [7] Report & Profit   →  💰 BOUNTY COLLECTED        │
└──────────────────────────────────────────────────────┘
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📊 `./stats --github --user OFFA1911`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=OFFA1911&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=36bcf5&text_color=ffffff&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OFFA1911&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=ffffff"/>

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=OFFA1911&theme=chartreuse-dark&hide_border=true&background=0d1117&stroke=00ff41&ring=36bcf5&fire=ff6b6b&currStreakLabel=00ff41&sideLabels=ffffff&dates=888888" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=OFFA1911&bg_color=0d1117&color=00ff41&line=36bcf5&point=ffffff&area=true&hide_border=true" />
</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🏆 `cat /achievements/trophies.log`

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=OFFA1911&theme=matrix&no-frame=true&no-bg=true&margin-w=4&row=1" />
</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🐍 `watch -n 1 git log --oneline`

<div align="center">
  <img src="https://raw.githubusercontent.com/OFFA1911/OFFA1911/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

> **Note:** لتفعيل الـ snake animation، اتبع التعليمات في الـ README بتاعي 👇

<details>
<summary><b>⚙️ إعداد Snake Animation</b></summary>

اعمل folder جديد `.github/workflows/` وحط فيه ملف `snake.yml`:

```yaml
name: Generate Snake
on:
  schedule: [{cron: "0 */12 * * *"}]
  workflow_dispatch:
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
</details>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=OFFA1911&label=Profile+Views&color=00ff41&style=for-the-badge" />

```
┌─────────────────────────────────────────┐
│   "Security is not a product,           │
│    but a process." — Bruce Schneier     │
│                                         │
│         Happy Hunting! 🐛💰             │
└─────────────────────────────────────────┘
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=100&section=footer"/>

</div>
