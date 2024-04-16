# Budget Tracker App in React & Redux + Django

```
Budget Tracker is an online ledger to help you track your expenditure and income accurately and effectively monitor your spending.
It is created in a user-friendly manner are diagrammatic and graphical representations to enhance
your understanding, save you time from the tedious process of bookkeeping, and allow you to
sync and manage your entire bookkeeping in a single app.
```

## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

1. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
