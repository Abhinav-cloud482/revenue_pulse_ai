# RevenuePulse AI — AI Business Intelligence & Revenue Predictor

An enterprise-grade, client-side dynamic AI platform built for small businesses, retail stores, and e-commerce companies to project revenue, forecast seasonal trends, cluster RFM customer segments, and detect sales anomalies using **100,000+ synthetic/uploaded transaction rows**.

![RevenuePulse AI Screenshot](https://img.shields.io/badge/Status-Production--Ready-brightgreen)
![Tech Stack](https://img.shields.io/badge/Stack-React_18_%7C_Vite_%7C_Tailwind_%7C_Recharts-blue)

---

## 🌟 Key Features

1. **High-Volume Data Processing Engine**:
   - Built-in dynamic synthesizer generating **100,000+ enterprise rows** on-the-fly.
   - Interactive CSV file drop-zone supporting real dataset ingestion with dynamic column mapping.
2. **Multi-Model Machine Learning Pipeline**:
   - **XGBoost Algorithm**: Feature-weighted regression for 90-day future revenue projections.
   - **Prophet Engine**: Time-series seasonal trend decomposition with configurable confidence intervals.
   - **K-Means Clustering**: RFM (Recency, Frequency, Monetary) customer categorization (Champions, Loyal, At-Risk, Hibernating).
   - **Isolation Forest**: Real-time sales anomaly & outlier detection flags.
3. **Interactive UI & Visualization**:
   - Synchronized Multi-Line Recharts comparing historical revenue, forecast curves, and model upper bounds.
   - Live AI Strategic Recommendations generator based on model metrics.
4. **Executive PDF Report Generator**:
   - Modal export suite to preview and print C-level summary reports.

---

## 🚀 Quick Start Guide

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (version 18+ recommended) installed.

### Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/revenue-pulse-ai.git
   cd revenue-pulse-ai
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the local development server**:
   ```bash
   npm run dev
   ```

4. **Build for Production**:
   ```bash
   npm run build
   ```

---

## 📦 Project Structure

```
revenue-pulse-ai/
├── public/
├── src/
│   ├── App.jsx          # Complete Single-Page UI & ML Calculation Engine
│   ├── index.css        # Tailwind directives and CSS styling rules
│   └── main.jsx         # React application root entry point
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── postcss.config.js    # PostCSS configuration for Tailwind
├── tailwind.config.js   # Tailwind layout theme setup
├── vite.config.js       # Vite build setup
└── README.md            # Documentation
```

---

## 📄 License
MIT License. Open source for commercial and personal deployment.
