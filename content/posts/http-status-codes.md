---
title: A look at HTTP Status Codes
seo_title: HTTP Status Codes
summary: All about some common and uncommon HTTP status codes
description: 
slug: http-status-codes 
author: Ishan Joshi

draft: false
date: 2023-11-17T21:21:46-05:00
lastmod: 2023-11-17T21:21:46-05:00
expiryDate: 
publishDate: 

feature_image: 
feature_image_alt: 

categories:
tags:
  - HTTP

toc: true
related: true
social_share: true
newsletter: false
disable_comments: false
---

HTTP (Hypertext Transfer Protocol) is the foundation of data communication on the World Wide Web. When you visit a website, your browser communicates with servers using HTTP to request and receive data. 

One crucial aspect of this communication is HTTP status codes. These codes are three-digit numbers returned by a server in response to a client's request. They convey information about the status of the request and guide the client on how to proceed. Let's explore some common HTTP status codes and their meanings:

### 1xx - Informational :bulb:

- **100 Continue:** The server has received the initial part of the request, and the client should continue with the rest of the request.

### 2xx - Success :white_check_mark:

- **200 OK:** The request was successful, and the server is returning the requested data.
- **201 Created:** The request has been fulfilled, and a new resource has been created as a result.
- **204 No Content:** The server successfully processed the request but is not returning any content.

### 3xx - Redirection :arrow_right_hook:

- **301 Moved Permanently:** The requested resource has been permanently moved to a new URL.
- **302 Found (Temporary Redirect):** The requested resource temporarily resides under a different URL.
- **304 Not Modified:** The resource has not been modified since the last request, and the client can use the cached copy.

### 4xx - Client Error :no_entry_sign:

- **400 Bad Request:** The server cannot process the request due to a client error, such as malformed syntax.
- **404 Not Found:** The requested resource could not be found on the server.
- **403 Forbidden:** The server understood the request but refuses to authorize it.

### 5xx - Server Error :skull:

- **500 Internal Server Error:** A generic error message indicating that the server encountered an unexpected condition.
- **502 Bad Gateway:** The server, while acting as a gateway or proxy, received an invalid response from an upstream server.
- **503 Service Unavailable:** The server is currently unable to handle the request due to temporary overload or maintenance.

Understanding these status codes is essential for web developers and system administrators to diagnose and troubleshoot issues efficiently. By interpreting these codes correctly, they can ensure smooth communication between clients and servers, leading to a better user experience on the web.

## Some (Un)common status codes 

HTTP status codes are not just technical responses; they can also be cool and creative. Here are some imaginative examples:

### 418 I'm a teapot :tea:

- **Definition:** This status code is defined in RFC 2324, Hyper Text Coffee Pot Control Protocol, as an April Fools' joke.
- **Example:** When a user tries to brew coffee using a teapot-shaped IoT device.
  ```http
  HTTP/1.1 418 I'm a teapot


### 420 Enhance Your Calm :relieved:

- **Definition:** Unofficial HTTP status code used humorously for when you need the client to chill out.
- **Example:** When a user sends too many requests per second to your API.
  ```http
  HTTP/1.1 420 Enhance Your Calm


### 500 Internet Server Error - We Lost Your Data :boom:

- **Definition:** A humorous take on the 500 Internal Server Error to acknowledge a data loss situation.
- **Example:** When a server crash results in data loss.
  ```http
  HTTP/1.1 500 Internet Server Error - We Lost Your Data


### 451 Unavailable For Coffee Break :coffee:

- **Definition:** A playful twist on the 451 status code to indicate that the server is unavailable because it's time for a coffee break.
- **Example:** When the server admin decides it's time for a coffee break, and maintenance begins.
  ```http
  HTTP/1.1 451 Unavailable For Coffee Break


