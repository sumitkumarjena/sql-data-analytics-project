You explore a sales database step by step, then go deeper with trends, segments and two full reports.

**New here? Open the setup guide in the `00_setup` folder.** It walks you through installing SQL Server and creating the database, on Windows and Mac, with the fixes for the common errors.

```
sql-data-analytics-project/
├── 00_setup/                        the setup guide, and the one-click Docker start for Mac
├── 01_datasets/                     the data, as a backup and as CSV files
│   ├── DataWarehouseAnalytics.bak   the database, ready to restore
│   └── csv-files/                   the same data, to build the database yourself
├── 02_docs/                         the project roadmap and notes
└── 03_scripts/                      the queries, in the order of the videos
    └── 00_init_database.sql         builds the database from the CSV files
```

Get the database in one of two ways:

- Restore `01_datasets/DataWarehouseAnalytics.bak` in SSMS. It needs SQL Server 2022 or newer.
- Or run `03_scripts/00_init_database.sql`. It builds the database from the CSV files in `C:\sql\sql-data-analytics-project\01_datasets\csv-files\`.

The videos show the folders without numbers: `datasets` there is `01_datasets` here, `scripts` is `03_scripts`.

---

## 🛡️ License

[MIT](LICENSE). Use it, change it, share it, with attribution.

## 🌟 About me

