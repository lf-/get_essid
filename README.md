# get_essid
A simple program to get the ESSID that an interface is connected to. Implemented in standard C and completely independent of network manager.

## Usage
`get_essid interface`

Gets the ESSID of that interface. If it's not wireless, it will error out with an operation not supported.

## Requirements

* ~~Nothing~~

* A Linux kernel

* A compiler

## Using it

```bash
make
cp get_essid /wherever/you/want/it
```
