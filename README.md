# rest_api_go
"Tutorial: Developing a RESTful API with Go and Gin" from go documentation.

For a client perspective to add a different album to the our database:
With the service running, open a different command line window, use curl to make a request to your running web service.

$ curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
