# 📊 Lot Size & Screenshot Tool for MetaTrader 4

A lightweight MetaTrader 4 Expert Advisor (EA) that helps traders calculate correct position size based on risk percentage and stop loss, and capture clean chart screenshots during live trading.

## 🚀 Overview

This tool adds an interactive calculator panel directly on the chart where traders can enter their risk percentage and stop loss distance. The EA automatically calculates the correct lot size and shows the exact risk amount in account currency. It also enables one-click chart screenshots to simplify trade documentation and review.

## ⚙️ Features

- Real-time risk-based lot size calculation  
- Displays calculated lot size and monetary risk  
- Automatic pip value handling for different symbol digit formats (e.g. 3 / 5 digit brokers)  
- Interactive on-chart calculator panel  
- Toggle button to hide or show the calculator UI  
- One-click chart screenshot capture  
- UI elements are automatically hidden before screenshot and restored afterward  
- Structured screenshot saving format:  
  `hamgam / account / symbol / date / timeframe / time.png`  
- Input validation for risk percentage and stop loss values  

## 🧠 Technical Highlights

- Developed using MQL4 for MetaTrader 4  
- Event-driven logic using `OnTick()` and `OnChartEvent()`  
- Dynamic UI rendering using chart object API  
- Risk calculation based on Account Equity, Stop Loss distance, and Pip Value  
- Symbol digit normalization handling  
- Calculator visibility state management  
- Screenshot automation using platform chart functions  

## ▶️ Usage

1. Copy the EA file into `MetaTrader4 / MQL4 / Experts`  
2. Compile using MetaEditor  
3. Attach the EA to any chart  
4. Enter risk percentage and stop loss  
5. View calculated lot size and risk amount  
6. Click “Screenshot” to capture the chart  

## 🔗 Context

This tool was developed as an early practical utility related to my trading performance platform concept, which later evolved into the web-based system **Journovate**, focused on structured trade journaling and behavioral analysis.

## 👨‍💻 Developer

**Arvin Golshani**  
Aspiring Full-Stack Developer | Founder of Journovate  
GitHub: https://github.com/ArvinGolshani
