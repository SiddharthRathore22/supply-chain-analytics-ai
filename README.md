# End-to-End Supply Chain Analytics with AI Tools

![Project Architecture](docs/architecture.png)

A complete analytics pipeline for supply chain optimization using modern AI tools: N8N for workflow automation, PostgreSQL for data storage, and Quadratic for AI-powered analysis.

## 🚀 Features

- **Automated Data Pipeline**: N8N workflow to extract data from emails and load into PostgreSQL
- **AI-Powered Analysis**: Quadratic spreadsheet with prompt-based analytics
- **Key Supply Chain Metrics**: Calculates OTIF (On-Time In-Full), line fill rate, volume fill rate
- **Multi-Country Support**: Handles data from both India and US markets

## 🛠️ Tech Stack

- **Workflow Automation**: [N8N](https://n8n.io/)
- **Database**: [PostgreSQL](https://www.postgresql.org/) (hosted on Supabase)
- **AI Analytics**: [Quadratic](https://www.quadratichq.com/)
- **Data Visualization**: Built-in Quadratic charts

## 📊 Key Metrics Calculated

1. **Order Fill Rates**
   - Line Fill Rate
   - Volume Fill Rate
2. **Delivery Performance**
   - On-Time Delivery %
   - On-Time In-Full (OTIF) %
3. **Customer Analysis**
   - Top customers by order value
   - Regional performance metrics

## 🏁 Getting Started

### Prerequisites
- N8N account
- Supabase/PostgreSQL database
- Quadratic account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/supply-chain-analytics-ai.git
