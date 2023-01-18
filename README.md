# rabbitmq-hello-world

Attempting to learn a bit about rabbitmq.

## Setup

### Install packages
`pip install -r requirements.txt`

### Run rabbitmq
`docker run -it --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq`

## Usage
Run on separate tabs
`python receive.py` and
`python send.py`

## Reference
https://www.rabbitmq.com/tutorials/tutorial-one-python.html
