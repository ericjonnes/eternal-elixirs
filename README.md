## Eternal Elixir's Summary ##
A full-stack e-commerce web application that allows users to browse, purchase, and manage fictional potion products, built as a team project using
Flask and a relational database

## Features ##
* User authentication and role-based access (Admin vs. Customer)
* Product browsing and inventory display
* Shopping cart and checkout workflow
* Admin functionality for managing inventory and products
* Relational database design for users, products, carts, and orders

## Technology Selection ##
* **Backend:** Python, Flask
*  **Frontend:** HTML, CSS, Bootstrap
*  **Database:** SQLite
*  **Version Control:** Git, GitHub

## Project Structure ##
```pgsql
eternal-elixirs/
├── static/
│   ├── css/
│   └── images/
├── templates/    #HTMl templates
├── admin.py    #admin features
├── app.py
├── auth.py     #authenitcation
├── cart.py    #cart logic
├── checkout.py    #checkout workflow
├── db.py
├── shop.py    #inventory, search
├── EternalElixers.db
├── EternalElixers.sql
├── requirements.txt
└── .gitignore
```

## Setup & Run
1. Clone the repository:
```bash
git clone https://github.com/ericjonnes/eternal-elixirs.git
cd eternal-elixirs
```
2. Create and activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
 4. Run application:
 ```bash
python3 app.py
```





