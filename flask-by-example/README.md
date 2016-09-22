# How to make this baby work

Run:
python worker.py &
redis-server &
python manage.py runserver

Test it:
enter a url, without https:// part
get id from terminal and write this address:
127.0.0.1:5000/results/<id>


