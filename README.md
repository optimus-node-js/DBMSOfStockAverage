# DBMSOfStockAverage: Data Management Services

> The database-management layer extracted from StockAverage: Python services that create, delete and update the JSON and MongoDB data stores used by the trade-analytics engine.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

## Services

| Script | Purpose |
|---|---|
| `DACFD_1.py` | Delete-All-Collections / files & directories |
| `DADIDLJSONF_9.py` | Delete-And-Download-Initialise data from DB to local JSON files |
| `USJSONDS_10.py` | Update-Server JSON data stores |
| `jsonLocatory.json` | Paths of all managed JSON stores |

## Usage

```bash
pip install pymongo
python USJSONDS_10.py
```

Set your own MongoDB connection string first.

**Part of:** [StockAverage](https://github.com/optimus-node-js/StockAverageSelfDestructWorking) · [Vega](https://github.com/optimus-node-js/Vega_CopyTrading_Platform)

---

## Author

**Rahul Vishwakarma**, Senior Full Stack Developer based in Ahmedabad, India

[![Portfolio](https://img.shields.io/badge/Portfolio-rahul--vishwakarma--portfolio.vercel.app-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://rahul-vishwakarma-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Vishwakarma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-vishwakarma-101346192)
[![Email](https://img.shields.io/badge/Email-karmarahul67%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karmarahul67@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-optimus--node--js-181717?style=flat-square&logo=github)](https://github.com/optimus-node-js)

