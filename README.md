RUN FLASK APP
--------------

Step 1: Put OPEN AI APIKEY in `api.py` file.
Step 2: type command `flask run` in your terminal.


ENDPOINTS
---------

There 3 main endpoint
- `/chat`
- `/get_chats`
- `/delete_chats`


`/chat`
---------

` curl --location '{baseURL}/chat' \
--header 'Content-Type: application/json' \
--data '{
    "user_id":"Hamza",
    "prompt":"my name ibtehaj khan I live in New York" }'`



`/get_chats`
-----------

`curl --location '{baseURL}/get_chats' \
--header 'Content-Type: application/json' \
--data '{
    "user_id":"Hamza"
}'`

`delete_chats`
--------------

`curl --location '{baseURL}/delete_chats' \
--header 'Content-Type: application/json' \
--data '{
    "user_id":"Hamza"
}'`
