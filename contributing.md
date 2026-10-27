# 🇮🇳 India States & Districts Data

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,13,28&height=210&section=header&text=India%20States%20%26%20Districts&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Complete%2C%20Accurate%20%26%20Developer-Ready%20Dataset&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.3.0-FF9933?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Format](https://img.shields.io/badge/JSON%20%7C%20CSV%20%7C%20SQL%20%7C%20API-138808?style=for-the-badge&logo=json&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-CC--BY--4.0-000080?style=for-the-badge&logo=creativecommons&logoColor=white)](LICENSE)
[![Updated](https://img.shields.io/badge/updated-2026-FF9933?style=for-the-badge&logo=clockify&logoColor=white)](https://github.com)

<br/>

### 🗺️ The most complete, up-to-date dataset of Indian states, districts & subdivisions

*🕌 28 States • 🏛️ 8 UTs • 📍 780+ Districts • 🔄 Auto-Updated*

<br/>

<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_DATA-FF9933?style=for-the-badge&logo=download&logoColor=white&labelColor=CC6E1A" alt="Download Data" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/📚_API_DOCS-138808?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0B5A05" alt="API Docs" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/🧪_LIVE_DEMO-000080?style=for-the-badge&logo=googleplay&logoColor=white&labelColor=00004D" alt="Live Demo" height="45"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**India States & Districts Data** is a comprehensive, well-structured dataset covering all **28 states** and **8 Union Territories** of India, complete with their districts, subdivisions, and administrative metadata.

Whether you're building a **shipping calculator**, a **government form**, a **map visualization**, or a **data analytics dashboard** — this dataset gives you clean, reliable, and developer-friendly data out of the box.


<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 What's Included

<div align="center">

| 🏛️ **States & UTs** | 📍 **Districts** | 🗺️ **Subdivisions** |
|:---:|:---:|:---:|
| All 28 states +<br/>8 Union Territories | 780+ districts<br/>with official codes | Tehsils, talukas<br/>& blocks |

| 🌐 **Multiple Formats** | 🔤 **Localization** | 🔄 **Auto-Updates** |
|:---:|:---:|:---:|
| JSON, CSV, SQL,<br/>YAML & REST API | English + 22<br/>official languages | Weekly sync with<br/>official sources |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why Use This Dataset

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ✅ **Verified & Clean** | Every entry manually checked against official government records |
| 📦 **Multi-Format Ready** | Drop-in JSON, CSV, SQL & YAML — no conversion needed |
| 🚀 **Zero Dependencies** | Lightweight files, no external libraries required to use |
| 🌍 **Multi-Language** | State & district names in Hindi, Tamil, Bengali, Telugu & more |
| 🔄 **Always Current** | Automated weekly sync with Census & MHA data sources |
| 🛠️ **Developer-Friendly** | Well-documented schema, TypeScript types & Python models included |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Sample Data Preview

<div align="center">

```json
{
  "state": "Maharashtra",
  "state_code": "MH",
  "type": "state",
  "capital": "Mumbai",
  "region": "West",
  "districts": [
    { "name": "Mumbai City",   "code": "MH-01", "population": 3145876 },
    { "name": "Pune",          "code": "MH-25", "population": 9429408 },
    { "name": "Nagpur",        "code": "MH-19", "population": 4653570 },
    { "name": "Nashik",        "code": "MH-20", "population": 6107187 }
  ]
}
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🇮🇳 india-states-districts-data/
├── 📂 data/
│   ├── states.json            # All states & UTs
│   ├── districts.json         # Districts grouped by state
│   ├── states.csv             # Flat CSV for spreadsheets
│   ├── districts.sql          # Ready-to-import SQL dump
│   └── schema.json            # JSON Schema for validation
├── 🌐 api/                    # Optional REST API server
│   ├── server.py
│   └── endpoints.md
├── 🔤 i18n/                   # Translations (22 languages)
├── 🧪 tests/                  # Schema & integrity tests
└── 📖 docs/                   # Usage guides & examples
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found an error? Missing a district? Want to contribute a translation?

<div align="center">

<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-FF9933?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/JJhAzJjZdySrOiEJv">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-138808?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Attribution

Distributed under the **Creative Commons Attribution 4.0 (CC-BY-4.0)** License. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### ⭐ Made with 🇮🇳 by the India Data Team

*Using this dataset? A star helps other developers find it!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,13,28&height=120&section=footer" width="100%"/>

</div>

---
