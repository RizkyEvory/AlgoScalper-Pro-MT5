# AlgoScalperPro — Professional Price Action Scalping Indicator (MT5)

![MT5](https://img.shields.io/badge/Platform-MetaTrader%205-blue)
![Type](https://img.shields.io/badge/Type-Non--Repaint%20Indicator-green)
![Market](https://img.shields.io/badge/Market-XAUUSD%20Optimized-gold)
![Style](https://img.shields.io/badge/Trading-Price%20Action%20%2F%20Scalping-orange)

**AlgoScalperPro** adalah indikator **price action–based scalping** untuk MetaTrader 5 yang dirancang untuk membantu trader mengidentifikasi **momentum valid, false breakout, dan area reaksi harga** secara objektif dan non-repaint.

> Dibangun dengan fokus pada **market structure, volatility, dan candle behavior**, bukan indikator lagging klasik.

---

## 🔥 Core Features

- ✅ **Non-Repaint Logic** (berbasis closed candle)
- 📊 **Multi-Setup Detection**
  - EMA Pullback (EMA Kiss)
  - Support & Resistance Bounce
  - False Breakout / Liquidity Sweep
- ⚡ **Momentum Validation**
  - Candle displacement
  - Range expansion
  - ATR impulse
- 🕒 **Session Filter**
  - Asian
  - London
  - New York
- 📈 **Dynamic Market State Detection**
  - Trend vs Range
  - Volatility condition
- 🖥️ **Visual Dashboard**
  - Market bias
  - Volatility status
  - Active session
  - Signal confidence score

---

## ❌ What This Indicator Is NOT

Penting untuk dipahami secara jujur:

- ❌ **Bukan Expert Advisor (EA)**
- ❌ **Tidak membuka order otomatis**
- ❌ **Bukan holy grail**
- ❌ **Bukan martingale / grid**
- ❌ **Tidak menjamin profit**

Indikator ini adalah **decision-support tool**, bukan mesin uang otomatis.

---

## 🎯 Recommended Usage

- **Market**: XAUUSD (Gold)
- **Timeframe**: M1 – M5
- **Style**: Scalping / Intraday
- **Broker**: Low spread & fast execution

Gunakan indikator ini sebagai:
- Konfirmasi entry manual
- Filter momentum
- Validasi false breakout
- Pendamping strategi price action / SMC

---

## ⚙️ Indicator Logic Overview

### 1. EMA Pullback (Trend Continuation)
- Harga retrace ke EMA
- Valid hanya jika:
  - Trend jelas
  - Momentum candle kuat
  - Volatility mendukung

### 2. Support & Resistance Bounce
- Rejection candle di area S/R
- Dikonfirmasi oleh:
  - Candle body dominance
  - Momentum & ATR

### 3. False Breakout / Liquidity Sweep
- Wick menembus high/low sebelumnya
- Close kembali ke dalam range
- Cocok untuk kondisi stop-hunt

---

## 📌 Signal Philosophy

AlgoScalperPro **tidak mengejar banyak sinyal**.  
Fokus utama adalah:

> **Kualitas pergerakan, bukan kuantitas entry.**

Lebih sedikit sinyal, tetapi:
- Lebih bersih
- Lebih terkontrol
- Lebih realistis untuk scalping

---

## 🛠️ Installation

1. Download file `AlgoScalperPro.mq5`
2. Buka MetaTrader 5
3. `File → Open Data Folder`
4. Masuk ke folder: `MQL5/Indicators/`
5. Paste file indikator
6. Restart MT5
7. Attach indikator ke chart XAUUSD

---

## ⚠️ Disclaimer

Trading forex & gold memiliki risiko tinggi.  
Gunakan indikator ini **dengan manajemen risiko yang disiplin**.

Developer **tidak bertanggung jawab atas kerugian finansial** akibat penggunaan indikator ini.

---

## 👤 Author

**M4DI~UciH4**  
Independent Trading System Developer  
Price Action & Market Structure Focused

---

## 📄 License

This project is released for **educational and personal use**.  
Redistribution or commercial use requires permission from the author.
