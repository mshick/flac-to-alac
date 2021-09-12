# flac-to-alac

A simple bash script to convert a folder of `flac` files to `alac` files.

## Installation (on macOS)

This has two system dependencies, `nq` a simple CLI queuing util, and `ffmpeg` to perform the lossless conversion.

```sh
$ brew bundle install
```

## Usage

```sh
$ ./flac-to-alac -i infolder -o outfolder
```
