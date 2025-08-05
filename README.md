

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

- 
## 📂 File Included

- `AtliQ Mart Supply Chain (1).grid`: Quadratic project file containing the analysis, KPIs, visualizations, and SQL queries.

---

## 🖥️ How to Open .grid File

1. Go to [Quadratic](https://quadratic.to)
2. Sign in or create a free account
3. Upload using the ➕ Upload button
4. Enjoy full interactivity:
   - ✏️ Modify SQL queries
   - 🤖 Ask AI questions
   - 📊 Create visuals

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

## 📊 Sample Visualizations

1. **Top 5 Customers: OTIF Performance**  
   ![Top Customers OTIF](dashboard.png)  
   *Identifies key accounts needing delivery improvement*

2. **Product Fill Rate Analysis**  
   ![Product Fill Rates](dashboard.png)  
   *Organic spices show only 79% fill rate compared to 94% for packaged foods*

3. **Monthly Trend Analysis**  
   ![Monthly Trends](dashboard.png)  
   *Q3 shows 22% more delays than Q2, correlating with monsoon season in Gujarat*

4. **Regional OTIF Performance**  
   ![Regional OTIF](docs/regional_otif.png)  
   *US operations maintain 15% higher OTIF than India (88% vs 73%)*

[▶ View interactive dashboard in Quadratic](#) *(add direct link if available)*

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

