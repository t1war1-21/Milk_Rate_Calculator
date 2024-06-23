# Milk Rate Calculator

The Milk Rate Calculator is a web-based application designed to calculate milk prices based on the fat content, SNF (Solid Not Fat) value, and total milk amount. This tool helps dairy farmers and milk suppliers to determine the pricing of milk efficiently.

## Project Structure


- **Milk_Rate_Calculator/**: Root directory of the project.
  - **requirements.txt**: Contains the list of dependencies required for the project.
  - **app.py**: Main Flask application script.
  - **rate_sheet.xlsx**: Excel file containing the rate sheet data.
  - **templates/**: Directory containing HTML template files.
    - **index.html**: Template for the input form.
    - **result.html**: Template for displaying the results.

```plaintext
Milk_Rate_Calculator/
├── requirements.txt
├── app.py
├── rate_sheet.xlsx
└── templates/
    ├── index.html
    └── result.html
```
Create a root directory named Milk_Rate_Calculator inside this directory keep requirements.txt, app.py, rate_sheet.xlsx files.
Now create a folder named templates inside the root folder Milk_Rate_Calculator and keep the files index.html and result.html inside the folder templates.
## Getting Started

### Clone the Repository:
```bash
git clone https://github.com/t1war1-21/Milk_Rate_Calculator.git
cd Milk_Rate_Calculator

#Create a Virtual Environment (Optional):
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`

#Install Dependencies:
pip install -r requirements.txt

#Run the Application:
python app.py
`````

### Access the Application:

Open your browser and go to http://localhost:5000.
                      or.
Open your browser and go to http://127.0.0.1:5000.
