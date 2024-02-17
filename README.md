# UPmap [![MIT License](https://img.shields.io/badge/License-MIT-a10b31)](https://github.com/NotWithering/upmap/blob/master/LICENSE)

**UPmap** is a program that will automatically update your Planetarium planet when you save to the PMap file you bind to

## Installing

### All platforms
```bash
go install github.com/NotWithering/upmap@latest
```

## Usage
```bash
$ upmap --help
Usage of upmap:
  -file string
        The map file
  -id int
        The id of the planet
  -now
        Skip checking for update, just update it now
  -silent
        Don't print that its updating
  -space string
        The spaceship cookie
```

## Example
```bash
$ upmap -file mymap.pmap -id 54 -space <your spaceship cookie value> &
$ echo "<game version='1'>\n</game>" > mymap.pmap
updating...updated
```

## What the freak does UPmap mean?
**U*****P***date ***P****Map*

## How the flip is it pronounced?
idk dude i pronounce it as "up map" or you can say it as "u pmap" i dont really care