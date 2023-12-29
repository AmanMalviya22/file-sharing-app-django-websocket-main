### completed file sharing api using DjangoRestFramework

## Basic setup and installation
# step1. clone the repo using command 
 git clone https://github.com/AmanMalviya22/file-sharing-app-django-websocket-main
# install the djangorestframework using below command
pip install djangorestframwork
# come inside project directory and run following command
python manage.py runserver
# open postman and run the below command 
http://127.0.0.1:8000/handle and in body section seletion form data and in input field upload file and set http method as post and click on send button
the output will look like .
![Screenshot 2023-12-29 124353](https://github.com/AmanMalviya22/file-sharing-app-django-websocket-main/assets/94959490/62c7e122-1974-4418-ab59-df6d6f0b61ac)

## in above image we get folder which contain all files that we uploaded
in order to download all file we upload we can share url
### http://127.0.0.1:8000/download/841cc7b1-e658-44d4-be56-6d39130286da


