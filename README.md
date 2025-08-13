# 🔍 Financial Document Analyzer

A powerful AI-powered tool for analyzing financial documents using Google's Gemini 1.5 Flash model. Extract insights, perform calculations, and get professional financial analysis from invoices, financial statements, annual reports, and more.

## ✨ Features

- **📄 Multi-Format Support**: Analyze JPG, PNG, JPEG, and PDF documents
- **🧮 Financial Calculations**: Automatic computation of P/E ratios, profit margins, debt-to-equity ratios, and more
- **📊 Comprehensive Analysis**: Handle invoices, financial statements, annual reports, and investment documents
- **🔒 Financial-Focused**: Strictly analyzes financial documents only
- **💾 Export Results**: Download analysis reports for further use
- **📱 Responsive Design**: Modern, user-friendly interface

## 🚀 Live Demo

[View the live application on Hugging Face Spaces](https://huggingface.co/spaces/YOUR_USERNAME/financial-document-analyzer)

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **AI Model**: Google Gemini 1.5 Flash
- **PDF Processing**: PyMuPDF (fitz)
- **Image Processing**: Pillow (PIL)
- **Environment**: Python 3.8+

## 📋 Supported Document Types

- **Invoices & Receipts**: Payment details, totals, tax calculations
- **Financial Statements**: Income statements, balance sheets, cash flow statements
- **Annual Reports**: Company performance, financial metrics
- **Investment Reports**: Portfolio analysis, returns, ratios
- **Tax Documents**: Tax calculations, deductions, liabilities
- **Bank Statements**: Transaction analysis, balance calculations

## 🧮 Financial Calculations Available

- **P/E Ratio**: Market Price per Share / Earnings per Share
- **Debt-to-Equity**: Total Debt / Total Shareholders' Equity
- **Gross Margin**: (Revenue - Cost of Goods Sold) / Revenue
- **Net Profit Margin**: Net Income / Revenue
- **Return on Equity (ROE)**: Net Income / Shareholders' Equity
- **Current Ratio**: Current Assets / Current Liabilities
- **And many more...**

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/financial-document-analyzer.git
   cd financial-document-analyzer
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   # Create .env file
   echo "GOOGLE_API_KEY=your_api_key_here" > .env
   ```

5. **Run the application**
   ```bash
   streamlit run main.py
   ```

## 🔑 Environment Variables

- `GOOGLE_API_KEY`: Your Google Gemini API key (required)

## 📁 Project Structure

```
financial-document-analyzer/
├── main.py                    # Main Streamlit application
├── requirements.txt           # Python dependencies
├── .streamlit/               # Streamlit configuration
│   └── config.toml          # App configuration
├── README.md                 # Project documentation
├── .gitignore               # Git ignore file
└── .env                     # Environment variables (local only)
```

## 🎯 Usage Examples

### Example Questions for Financial Statements:
- "What is the P/E ratio for 2024?"
- "Calculate the debt-to-equity ratio"
- "What was the net profit margin?"
- "Show me the revenue growth from 2023 to 2024"

### Example Questions for Invoices:
- "What is the total amount due?"
- "Calculate the tax amount"
- "What are the payment terms?"
- "When is this invoice due?"
- "What is the invoice date?"
- "Who is the vendor/supplier?"

## 🔒 Security & Privacy

- **No Data Storage**: Documents are processed in memory and not stored
- **API Key Security**: API keys are stored securely as environment variables
- **Financial Focus**: Only analyzes financial documents, rejects other content
- **Local Processing**: All analysis happens on Hugging Face servers

