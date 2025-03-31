AI-Powered Personal Finance Tracker

A comprehensive financial management application with a focus on AI-driven insights, real-time data processing, and cryptocurrency tracking built specifically for Indian users.

Features

- Real-time Financial Insights: Leverages Pathway's vector store for transaction analysis and pattern detection
- Natural Language Queries: Ask questions about your finances in plain language with advanced RAG capabilities
- Indian Banking Integration: Connects with UPI and Account Aggregator framework
- Cryptocurrency Portfolio Management: Track and analyze your crypto investments with market data
- Interactive Visualizations: Visual representation of your spending patterns and financial status
- Community Insights: Compare your spending with demographic averages
- AI-Powered Financial Advice: Get personalized recommendations and coaching
- Predictive Expense Analysis: Forecast future expenses based on spending patterns
- Multi-Currency Support: Handle different currencies with automatic conversion
- Indian Tax Tools: Specific features for Indian tax calculation and planning
- Secure Authentication: Bank-level encryption and security protocols
- Savings Goals: Track progress toward financial objectives
- Voice Commands: Interact with the application through voice commands

Getting Started

Prerequisites

- Python 3.8 or higher
- Dependencies listed in `requirements.txt`

Installation

1. Clone this repository
```bash
Download the zip file from the repo
Extract the Zip
Open the extracted folder in VS code
cd FINANCEFLOW
```

2. Install required packages
```bash
pip install -r dependencies.txt
```

3. Set up environment variables
   - Create a `.env` file with the following variables:
   ```
   OPENAI_API_KEY=your_openai_api_key
   UPI_CLIENT_ID=your_upi_client_id
   UPI_CLIENT_SECRET=your_upi_client_secret
   ACCOUNT_AGGREGATOR_API_KEY=your_aa_api_key
   ```

4. Run the application
```bash
streamlit run app.py
```

 Usage

1. Authentication: Start by registering or logging into your account
2. Dashboard: Get an overview of your finances with key metrics and visualizations
3. Transactions: Add, categorize, and manage your financial transactions
4. Analytics: Explore detailed financial analysis and insights
5. AI Insights: Get personalized recommendations and answers to financial questions
6. Crypto Tracker: Manage and monitor your cryptocurrency portfolio
7. Settings: Customize application preferences and connect external accounts

Security

This application prioritizes your financial data security:
- End-to-end encryption for all transaction data
- Secure authentication protocols
- No storage of banking credentials on our servers
- Compliance with financial data protection regulations

API Integration

The application can connect with:
- UPI (Unified Payments Interface)
- Account Aggregator Framework
- Various cryptocurrency exchanges
- OpenAI/Gemini for AI capabilities

Development

Project Structure

- `app.py`: Main application file and UI components
- `database.py`: Database connection and operations
- `ai_agents.py`: AI-based data processing and insights generation
- `pathway_integration.py`: Real-time data processing with Pathway
- `openai_integration.py`: Integration with OpenAI for insights
- `crypto_integration.py`: Cryptocurrency data management
- `indian_bank_integration.py`: Integration with Indian banking systems
- `visualization.py`: Data visualization components
- `auth.py`: Authentication functionality
- `data_processing.py`: Core data transformation and analysis
- `community_insights.py`: Demographic comparison functionality
- `utils.py`: Utility functions and helpers

Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

- Data processing framework: [Pathway](https://pathway.com)
- AI capabilities: [OpenAI](https://openai.com)
- Visualization tools: [Plotly](https://plotly.com) and [Streamlit](https://streamlit.io)
- Cryptocurrency data: [CoinGecko API](https://coingecko.com)