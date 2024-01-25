## How to use this GitHub Application?

* Run `go run config.go issue_comment.go main.go` in one terminal, this will start the server.
* Run `smee -u <smee-webhook-proxy-url goes here> -t http://127.0.0.1:8080/` to start the smee client.
* Now this Application reacts to all the PR comments made within a repository where this App is installed.
