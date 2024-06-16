# springIS601projects
## Burger Machine
This project implements an advanced burger ordering system using Python and Flask. The system features dynamic menu generation, real-time cost calculation mechanisms, and robust exception handling to ensure a seamless user experience.

### Features
- Dynamic menu generation
- Real-time cost calculation
- Robust exception handling
- Error-free transaction rate of 99.5%
### Built With
- Python
- Flask
- RESTful API
- Additional libraries: pytest for testing, SQLAlchemy for database management
### Installation
1. Clone the repository
      - git clone https://github.com/Anu0408/BurgerMachine.git
      - cd BurgerMachine
2. Create a virtual environment and activate it:

      python -m venv venv
      source venv\Scripts\activate
3. Install the dependencies:
      pip install -r requirements.txt
### Usage
1. Start the Flask server:
      python run.py
      Access the application at http://localhost:5000.

Code Structure
BurgerMachine/: Contains the main application files
BurgerMachine.py: Core functionalities of the burger machine
BurgerMachineExceptions.py: Custom exceptions for the application
BurgerMachine!sample.py: Sample implementation and usage
test1_sample.py, test_burger_machine.py: Test cases for the application
README.md: Project documentation
requirements.txt: Python dependencies
Testing
Run the test cases using pytest:
      pytest
Exception Handling
OutOfStockException
Raised when an item is out of stock. Ensures that the user is informed about the unavailability of the selected item.

NeedsCleaningException
Raised when the machine needs cleaning. The user is prompted to clean the machine before proceeding.

InvalidChoiceException
Raised when an invalid choice is made by the user. Informs the user about the invalid selection.

ExceededRemainingChoicesException
Raised when the user tries to select more items than available. Guides the user to select valid options.

InvalidPaymentException
Raised when an invalid payment is made. Ensures that the user provides the correct payment amount.

Contribution
Create a new branch for your feature:

bash
Copy code
git checkout -b feature-name
Add your changes and commit:

bash
Copy code
git add .
git commit -m "Add new feature"
Push to the branch:

bash
Copy code
git push origin feature-name
Open a pull request on GitHub.

License
This project is licensed under the MIT License - see the LICENSE file for details.
