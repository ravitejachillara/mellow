# **Mellow - Email Verifier Tool**

## **Description**

This Email Verifier Tool is a simple yet powerful Python application designed to validate and verify email addresses in bulk from an Excel file. It checks for the validity of email syntax and the existence of domain MX records. The application features a user-friendly graphical interface, allowing users to easily select input files and save the processed output. It's ideal for users who need to verify large lists of email addresses quickly and efficiently.

## **Features**

- **Email Syntax Validation**: Checks if email addresses are in the correct format.
- **MX Record Verification**: Validates the existence of MX records for the domain of each email address.
- **Excel File Processing**: Allows bulk processing of email addresses from an Excel file.
- **Progress Tracking**: Includes a progress bar to monitor the verification process.
- **User-Friendly GUI**: Simple and intuitive graphical user interface for ease of use.

## **Installation**

### **Prerequisites**

- Python (3.6 or later)
- Pip (Python package manager)

### **Dependencies**

The following Python packages are required:

- **`openpyxl`**
- **`dnspython`**
- **`tkinter`** (usually included in standard Python installation)

To install these dependencies, run:

```bash
pip install openpyxl dnspython

```

### **Executable Version**

For ease of use, an executable version of the application is also available, which does not require a separate Python installation. (Check Releases)

## **Usage**

### **Running the Script**

- Clone the repository or download the source code.
- Navigate to the script's directory.
- Run the script using Python:
    
    ```bash
    python mellow.py
    
    ```
    

### **Using the Application**

- Click on "Open File" to select your Excel file containing email addresses.
- Click on "Save As" to choose the destination for the output file.
- The application will process the emails and update their status in the new Excel file.


## **Contributing**

Contributions to the Email Verifier Tool are welcome. If you have suggestions for improvement or have found a bug, please open an issue or submit a pull request.

## **License**

This project is licensed under the [MIT License](https://github.com/ravitejachillara/mellow/blob/main/GPL-MIT-License.txt).

## **Contact**

For any queries or further assistance, please contact [iamravitejachillara@gmail.com].
