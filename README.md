# Rest Based Recovery Approach
Rest based recovery approach is a microservice architecture that help us to determine logs and metrixs of each service while it is communication withe other services.

# How to Run
To this microservice architecture you can use the docker-compose file. 

    docker-compose up -d

# Endpoints
In this microservice architecture we have two microservieces whose endpoints are the following.

## Book service
### Endpoints
save book:

    http://localhost:7070/books/

all books:

    http://localhost:7070/books/

bookById:

    http://localhost:7070/books/book/id/{id}

bookByIsbn:

    http://localhost:7070/books/book/isbn/{isbn}

all authors:

    http://localhost:7070/books/authors/

authorsById:

    http://localhost:7070/books/authors/author/id/{id}

authorsByName:

    http://localhost:7070/books/authors/author/name/{name}

## Author service
### Endpoints

all authors:

		http://localhost:7071/authors/

authorsById:

		http://localhost:7071/authors/author/id/{id}

authorsByName:

		http://localhost:7071/authors/author/name/{name}


# Technologies Used
we have some technologies that made our tasks easy. The following technologies are used.

1. Prometheus

    http://localhost:9090

2. Grafana

    http://localhost:3000

3. Zipkins

    http://localhost:9411

Currently we are using its latest version. but you can change according to your need. 
