# Books-Management (simple-flask-API)
This is simple Books-Management API for handling books using flask .

Run api.py file and go to your browser to add/del/get the list of books.

Example: 

To Add a Book:-
http://localhost:8888/v1/addbook?title="Macbeth"&author="Shakespeare"

To get the all the added book details:-
http://localhost:8888/v1/getbooks

To delete any added Book:-
http://localhost:8888/v1/delbook?title="Macbeth"

Currently, it doesnot have any database connectivity so, once the brower session is closed, the books details will be lost.
