<p align="center">
  <img src="https://raw.githubusercontent.com/tomek7667/tomek7667/main/assets/header.svg" alt="tomek7667" width="880"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/tomek7667/tomek7667/main/assets/now.svg" alt="now" width="720"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" height="22"/>
</p>

---

Software engineer, cybersecurity enthusiast. I play CTFs with
[justCatTheFish](https://ctftime.org/team/33893) and write the solves up at
[cyber-man.pl](https://cyber-man.pl).

Go is my favourite. Single binary, cross compile, `go install`, done. Most of what
is here is either a library I got tired of rewriting for the next private project,
or a tool that already existed but wanted an account first.

### Stack

Go, TypeScript, Python, SQLite. Docker, systemd, Cloudflare, Grafana Loki underneath.
Burp Suite and my own extensions for the security side, mostly web, crypto and misc.

### Go libraries and tools

- [secrets](https://github.com/tomek7667/secrets) - self hosted secrets manager. SQLite, JWT auth, API tokens with pattern permissions, audit log, web UI.
- [links](https://github.com/tomek7667/links) - link directory and resource monitor for the services on my raspberry pi. Self updating binary, JSON on disk.
- [bap](https://github.com/tomek7667/bap) - bump and push. Git tag versioning in one command, with a dry run flag.
- [gotransaction](https://github.com/tomek7667/gotransaction) - transactions with custom rollback, for when three clients already committed and the fourth errored.
- [go-multi-logger-slog](https://github.com/tomek7667/go-multi-logger-slog) - env configured slog handler. JSON to Loki when the endpoint is set, readable tint output when it is not.
- [go-http-helpers](https://github.com/tomek7667/go-http-helpers) - CRUD, response logging and JWT plumbing used in nearly all my private projects.
- [goimail](https://github.com/tomek7667/goimail) - iCloud+ mail sending.
- [orange-is-stupid](https://github.com/tomek7667/orange-is-stupid) - Cloudflare dynamic DNS, because my ISP will not sell a private person a static IP.
- [Logo-Maker](https://github.com/tomek7667/Logo-Maker) - generates every icon size the App Store and Play Store ask for.
- [scaler](https://github.com/tomek7667/scaler) - small site showing different types of scales.
- [przepisy](https://github.com/tomek7667/przepisy) - mobile first recipe app with ranking.

### Security and CTF

- [Copy-Request](https://github.com/tomek7667/Copy-Request) - Burp extension that copies a request as code in the language you want to write the exploit in.
- [Burp-Export-History](https://github.com/tomek7667/Burp-Export-History) - Burp extension for exporting proxy history.
- [ExtendedRandCrack](https://github.com/tomek7667/ExtendedRandCrack) - randcrack with the parts CTFs keep needing: offsetting into the Mersenne Twister state, and `getrandbits(64)` outputs.
- [mcp-ctftime](https://github.com/tomek7667/mcp-ctftime) - MCP server over the CTFtime API. On npm, `npx mcp-ctftime`.
- [openctf](https://github.com/tomek7667/openctf) - open source alternative to CTFtime. Rates weight, difficulty and quality as separate metrics instead of one number. Not currently deployed.
- [mc-rce](https://github.com/tomek7667/mc-rce) - RCE PoC plugin for a Paper 1.20.2 Minecraft server.
- [PING-sandbox-escape](https://github.com/tomek7667/PING-sandbox-escape) - sandbox escape practice challenges from a talk I gave.
- [Race-Condition-Laboratory](https://github.com/tomek7667/Race-Condition-Laboratory) - practice targets for race conditions.
- [Password-Cracker](https://github.com/tomek7667/Password-Cracker) - distributed password cracking platform.
- [ctfd-challenges](https://github.com/tomek7667/ctfd-challenges) and [pingCTF-2022-files](https://github.com/tomek7667/pingCTF-2022-files) - challenges I wrote.

### Web and libraries

- [Human-Error-Calculator](https://github.com/tomek7667/Human-Error-Calculator) - probability of human error using the TESEO method. Live at [hec.cyber-man.pl](https://hec.cyber-man.pl).
- [gpt-programmer](https://github.com/tomek7667/gpt-programmer) - API giving LLMs the ability to create whole projects and browse.
- [pocketbase-utils](https://github.com/tomek7667/pocketbase-utils) - the utils PocketBase is missing.
- [Hebe-API-js](https://github.com/tomek7667/Hebe-API-js) / [Hebe-API-python](https://github.com/tomek7667/Hebe-API-python) and [Zacks-API](https://github.com/tomek7667/Zacks-API) - unofficial clients for services with no public API.
- [mi-bulb-homebridge](https://github.com/tomek7667/mi-bulb-homebridge) - Homebridge plugin for Mi bulbs, MJDPL04YL in particular.
- [biotech-js](https://github.com/tomek7667/biotech-js), [Splitter](https://github.com/tomek7667/Splitter), [extract-genes](https://github.com/tomek7667/extract-genes), [Blaster](https://github.com/tomek7667/Blaster) - bioinformatics file parsing, sequence splitting and organism prediction, from my time as a bioinformatician.
- [LeetTranslator](https://github.com/tomek7667/LeetTranslator) - leet to human text.

### Game mods and addons

- [speed-o-meter](https://github.com/tomek7667/speed-o-meter) - TurtleWoW addon measuring your speed.
- [Auction-Watch](https://github.com/tomek7667/Auction-Watch) - TurtleWoW auction house watcher.
- [PeggleTurtle](https://github.com/tomek7667/PeggleTurtle) / [BetterPeggle](https://github.com/tomek7667/BetterPeggle) - two attempts at Peggle inside WoW.
- [Messenger](https://github.com/tomek7667/Messenger) - Minecraft mod for automating messages on an interval.

### Coding activity

Updated daily from WakaTime, last 30 days.

<!--START_SECTION:waka-->

```txt
Total Time: 68 hrs 54 mins

Markdown                   27 hrs 9 mins         ███████▓░░░░░░░░░░░░░░░░░   30.54 %
Other                      20 hrs                █████▓░░░░░░░░░░░░░░░░░░░   22.50 %
Go                         8 hrs 40 mins         ██▒░░░░░░░░░░░░░░░░░░░░░░   09.75 %
TypeScript                 6 hrs 47 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   07.64 %
Python                     4 hrs 41 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   05.28 %
```

<!--END_SECTION:waka-->

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=tomek7667&show_icons=true&hide_border=true&theme=github_dark&icon_color=00ADD8&title_color=00ADD8"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs?username=tomek7667&layout=compact&hide_border=true&theme=github_dark&title_color=00ADD8"/>
</p>

### Contact

Open an issue on any of the repos above. For anything about a specific repo that is
the fastest way to reach me, and it leaves the answer where the next person can find it.

Otherwise: [cyber-man.pl](https://cyber-man.pl) or [@_tomek7667](https://x.com/_tomek7667).
