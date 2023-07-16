# HTTP_Status_code
A comprehensive collection of HTTP status codes and meanings. Get detailed explanations, code samples, and practical use cases for web apps, APIs, and network protocols. Suitable for beginners and experienced developers, it helps you handle status codes effectively.

# HTTP Status Codes

HTTP Status Codes Repository is a comprehensive collection of the most commonly used HTTP status codes and their meanings. This repository aims to provide developers and web enthusiasts with a centralized and accessible resource for understanding and effectively handling these status codes in their applications.

## Introduction

HTTP, or Hypertext Transfer Protocol, is the protocol used for communication between a client (e.g., a web browser) and a server. When a client makes a request to a server, the server responds with an HTTP status code to indicate the outcome of the request. Status codes are three-digit numbers grouped into different categories, each conveying a specific meaning.

**This repository serves as a handy reference guide for understanding the most used HTTP status codes, their purposes, and how they can be handled in different scenarios.**

![http_codes](https://github.com/JubairRahman/HTTP_Status_code/assets/84774437/fc44e206-a5a9-4b01-ade5-e9f9fc53d074)


## Most Used HTTP Status Codes

### Informational Responses - 1xx

Informational responses indicate that the server has received the request and is still processing it. These responses are not commonly used in everyday scenarios.

### Successful Responses - 2xx

Successful responses indicate that the client's request was successfully received, understood, and processed by the server.

- **200 OK**: The request was successful, and the server has returned the requested resource.
- **201 Created**: The request was successful, and a new resource has been created (commonly used for POST requests).
- **204 No Content**: The server has successfully processed the request, but there is no content to return (suitable for DELETE requests).

### Redirection Responses - 3xx

Redirection responses indicate that the client needs to take additional actions to complete the request.

- **301 Moved Permanently**: The requested resource has been permanently moved to a new location.
- **302 Found**: The requested resource is temporarily located at a different URL.
- **304 Not Modified**: The client's cached copy of the resource is still valid, and there is no need to retrieve it again.

### Client Error Responses - 4xx

Client error responses indicate that there was an issue with the client's request.

- **400 Bad Request**: The server could not understand the client's request due to invalid syntax or other client-side errors.
- **401 Unauthorized**: The client must authenticate itself to access the requested resource.
- **403 Forbidden**: The client is authenticated, but it does not have permission to access the requested resource.
- **404 Not Found**: The requested resource could not be found on the server.
- **405 Method Not Allowed**: The requested method (e.g., GET, POST, PUT, DELETE) is not allowed for the given resource (suitable for API development).

### Server Error Responses - 5xx

Server error responses indicate that there was an issue on the server side while processing the request.

- **500 Internal Server Error**: An unexpected error occurred on the server.
- **501 Not Implemented**: The server does not support the functionality required to fulfill the request.
- **502 Bad Gateway**: The server acting as a gateway or proxy received an invalid response from an upstream server.
- **503 Service Unavailable**: The server is temporarily unable to handle the request due to maintenance or overloading.
- **504 Gateway Timeout**: The server acting as a gateway or proxy did not receive a timely response from an upstream server.

## How to Contribute

Contributions to this repository are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository and create a new branch for your changes.
2. Make your desired changes to the status code descriptions, code snippets, or any other relevant sections.
3. Ensure that your changes adhere to the repository's formatting and style.
4. Submit a pull request, explaining the purpose and impact of your changes.



## Feedback and Support

If you have any feedback, suggestions, or questions, please open an issue in the repository. We are here to help!

Happy coding!
