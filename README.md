# portfolio
This is entended to be a light weight web app to display personal development projects and a project in itself that is Perpetually in development.

---

## TODOs
- [] Finish basic styling / minimum viable product
- [x] add a database locally.
    - [x] connect local app to database
    - [x] create project model for database. 
        - [] create documents model, one to one relationship
    - [x] add alembic and generate migrations from sqlalchemy model
    - [x] create tables in database

- [] automate deployment and necessary development processes
    - determine sub tasking
- [] deploy to AWS
- [x] set up pipenv
- [] add a reusable project template so projects can be viewed with more details.
---

### first level dependencies
- fastapi
- uvicorn
- jinja2
- pydantic
- sqlalchemy
- alembic
- psycopg2
