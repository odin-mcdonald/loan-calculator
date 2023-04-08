# Simple Loan Calculator

3300 - loan calculator Python Flask web app

Basic Flask application using Jinja templates. The user enters details of their loan and it calculates the monthly payment and an amortization table.

This application is used to teach CI/CD.

- automated testing
- GitHub Actions workflow files (.yaml)

### To Run This Application

---

1. Clone this repository to local computer

2. Create a new virtual environment

   - Windows: `python -m venv ./venv`
   - Mac: `python3 -m venv ./venv`

3. Activate the new virtual environment

   - Windows: `.\venv\Scripts\activate`
   - Mac: `source ./venv/bin/activate`

4. Install the dependencies `pip install -r requirements.txt`

5. Run the application with
   `python app.py ` or `flask run`

### TODO:

---

[x] ~~Loan calculation~~  
[x] ~~Amoritzation table~~  
[x] ~~Formatting with Bootstrap 5~~  
[x] ~~Sticky header on amortization table~~  
[x] ~~Bootstrap 5 tooltips for help~~  
[x] ~~Font Awesome icons for tooltips~~  
[ ] Pytest file for unit and functional testing  
[ ] Custom GitHub Action workflow file for CI/CD
