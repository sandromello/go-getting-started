
# go-getting-started

A barebones Go app, which can easily be deployed to Koli.

## Running Locally

Make sure you have [Go](http://golang.org/doc/install).

```sh
$ go get -u github.com/koli/go-getting-started
$ cd $GOPATH/src/github.com/koli/go-getting-started
$ go build
$ ./go-getting-started
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

You should also install [Godep](https://github.com/tools/godep) if you are going to add any dependencies to the sample app.