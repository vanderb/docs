# Configuration — HTTP dumps

It's an indispensable tool that simplifies the process of capturing, analyzing, and debugging HTTP requests in their
applications. With the HTTP Requests Dump Server, developers can effortlessly capture all the relevant request data and
gain valuable insights. They can dive deep into the captured requests, examine their contents, and pinpoint any issues
or anomalies that might be affecting their application's performance.

Simply start the server and send your requests to the `http://http-dump@127.0.0.1:8000` URL, it will not only
capture the URI segments but also gather additional details such as the request `headers`, `cookies`, `POST data`,
`query strings`, and any `uploaded files`.

For instance, let's say you have a POST request: `http://http-dump@127.0.0.1:8000/user/3/update`. In this case,
server will intercept the request and capture all the relevant information. It will then display the
dumped data, allowing you to examine the request details, including the URI segments (`user/3/update` in this example).

![HTTP Requests dump server](https://github.com/spiral/docs/assets/773481/209f9c8c-00d2-4086-9f54-ce2cf8121394)