
## Blockchain based solution to Distributed Ledger Technology Compromises -- VIP Summer 2019 ##
VIP 2019 Summer Term Repo for Blockchain Solution Simulation 

[![Build Status](https://travis-ci.org/dvf/blockchain.svg?branch=master)](https://travis-ci.org/dvf/blockchain)


## Installation

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed. 
2. Install [pipenv](https://github.com/kennethreitz/pipenv). 

```
$ pip install pipenv 
```
3. Install requirements  
```
$ pipenv install 
``` 

4. Run the server:
    * `$ pipenv run python blockchain.py` 
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`
    
## Docker

Another option for running this blockchain program is to use Docker.  Follow the instructions below to create a local Docker container:

1. Clone this repository
2. Build the docker container

```
$ docker build -t blockchain .
```

3. Run the container

```
$ docker run --rm -p 80:5000 blockchain
```

4. To add more instances, vary the public port number before the colon:

```
$ docker run --rm -p 81:5000 blockchain
$ docker run --rm -p 82:5000 blockchain
$ docker run --rm -p 83:5000 blockchain
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
