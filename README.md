# go-make-labels

This utility takes input from `example.json` and creates or updates labels on a
repository accordingly. Right now it's in a POC state. This is the author's
first attempt at a utility written in Go, so there's certainly a lot of learning
to do.

## Usage

Populate label configuration in `example.json` and run

```shell
export OCTOKIT_ACCESS_TOKEN=1234567890
go run main.go "kylemacey/go-make-labels"
```
