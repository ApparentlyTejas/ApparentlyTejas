<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,18&height=220&section=header&text=Hey,%20I'm%20Tejas&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20%7C%20Systems%20that%20have%20to%20actually%20hold%20up&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/ApparentlyTejas/incident-lens">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Python+%2B+FastAPI+%2B+PostgreSQL;Finding+race+conditions+under+real+load;Building+MCP+servers+that+cite+their+evidence;Currently+shipping+Incident+Lens" alt="Typing SVG" />
</a>

<br/>

[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tejas.malhotra.14@gmail.com)
[![GitHub](https://img.shields.io/badge/-ApparentlyTejas-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ApparentlyTejas)

</div>

<br/>

### What I build

I like backend systems that have to actually hold up under load, not just demo well:
APIs with real concurrency, databases pushed to the row counts where the easy queries stop
being fast, and tools that tell you what broke instead of just that something did.

- 🧪 I test things by actually breaking them — race conditions under real concurrent load, clean-checkout runs, chasing down query-planner behavior instead of trusting the first benchmark number.
- 🛠️ Comfortable across the stack: FastAPI/Flask APIs, AI/MCP integrations, AWS deployments (EKS, multi-tier web apps), and systems-level work in C++.

<br/>

### Tech

<p>
<img src="https://skillicons.dev/icons?i=python,fastapi,flask,postgres,docker,aws,ts,react,cpp,git" />
</p>

<br/>

### Featured projects

<table width="100%">
<tr>
<td width="50%" valign="top">

**[incident-lens](https://github.com/ApparentlyTejas/incident-lens)**

Role-aware, evidence-backed MCP server over BGL and OpenStack logs in SereneDB — every answer cites a tamper-evident, hash-chained audit entry, ranks failure patterns by concentration rather than raw frequency, and queries a billion-row remote Parquet file over S3 with zero download.

`Python` `MCP` `PostgreSQL`

</td>
<td width="50%" valign="top">

**[RoomLock](https://github.com/ApparentlyTejas/RoomLock)**

Concurrency-safe room-booking API: found a real double-booking race under load, fixed it two different ways (row lock, then a Postgres exclusion constraint), and load-tested both to compare correctness and throughput before picking one.

`Python` `PostgreSQL` `Concurrency`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[DevPulse](https://github.com/ApparentlyTejas/DevPulse)**

AI-powered engineering-ops platform: centralizes service monitoring, metrics and incident management, and exposes the whole thing to Claude via MCP. Async FastAPI + SQLAlchemy 2.0, Postgres + pgvector, Redis, background job scheduling.

`FastAPI` `MCP` `pgvector` `Redis`

</td>
<td width="50%" valign="top">

**[ReviewLenzAI](https://reviewlenzai.vercel.app)**

AI-powered GitHub pull-request reviewer — sign in with GitHub or Google, browse your repos, pick a PR, get structured findings ranked by severity. Deployed and live, not just a repo.

`FastAPI` `React` `TypeScript`

</td>
</tr>
</table>

<br/>

<div align="center">

<img src="https://raw.githubusercontent.com/ApparentlyTejas/ApparentlyTejas/output/github-contribution-grid-snake.svg" width="100%" alt="contribution snake"/>

</div>
