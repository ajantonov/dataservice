# dataservice
Data Processing Service

## Work with Docker 

### Build Image
    > docker build -t dataservice .

### Run Image
    > docker run --publish 8888:8888 --name dataservice --rm dataservice

### Stop Image
    > docker stop dataservice