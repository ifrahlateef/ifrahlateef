# Project Title

This project is intented to help readers save their time aswell as the resources by simply using this 
Book search App. It allows the user to explicitly search the desired book and then it returns the 
details about the book searched.
Example:Name of the Author, Publisher, Published date, Page count, Price of the book and many more.

## Getting Started

The instructions below will help you get the understanding of the project and how you can run on your 
local machines for development and testing purposes. For deployment refer notes on how to deploy 
project on live system.

### Prerequisites

The project uses REST API, flask which is a python's micro framework, JSON(Java Script Object Notation)
And for the communication between program and Database we used SQLAlchemy.
 
 
### Installation

flask can be installed  using the command
pip3 install flask 
JSON syntax is derived from Java Script object notation syntax

`code`

#### only uncomment on first run otherwise database would be overwritten

`code`

[googleapis](URL = 'https://www.googleapis.com/books/v1/volumes')

`code`

### Deployment


### Built With

[Kubernetes](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)
apiVersion: v1
type: LoadBalancer
ports:
protocol: TCP
port: 80
targetPort: 80
nodePort: 30000