

# 📦 AI-Powered Supply Chain Analytics (n8n + PostgreSQL + Quadratic)

An end-to-end analytics solution that identifies inefficiencies in organic food distribution across India and US markets using modern AI tools.

## 🌟 Key Features

- **Automated Data Pipeline**: n8n workflows that monitor emails, process attachments, and load to database
- **AI-Driven Insights**: Natural language queries in Quadratic to analyze supply chain performance
- **Critical KPIs**: Calculates On-Time In-Full (OTIF), line fill rate, and volume fill rate metrics
- **Multi-Region Support**: Comparative analysis between Gujarat (India) and New Jersey (US) operations

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Workflow Automation** | n8n | Extracts CSVs from emails and loads to PostgreSQL |
| **Database** | PostgreSQL (Supabase) | Stores order data with fact/dimension tables |
| **Analytics Engine** | Quadratic | AI-powered spreadsheet for prompt-based analysis |
| **Visualization** | Quadratic Charts | Interactive performance dashboards |

## 📈 Business Insights Uncovered

1. **Delivery Performance**
   - Identified 23% revenue loss from incomplete orders
   - Calculated average 2.4-day delay for late deliveries

2. **Customer Analysis**
   - Ranked top 5 customers with OTIF issues
   - Compared regional performance (India vs US)

3. **Product Analysis**
   - Highlighted 3 product categories with <85% fill rates
   - Quantified inventory gaps causing delivery failures

## 🚀 Getting Started

### Prerequisites
- n8n account (free trial available)
- Supabase PostgreSQL database
- Quadratic account (free tier available)

### Installation Steps

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/supply-chain-ai.git
   cd supply-chain-ai
   ```

2. **Import n8n workflow**
   - Navigate to your n8n instance
   - Import `workflows/email_to_postgres.json`
   - Configure Gmail and Supabase credentials

3. **Set up Quadratic**
   - Upload `quadratic/supply_chain_analysis.qtu`
   - Connect to your Supabase database
   - Refresh data connections

## 📂 Project Structure

```
supply-chain-ai/
├── data/                   # Sample datasets
│   ├── india_orders.csv
│   └── usa_orders.csv
├── workflows/              # n8n automation files
│   └── email_to_postgres.json
├── quadratic/              # AI analysis files
│   └── supply_chain_analysis.qtu
├── sql/                    # Database scripts
│   ├── schema_setup.sql
│   └── kpi_queries.sql
└── docs/                   # Documentation
    ├── architecture.png
    └── exercise_solutions.pdf
```

## 🖼️ Sample Visualizations

![OTIF Performance by Region](docs/otif_by_region.png)
*On-Time In-Full metrics show 15% better performance in US market*

![Top Customers Analysis](docs/top_customers.png)
*Revenue impact analysis for customers with delivery issues*

## 💡 Key Learnings

Through this project, I gained:
- Hands-on experience building automated data pipelines
- Practical understanding of supply chain KPIs
- Ability to implement AI-powered analytics
- Skills in connecting low-code tools (n8n → PostgreSQL → Quadratic)

## 🤝 How to Contribute

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add new analysis feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📜 License

This project is for learning and demonstration purposes only.

## 📬 Contact

For questions or collaborations:  
Siddharth Rathore - siddharthrathore2212@gmail.com
LinkedIn Profile =  https://www.linkedin.com/in/siddharthrathore2/
GitHub Portfolio

