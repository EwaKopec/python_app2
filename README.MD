## Technologies used:
- Docker
- Flask
- SQLlite
- Python
- Werkzeug

## Docker instructions

To create a docker image execute: 

`docker build . -t library`

To run the docker image execute:

`docker run --detach -p 5000:5000 library` and visit with your browser http://localhost:5000
