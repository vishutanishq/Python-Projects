## Certificate Eligibility Project
https://github.com/vishutanishq/Python-Projects/tree/main
### Project Overview
This Python project is an interactive command-line application that determines if a user is eligible to receive a certification based on several criteria. The user is prompted to provide input for various checks such as class attendance, assignment completion, live class participation, and camera usage during live sessions. If the user meets all the conditions, they are awarded a certificate.

### Features
- **Interactive Prompts:** The user is asked a series of questions, and the input is processed to evaluate their eligibility.
- **Multiple Criteria Validation:** The project checks four conditions:
  1. Class Attendance
  2. Assignment Completion
  3. Daily Live Class Participation
  4. Camera On During Live Classes
- **Simple Certificate Generation:** After successful validation, the user can enter their name to generate a simple certificate in the console.
- **Error Handling:** Invalid inputs are recognized and handled appropriately with error messages.
  
### Project Structure
This project consists of a single Python file that handles all the logic:
- Prompts the user for input using the `input()` function.
- Evaluates responses with `if-elif-else` conditional statements.
- Displays a certificate if all conditions are met.

### Prerequisites
- Python 3.x

### How to Run the Project
1. Clone the repository or download the script to your local machine.
   ```bash
   git clone https://github.com/your-username/certificate-eligibility-project.git
   ```
2. Navigate to the project directory.
   ```bash
   cd certificate-eligibility-project
   ```
3. Run the Python script.
   ```bash
   python certificate_eligibility.py
   ```
4. Follow the on-screen prompts and answer the questions. If you meet the eligibility criteria, a certificate will be generated.

### Example
```bash
--------------Certificate Eligibility project-----------------
 Are You Attend Every Class (Yes=1 or No=2)1
Amazing, You Attend Classes Right. We Move to Next Verification.
Complete Your assignment or not(yes=1 or No ==2)1
Great , You Complete Your Assignment. We Move to Next Verification.
Take Daily Live classes or not(Yes=1 or No ==2)1
Amzing , You Complete Your Daily Live classess. We Move to Next Verification.
Is you Camera is On In Live Classes? (Yes=1 or No =2)1
 Great , You select That your Camera is ON. We Move to Next Verification.
_________________Final Page______________________
Congratulation , You Are eligible for certification.
Enter Your NAME :Tanishq
--------------------Certification--------------------------------------
 Certificate awarded to Tanishq for successfully completing. 
 5 day Python class on 18-09-2023 to 22 -09-2023. 
Your dedication and hard work are recognized and celebrated.
-----------------------------------------------------------------------
Thank you
```

### Customization
Feel free to modify the code to adjust the eligibility criteria, the certificate content, or any other aspects of the project.

### Code Credits
- **Author:** Tanishq Kr Vishwakarma

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
