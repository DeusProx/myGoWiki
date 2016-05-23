# myGoWiki

This project is oriented on this tutorial [https://golang.org/doc/articles/wiki/] and implements a simple wiki using the standard http router and the standard template engine.

## 1. Getting started (Linux)
* install Git
* install go tools
* Create a workspace for go e.g. "~/go"
* Export the environment Variables. Pay Attention if you use another directory as workspace! You should also put them into your "~/.bashrc" and your "~/.profile" so they will be loaded automatically in the future.
```
export GOPATH="$HOME/go"
export PATH="$PATH:$GOPATH/bin"
```
* Get the Project and run it:
```
go get github.com/DeusProx/myGoWiki
cd $GOPATH/src/github.com/DeusProx/myGoWiki
go install
myGoRest
```
* You can also check this official golang tutorial: [https://golang.org/doc/code.html]

```
Developed by
    Gordon Lawrenz <lawrenz@dbis.rwth-aachen.de>
```
