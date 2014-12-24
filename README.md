revelSkeleton
============

## Update [Revel Framework](http://revel.github.io) skeleton

### default skeleton
- Bootstrap v2.1.1
- jQuery v1.9.1

### this skeleton
- Bootstrap v3.3.1
- jQuery v2.1.1

####Add
- Lo-Dash v2.4.1

## Usage
```
$ go get github.com/revel/revel
$ go get github.com/revel/cmd/revel

$ go get -d github.com/s-nlf-fh/revelSkeleton
$ cd [GOPATH]/src/github.com
$ mv revel/revel/skeleton revel/revel/skeleton_old
$ cp -r s-nlf-fh/revelSkeleton/skeleton revel/revel/

$ cd [GOPATH]/src
$ revel new myapp
```
