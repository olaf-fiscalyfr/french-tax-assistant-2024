# 🇫🇷 French Tax Assistant 2025 – Clickimpôts

An intelligent assistant to automatically extract tax data from client documents (PDF, Word, JSON) and generate structured output files ready to import into Clickimpôts and other French tax software.

## 🔧 Features

- **Smart Document Processing**: Upload PDF, Word, Excel, images and text documents for automatic tax data extraction
- **OCR Capability**: Extract data from scanned documents using advanced OCR technology
- **AI-Powered Analysis**: Powered by GPT-4 Turbo to accurately identify tax relevant information
- **Complete Tax Forms Coverage**:
  - Form 2042: General income declaration (salaries, pensions, investment income)
  - Form 2044: Real estate income
  - Form 2047: Foreign source income
  - Form 2086: Professional expenses
  - Form 3916: Foreign bank accounts
- **Exchange Rate Management**: Built-in currency conversion with customizable exchange rates
- **Editable Results**: Review and modify extracted data before exporting
- **Multiple Export Options**:
  - Excel workbook with formatted sheets matching IRPP standards
  - JSON file compatible with Clickimpôts import feature
- **Bank Account Detection**: Automatically identifies and catalogs foreign bank accounts for 3916 declaration
- **Data Validation**: Automatically validates tax codes and highlights potential issues

## 📋 Requirements

- Python 3.10 or higher
- OpenAI API key (for GPT-4 Turbo)
- Required Python packages (see requirements.txt)
- Tesseract OCR (for document scanning capability)

## 🚀 Installation & Setup

### Option 1: Local Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/french-tax-assistant.git
   cd french-tax-assistant
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
3. Install Tesseract OCR:
   - **Windows**: Download from [GitHub](https://github.com/UB-Mannheim/tesseract/wiki)
   - **macOS**: `brew install tesseract`
   - **Linux**: `sudo apt install tesseract-ocr tesseract-ocr-fra`

4. Set up your OpenAI API key:
   - Create a file named `.env` in the project directory
   - Add your API key: `OPENAI_API_KEY=your_api_key_here`
   - Alternatively, enter your API key in the app's settings sidebar

5. Run the application:
   ```bash
   streamlit run app.py
   ```

### Option 2: Docker Installation

1. Build the Docker image:
   ```bash
   docker build -t french-tax-assistant .
   ```

2. Run the container:
   ```bash
   docker run -p 8501:8501 french-tax-assistant
   ```

3. Open your browser and go to: http://localhost:8501

## 📝 Usage Guide

1. **Upload Documents**: Use the file uploader to select client tax documents (questionnaires, P60s, bank statements, etc.)
2. **Enter Client Information**: Add basic taxpayer information to personalize the outputs
3. **Analyze Documents**: Click the "Analyze Documents" button to start the AI extraction process
4. **Review Extraction**: Examine the extracted tax information and correct any errors
5. **Edit if Needed**: Modify the extracted data in the interactive table as needed
6. **Download Results**: Export to Excel (for your records) and JSON (for Clickimpôts)

## 📚 Supported Tax Codes

The application supports all standard French tax codes across the following forms:

- **Form 2042**: Salaries, pensions, investment income, etc.
- **Form 2044**: Real estate income and expenses
- **Form# 🇫🇷 French Tax Assistant 2025 – Clickimpôts

An intelligent assistant to automatically extract tax data from client documents (PDF, Word, JSON) and generate structured output files ready to import into Clickimpôts and other French tax software.

## 🔧 Features

- **Smart Document Processing**: Upload PDF, Word, and text documents for automatic tax data extraction
- **AI-Powered Analysis**: Powered by GPT-4 Turbo to accurately identify tax relevant information
- **Complete Tax Forms Coverage**:
  - Form 2042: General income declaration (salaries, pensions, investment income)
  - Form 2044: Real estate income
  - Form 2047: Foreign source income
  - Form 2086: Professional expenses
  - Form 3916: Foreign bank accounts
- **Exchange Rate Management**: Built-in currency conversion with customizable exchange rates
- **Editable Results**: Review and modify extracted data before exporting
- **Multiple Export Options**:
  - Excel workbook with formatted sheets matching IRPP standards
  - JSON file compatible with Clickimpôts import feature

## 📋 Requirements

- Python 3.10 or higher
- OpenAI API key (for GPT-4 Turbo)
- Required Python packages (see requirements.txt)

## 🚀 Installation & Setup

### Option 1: Local Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/french-tax-assistant.git
   cd french-tax-assistant
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a file named `.env` in the project directory
   - Add your API key: `OPENAI_API_KEY=your_api_key_here`
   - Alternatively, enter your API key in the app's settings sidebar

4. Run the application:
   ```bash
   streamlit run app.py
   ```

### Option 2: Docker Installation

1. Build the Docker image:
   ```bash
   docker build -t french-tax-assistant .
   ```

2. Run the container:
   ```bash
   docker run -p 8501:8501 french-tax-assistant
   ```

3. Open your browser and go to: http://localhost:8501

## 📝 Usage Guide

1. **Upload Documents**: Use the file uploader to select client tax documents
2. **Review Extraction**: The app will automatically process and extract tax information
3. **Edit if Needed**: Review and modify the extracted data in the interactive table
4. **Download Results**: Export to Excel (for your records) and JSON (for Clickimpôts)

## 📚 Supported Tax Codes

The application supports all standard French tax codes across the following forms:

- **Form 2042**: Salaries,# french-tax-assistant-2024
