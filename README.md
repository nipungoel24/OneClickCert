# OneClickCert

OneClickCert automates the generation and distribution of certificates with just one click! It takes a certificate template and an Excel sheet containing participant details (name, role, event name, email) and auto-fills the required fields before emailing the certificates directly to recipients. A one-stop solution for efficient and organized certificate distribution.

## Features
- Auto-fills certificate templates with participant details
- Reads participant data from an Excel sheet
- Generates personalized certificates in bulk
- Sends certificates via email automatically
- Ensures an organized and hassle-free certificate distribution process

## How to Run

### Step 1: Clone the Repository  
```bash
git clone https://github.com/nipungoel24/OneClickCert.git
cd OneClickCert
```

### Step 2: Create and Activate a Conda Environment  
```bash
conda create -n oneclickcert python=3.10
conda activate oneclickcert
```

### Step 3: Install Dependencies  
```bash
pip install -r requirements.txt
```

### Step 4: Run the Script  
```bash
python oneclickcert.py
```

## Configuration
- Ensure you have a certificate template in `.png` or `.pdf` format.
- The Excel sheet should contain columns for **Name, Role, Event Name, Email**.
- SMTP settings need to be configured for email distribution.

## Future Enhancements
- Add support for multiple certificate templates
- Implement a web interface for easier management
- Integrate cloud storage options for saving certificates
- Provide detailed logging and error handling

## Contributions  
Feel free to fork the repo and open a pull request with your improvements!

