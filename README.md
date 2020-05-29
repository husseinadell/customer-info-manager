install:
    - pip install -r requirements.txt
    - python manage.py migrate
    - cd frontend/
    - npm i

run: 
    - Backend: python manage.py runserver
    - frontend: npm start