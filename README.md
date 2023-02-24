# Example: Haskell + CGI

Run CGI scripts within haskell webserver

## Run

Start the server

```shell
cabal run
```

Execute the `hello` cgi script:

```shell
curl http://localhost:2345/hello
```
