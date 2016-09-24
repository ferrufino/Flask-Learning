# How to make it run and test API

##Run:


redis-server &
python worker.py &
python manage.py runserver

##Test it:

enter a url, without "https://" part

get id from terminal and write this address:

127.0.0.1:5000/results/"id"


