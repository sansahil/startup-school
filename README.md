### How to run this locally

- Run the database container using this command -

```sh
docker run --name postgresql-container -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres
```

- Clone the repo to local and run the server

```sh
git clone https://github.com/sansahil/startup-school.git
cd sample-flask-project
python3 app.py runserver
```

- Look for the URL in the browser - `http://127.0.0.1:5000/signup`
- Run the operations in the page, it should work and lead to the dashboard page

### Here is the demo of the progress

![signup_demo](https://github.com/user-attachments/assets/9e5e1915-38e0-4553-89ac-49d8ac59a2aa)


###   Here is the demo of the progress
![users](https://github.com/user-attachments/assets/16ea1ce4-9c8a-4f7d-9f1c-7b8b76c93219)

