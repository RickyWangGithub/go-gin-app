# Go gin app

This is the code from the article [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin).

# build

go mod init app
go build -o app
 # run
 
 ./app
curl -X GET -H "Accept: application/json" http://10.227.71.26:8080/article/view/1
