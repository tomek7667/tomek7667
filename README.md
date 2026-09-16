<p align="center">
  <img src="https://raw.githubusercontent.com/tomek7667/tomek7667/main/assets/header.svg" alt="tomek7667 — Security Engineer & CTF Player" width="880"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/tomek7667/tomek7667/main/assets/now.svg" alt="now" width="720"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/Gda%C5%84sk-PL-555555?style=flat" height="22"/>
</p>

---

Senior software engineer in Gdańsk and a cybersecurity enthusiast. I play CTFs with
**[justCatTheFish](https://ctftime.org/team/33893)**, write the solutions up at
**[cyber-man.pl](https://cyber-man.pl)** so I actually remember them, and spend the rest
of the time building small Go services that run on a Raspberry Pi and do not need a
runtime, a container registry or my attention.

Most of what I publish is not a framework. It is the library I got tired of rewriting for
the fourth private project, or the tool that existed but wanted an account first.

I love Go &lt;3. Single binary, cross-compile, `go install`, done.

### Stack

Day to day:

- **Go** — HTTP services, CLIs, libraries; almost everything self-hosted I run
- **TypeScript** — frontends and the odd API when the ecosystem is worth it
- **Python** — CTF tooling, crypto scripting, Burp extensions
- **SQLite** — when a service genuinely does not need a database server
- **Docker, systemd, Cloudflare, Grafana Loki** for the layer underneath

Security side:

- Web, crypto and misc are where I am most comfortable; rev and pwn I keep working on
- Burp Suite, and writing my own extensions when the workflow does not fit
- Building CTF infrastructure as often as I break it — CTFd challenges, platform work

Opinions I hold quietly:

- If a tool needs an account before it does anything, I will write my own
- A library used by one person is still worth a README and a tagged version
- Writing up the solve is half the learning; skipping it wastes the whole night
- `ENV`-configured, stdout-logged, one binary — the deployment story should be boring

### Projects

**[secrets](https://github.com/tomek7667/secrets)** — self-hosted secrets management with
a web UI and a REST API. SQLite-backed single binary, multi-user with JWT, API tokens with
pattern-based permissions, and an audit log. Built because the hosted options all start at
"create an organisation".

**[openctf](https://github.com/tomek7667/openctf)** — an open-source alternative to
CTFtime, integrated with their results. Team claiming, event import, and a rating model
that separates *weight*, *difficulty* and *quality* instead of mashing them into one
number. Live at [openctf.cyber-man.pl](https://openctf.cyber-man.pl).

**[mcp-ctftime](https://github.com/tomek7667/mcp-ctftime)** — an MCP server wrapping the
public CTFtime API, so an assistant can look up events, teams, rankings and results
without me pasting JSON at it. On npm, `npx mcp-ctftime`.

**[bap](https://github.com/tomek7667/bap)** — *bump and push*. Git tag versioning as one
command, with a `-dry` flag for when you do not trust it yet. Written after the tenth time
I typed the tag by hand and got the patch number wrong.

**[gotransaction](https://github.com/tomek7667/gotransaction)** — universal transactions
with custom rollback, for the case SQL transactions do not cover: three clients already
committed and the fourth one errored.

**[go-multi-logger-slog](https://github.com/tomek7667/go-multi-logger-slog)** — an
env-configured `slog` handler. Ships JSON to Grafana Loki when the endpoint is set,
falls back to readable `tint` output on stdout when it is not.

**[links](https://github.com/tomek7667/links)** — a tiny link directory and resource
monitor for the services on my Raspberry Pi. Self-updating binary, JSON on disk, no
database. I open it far more often than I expected to.

**[Copy-Request](https://github.com/tomek7667/Copy-Request)** — Burp Suite extension that
copies a request as code in the language you actually want to write the exploit in.

**[ExtendedRandCrack](https://github.com/tomek7667/ExtendedRandCrack)** — `randcrack` with
the parts CTFs keep needing: offsetting into the Mersenne Twister state, and submitting
`getrandbits(64)` outputs.

Plus the small ones that keep the rest running:
[go-http-helpers](https://github.com/tomek7667/go-http-helpers) (CRUD, response logging
and JWT plumbing used in nearly all my private projects),
[goimail](https://github.com/tomek7667/goimail) (iCloud+ mail sending),
[orange-is-stupid](https://github.com/tomek7667/orange-is-stupid) (Cloudflare DDNS,
because my ISP will not sell a private person a static IP).

### Where I have been

- **justCatTheFish** — current CTF team
- **ECSC 2024**, Turin — Polish national team; Poland took 3rd place 🥉
- **153plus1 (2023)** — winning pair 🥇
- **pingCTF** — captain 2021–2023, and led the PING cybersecurity science club at Gdańsk Tech
- **Carrier** 2022–2025 — backend developer → tech lead → sr. assoc. software engineer
- **Gdańsk Tech** — BSc in Data Engineering; currently part-time CS master's

### What I am doing now

Writing up recent solves on the blog —
[0ctf 2025 *ezmd*](https://cyber-man.pl/0ctf-2025-ezmd-web),
[SECCON Quals *dummyhole*](https://cyber-man.pl/SECCON-Quals-2025-dummyhole-web),
[corCTF *control*](https://cyber-man.pl/corCTF-2025-control-misc),
[SekaiCTF *sekai-craft*](https://cyber-man.pl/SekaiCTF-sekaicraft-misc) — and starting a
write-up YouTube channel for the same reason I started the blog: explaining the solve is
what makes it stick. Still chipping away at openctf on the side.

### 📊 Activity

#### :computer: Last week coding activity
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

Open an issue on any of the repositories above — for anything about a specific repo, that
is the fastest way to reach me and it leaves the answer somewhere the next person can
find it.

Otherwise: [cyber-man.pl](https://cyber-man.pl) · [@_tomek7667](https://x.com/_tomek7667)

---

Gdańsk, PL · UTC+1/+2 · replies are usually same-day on weekdays, and whenever the CTF
ends at weekends.
