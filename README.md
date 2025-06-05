# Business Impact of Data Breaches: Power BI Dashboard Analysis

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://scikit-learn.org/)

Interactive Power BI dashboards analyzing data breach impacts across industries with machine learning predictions for strategic business intelligence.

## 📊 Overview

**Key Statistics:**
- 4,000+ breach incidents analyzed (2000-2024)
- 20+ billion individuals affected
- $148.85 billion in financial losses
- 203,000+ lawsuits filed

## 🏗️ Architecture

**Data Pipeline:**
Web Scraping (Python) → Data Processing (Pandas, Power Query) → ML Models (Scikit-learn) → Power BI Dashboards

**Data Sources:** OWASP, HaveIBeenPwned, Verizon DBIR, IBM Security Reports, Regulatory websites

## 📈 Dashboards

1. **Breach Trends & Analysis** - Timeline patterns, industry targeting, breach types
2. **Financial & Business Impact** - Monetary losses, stock performance, company rankings  
3. **Cybersecurity Insights** - Attack vectors, breach causes, technical analysis
4. **Regulatory & Legal Impact** - Compliance costs, legal consequences by country

## 🔍 Key Insights

- **Most Affected Industries:** Healthcare, Telecom, Technology
- **Average Financial Loss:** $250M per breach
- **Stock Impact:** 19.71% average decline post-breach
- **Primary Attack Vectors:** Phishing (35%), Malware (28%), Ransomware (22%)
- **Largest Incident:** Yahoo breach ($21B loss, 3B accounts)

## 🚀 Quick Start

### Power BI Dashboard Analysis
```bash
# Clone repository
git clone https://github.com/yourusername/data-breach-analysis.git

# Install Python dependencies  
pip install pandas numpy scikit-learn beautifulsoup4 selenium requests

# Open Power BI dashboards
# Load .pbix files in Power BI Desktop
```

### Web Application
This project includes a [Next.js](https://nextjs.org/) web application bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

```bash
# Install Node.js dependencies
npm install
# or
yarn install

# Run the development server
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## 🛠️ Tech Stack

- **Data Collection:** Python (BeautifulSoup, Selenium)
- **Processing:** Pandas, Power Query
- **ML Models:** Linear Regression, ARIMA forecasting
- **Visualization:** Power BI, DAX
- **Web Application:** Next.js, React, TypeScript

## 📋 Dataset

- **File:** DataBreaches.xlsx (~8MB)
- **Records:** 1,000+ verified incidents
- **Completeness:** 95% after cleaning
- **Key Fields:** Date, Organization, Industry, Financial Impact, People Affected, Stock Impact

## 🔮 Future Enhancements

- Real-time threat monitoring
- Advanced ML models (Neural Networks)
- Geospatial analysis
- Mobile dashboard support

## 📚 Learn More

To learn more about Next.js, check out:
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial
- [Next.js GitHub repository](https://github.com/vercel/next.js/) - feedback and contributions welcome!

## 🚀 Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

