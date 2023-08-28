# web-development-newbie
Creating server-side backend using Django
Django is famous for being scalable, secure and simple. It allows for rapid server-side web development. Follows Model-View-Template architecture. Code reuse and maintainability.

                                             HTTP response
                                                   ^
                                                   |
HTTP request -> URLS (urls.py) -> appropriate view in views.py <- HTML files 
                                                   ^
                                                   |
                                               models.py
                                               
Using django-graphene fro GrpahQL with django

Creating the environment:
1. Create python virtual environment :
    go to the folder containing the project
   
    '''python3 -m venv evn_name'''
   
    '''source evn_name/bin/activate'''
   
3. Install the required packages:
   
     '''pip install graphene-django'''
