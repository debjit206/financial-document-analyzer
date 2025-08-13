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
- **Deployment**: Hugging Face Spaces
- **Version Control**: Git & GitHub

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

### GitHub Setup

1. **Initialize Git repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Financial Document Analyzer"
   ```

2. **Connect to GitHub**
   ```bash
   git remote add origin https://github.com/yourusername/financial-document-analyzer.git
   git branch -M main
   git push -u origin main
   ```

### Hugging Face Deployment

1. **Create a new Space** on [Hugging Face Spaces](https://huggingface.co/spaces)
2. **Choose Streamlit SDK**
3. **Link to GitHub repository** for auto-deployment
4. **Add GOOGLE_API_KEY** as a secret in Space settings
5. **Deploy and enjoy!**

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
├── DEPLOYMENT.md            # Deployment guide
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

## 🔒 Security & Privacy

- **No Data Storage**: Documents are processed in memory and not stored
- **API Key Security**: API keys are stored securely as environment variables
- **Financial Focus**: Only analyzes financial documents, rejects other content
- **Local Processing**: All analysis happens on Hugging Face servers

## 🚀 Deployment Features

- **Continuous Deployment**: Auto-deploy on every GitHub push
- **Professional Pipeline**: GitHub → Hugging Face integration
- **Version Control**: Track all changes and improvements
- **Easy Updates**: Simple git push to update live app

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini**: For providing the AI model
- **Streamlit**: For the amazing web framework
- **PyMuPDF**: For PDF processing capabilities
- **Hugging Face**: For hosting and deployment platform
- **GitHub**: For version control and collaboration

## 📞 Support

If you encounter any issues or have questions:
- Create an issue on GitHub
- Check the [Hugging Face Space](https://huggingface.co/spaces/YOUR_USERNAME/financial-document-analyzer) for updates

---

**Made with ❤️ for financial professionals and analysts**

## 🎓 **Project Showcase for Placement**

This project demonstrates:
- **AI/ML Integration**: Google Gemini API implementation
- **Full-Stack Development**: Streamlit frontend + Python backend
- **DevOps Skills**: GitHub + Hugging Face deployment pipeline
- **Financial Domain Knowledge**: Understanding of financial documents and calculations
- **Professional Development**: Clean code, documentation, and best practices 