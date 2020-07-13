## Async Hooks Demo

An app to demonstrate the basics of working with the async hooks API in web request context handling, akin to thread based storage in multi-threaded environments.

### Getting Started

1. Clone the repository:

```bash
git clone git@github.com:Allan690/async-hooks-demo.git
```

2. Install the dependencies:

```bash
npm install
```

3. Then run the app:

```bash
npm start
```

Make a curl request to http://localhost:3000 . This should log some data on your terminal as shown:

```bash
$ curl http://localhost:3000
{"requestId":"df0e321c-6bcd-4f66-a857-9e8df7ca291c","data":{"headers":{"host":"localhost:3000","user-agent":"curl/7.64.1","accept":"*/*"}}}%
```
