# HTTP Request and Response

## What is HTTP?

HTTP (HyperText Transfer Protocol) is a protocol used for communication between a browser and a server.

It defines how requests and responses are exchanged over the Internet.

## Request and Response

When we open a website:

1. The browser sends a request.
2. The request reaches the server.
3. The server processes the request.
4. The server sends a response back.

```text
Browser → Request → Server
Browser ← Response ← Server
```

## Example

When we open:

```text
https://google.com
```

The browser sends an HTTP request to Google's server.

The server returns an HTTP response containing the webpage data.

## DevTools Network Tab

The Network tab in browser DevTools helps us see:

- Requests sent by the browser
- Responses received from the server
- Loading time
- Status codes

It is useful for understanding how websites communicate with servers.

## Server

A Server is a computer that receives requests and sends responses.

Websites are hosted on servers.

## Summary

- HTTP is used for communication between browsers and servers.
- Browsers send requests and servers send responses.
- The Network tab helps inspect requests and responses.
- Servers host websites and return data to users.
