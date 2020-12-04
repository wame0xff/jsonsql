# JsonSql
JSONSql is a CLI tool that will allow you to perform queries on rest api endpoints with an SQL style langage

# Installation
- download the files
- install 'requests' library with : pip install -r requirements.txt
- run the cli: python cli.py

# Usage Examples

- jsonsql> use https://jsonplaceholder.typicode.com/todos as todos
- jsonsql> desc todos
- jsonsql> select id, title from todos where userId = 1 and id < 5
