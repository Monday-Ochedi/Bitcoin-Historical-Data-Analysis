# Bitcoin-Historical-Data-Analysis

<img width="740" alt="Bitcoin Analysis" src="https://github.com/user-attachments/assets/b55a7178-e2d2-4c9e-8c9b-7ebce816370d">

## Table of Content

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)

### Project Overview
Bitcoin is the longest running and most well known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto. 
Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger (the blockchain) without the need for a trusted record keeping authority or central intermediary.

### Dataset
CSV files for select bitcoin exchanges for the time period of Jan 2012 to December March 2021, with 
a minute to minute updates of OHLC (Open, High, Low, Close), Volume in BTC and indicated currency, 
and weighted bitcoin price. Timestamps are in Unix time. Timestamps without any trades or activity have
their data fields filled with NaNs

### Tools
- Data Cleaning - Power Query Editor
- Data Visualization - Microsoft Power BI
  - [Download Here](https://microsoft.com)

### Data CLeaning
- Removed unneccesary records
- Handled missing Values
- Timestamp converted to Date & Time Fields
