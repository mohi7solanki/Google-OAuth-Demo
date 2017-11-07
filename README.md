# Installation guide

Complete guide at - https://fosstack.com/how-to-add-google-authentication-in-django/

1) Clone repository ```git clone https://github.com/mohi7solanki/Google-OAuth-Demo.git```
2) cd (change directory) to repository. 
3) Create a virtualenv ``` virtualenv -p python3 . ```
4) Activate virtualenv ``` source bin/activate  ```
5) Install required packages ``` pip3 install -r requirements.txt  ```
6) Make migration ``` python manage.py migrate  ```
7) Run the server ``` python manage.py runserver  ```

## Note : Make Sure to add Google client ID and secret key in ``` settings.py ``` !