# Medical Bill Management System

A Flask-based web application for managing medical bills and generating reports in both PDF and DOCX formats.

## Features

- Add, edit, and delete medical bill entries
- Group bills by month with subtotals
- Generate PDF reports
- Generate DOCX reports
- Import/Export bill data
- Support for multiple patients
- Automatic calculation of totals
- Professional document formatting

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd medical-bill-app
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python medical_bill_flask/app.py
```

5. Open your browser and navigate to:
```
http://localhost:5000
```

## Dependencies

- Flask
- Flask-WTF
- python-docx
- reportlab
- num2words

## Usage

1. Select the patient (Rashida Sultana or Md. Moklasur Rohman)
2. Add bill entries with:
   - Invoice/Voucher No.
   - Date
   - Amount (Taka)
   - Name of Medicine
3. Use the action buttons to:
   - Save table data
   - Import saved data
   - Download PDF report
   - Download DOCX report
4. Edit or delete entries as needed

## License

This project is licensed under the MIT License. 