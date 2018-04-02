[![GoDoc](https://godoc.org/github.com/bruno-chavez/restedancestor?status.svg)](https://godoc.org/github.com/bruno-chavez/restedancestor)
[![Go Report Card](https://goreportcard.com/badge/github.com/bruno-chavez/restedancestor)](https://goreportcard.com/report/github.com/bruno-chavez/restedancestor)

![Torch](docs/images/dd.png)

`restedancestor` is a pretty simple REST API, delivers quotes from the Ancestor of the Darkest Dungeon in JSON format.

## Installation

### Linux

#### From source code:

Requires Go to be installed on your machine. You can install Go from
https://golang.org/doc/install

Once installed, and with a correctly configured GOPATH, on a terminal type:

```
$ go get github.com/bruno-chavez/restedancestor
```

Then go to:

```
$GOPATH/src/github.com/bruno-chavez/restedancestor
```

And last, on a terminal type:

```
$ go install
```

## Updating

To update `restedancestor` simply type:

```
$ go get -u github.com/bruno-chavez/restedancestor
```

## Usage

Once installed type on a terminal `restedancestor` and you should see a message like this:

```
Welcome to restedancestor, the API is running in a maddening fashion!
The Ancestor is waiting and listening on port 8000 of localhost
```

You can communicate with the API in various ways, for example going to your browser and typing on your serach bar `localhost:8000`, followed with one of the routes listed on the Routes seccion, if succesful you should see something like this:

![browser image](docs/images/browserImage.png)

## Routes

`rquote` accepts the `GET` method and returns a random quote.

```
{
"quote": "Beacons in the darkness, stars in the emptiness of the void."
{
```

`allquote` accepts the `GET` method and returns all the quotes in the API.

```
[
{
"quote": "Brigands have the run of these lanes, keep to the side path, the Hamlet is just ahead."
},
{
"quote": "Dispatch this thug in brutal fashion, that all may hear of your arrival!"
},
...
}
]
```

## Notes

This is a pretty small and niche project, created mainly to have fun,
so do that!

Only tested on Linux.

Sister project of [ancestorquotes](https://github.com/bruno-chavez/ancestorquotes).

Current version: `0.2`

## Contribute

Found an bug or an error? Post it in the [issue tracker](https://github.com/bruno-chavez/ancestorquotes/issues).

Want to add an awesome new feature? [Fork](https://github.com/bruno-chavez/ancestorquotes/fork) this repository and add your feature, then send a pull request.

## License
The MIT License (MIT)
Copyright (c) 2018 Bruno Chavez
