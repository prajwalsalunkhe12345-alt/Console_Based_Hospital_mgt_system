# Console_Based_Hospital_mgt_system
A simple console-based Hospital Management System written in Python. It stores patient records in a local JSON file and lets a user manage those records through a text menu.

## Features

- Add a patient and generate a patient ID automatically
- View all patient records
- Search for a patient by ID
- Update a patient record
- Delete a patient record after confirmation
- Display patient statistics
- Save patient data to `patients_info.json`

Patient details include ID, name, age, gender, mobile number, disease, and date added. Gender input accepts `male` or `female` (case-insensitive). Disease input accepts letters and spaces only.

## Requirements

- Python 3

## Run the program

1. Save the Python source code in a file, for example `hospital_management.py`.
2. Open a terminal in the folder containing the file.
3. Run:

   ```bash
   python hospital_management.py
   ```

   On some systems, use `python3 hospital_management.py` instead.

4. Choose an option from the displayed menu by entering its number.

## Data storage

The program reads and writes patient records in `patients_info.json` in its current working directory. The file is created when patient data is first saved. Keep this file to retain records between runs.

## Input rules

- **Name:** required; letters and spaces only
- **Age:** whole number from 1 to 80
- **Gender:** `male` or `female`
- **Mobile number:** exactly 10 digits
- **Disease:** required; letters and spaces only

## Menu

1. Add Patient
2. View Patients
3. Search Patient
4. Update Patient
5. Delete Patient
6. Patient Statistics
7. Exit
