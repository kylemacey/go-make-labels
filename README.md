# go-make-labels

This utility takes input from `example.json` and creates or updates labels on a
repository accordingly. Right now it's in a POC state.

## Disclaimer

This is the author's first attempt at a utility written in Go, so there's
certainly a lot of learning to do. Maybe don't count on this being excellent
software for the time being.

![I have no idea what I'm doing](https://user-images.githubusercontent.com/519171/45828811-7f984700-bcc7-11e8-8ff5-114ff55d9014.gif)


## Usage

Populate label configuration in `example.json` and run

```shell
export OCTOKIT_ACCESS_TOKEN=1234567890
go run main.go "kylemacey/go-make-labels"
```
