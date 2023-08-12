# Basic HTTP Server with Golang

This is a simple project to demonstrate how to create a basic HTTP server using Golang. The project includes two routes: `/hello` to display a "Hello from Golang" message from Golang, and `/form` to handle POST requests and display the results with Golang.

## Requirements

- Go (Golang) installed on your machine. You can download it from [here](https://go.dev/dl/).

## Getting Started

1\. Clone this repository to your local machine:

```bash\
git clone https://github.com/rizalthewebdev/basic-http-server-golang.git
```

2\. Navigate to the project directory:

```bash\
cd basic-http-server-golang
```

3\. Run the server:

```bash\
go run main.go
```

4\. Open your web browser and access the following routes:

- To display a "Hello from Golang" message: [http://localhost:8080/hello](http://localhost:8080/hello)
- To access the form: [http://localhost:8080/form](http://localhost:8080/form)

## Routes

### `/hello`

Accessing this route will display a "Hello from Golang" message generated by the Golang server.

### `/form`

Accessing this route will display a simple form that you can use to send a POST request. After submitting the form, the server will process the data and display the results with Golang.

## Example

1\. Access the `/hello` route: [http://localhost:8080/hello](http://localhost:8080/hello)\
   You will see a message: "Hello from Golang!"

2\. Access the `/form` route: [http://localhost:8080/form](http://localhost:8080/form)\
   Fill out the form and submit it. The server will process your request and display the results with Golang.