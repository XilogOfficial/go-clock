# go-clock
 Alternative to tty-clock which kinda sucks. Written in Go (first Go app!)
 
## Compatibility
- Linux
- Darwin (untested)
- Windows (untested)

Needs unicode

## Installation
If you had go installed properly,
```
go build .
go install .
go-clock
```
But I am stupid so if you just build it and move the binary to /usr/bin/go-clock it works.  
Or just run it in the folder you're in with `./go-clock`

## Usage
`go-clock -h` to see help for all available flags.  
`go-clock` default settings  
`--color=<c>` <c> is the foreground color. (white, red, yellow, green, mint, cyan, teal, blue, purple, magenta, violet, pink, black, grey, gray) Default = white  
`--seconds` Enables the seconds digits  
`--font=<f>` Font. (█default, ║pipe, ┃line) Default = default
