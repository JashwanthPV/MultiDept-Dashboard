# MultiDept-Dashboard
# MultiDept Dashboard,  MultiDept Dashboard is a web application built using Flask that dynamically generates individual dashboards for each department listed in an input file. The project provides an intuitive sidebar navigation where users can view and access specific dashboards tailored for each department.  

*********************************************************************************************************************************************************************************************************************
MultiDept Dashboard/ ├── templates/ │ ├── base.html │ ├── index.html │ └── department_dashboard.html ├── static/ │ └── style.css ├── departments.txt └── app.py

### Files and Directories
- **app.py**: The main Flask application file.
- **departments.txt**: Input file containing a list of department names. Each line represents a department.
- **templates/**: Contains HTML templates:
  - **base.html**: Base layout with sidebar for department navigation.
  - **index.html**: Main dashboard page.
  - **department_dashboard.html**: Template for individual department dashboards.
- **static/**: Directory for static files (e.g., CSS stylesheets).

## Features
- **Dynamic Sidebar Navigation**: Generates a sidebar with links to each department dashboard based on `departments.txt`.
- **Individual Department Dashboards**: Each department has its unique page with customizable content.
- **Responsive Layout**: The dashboard layout is responsive and adjusts across different screen sizes.

Install Dependencies Ensure Python is installed, then install Flask:
pip install flask

Prepare the Department File Add department names in departments.txt, each on a new line:
Sales
Marketing
HR
Finance
Operations

Run the Application:
python app.py
Access the dashboard at http://127.0.0.1:5000/.
