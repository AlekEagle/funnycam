# Funnycam

![funnycam image](./funnycam.png)

It's a funny camera :^)

## Prerequisites

- [ffmpeg](https://www.ffmpeg.org/)
- [v4l2loopback](https://github.com/umlaeute/v4l2loopback)

## Installation

There isn't any installation required.

## Usage

funnycam expects 1 argument: the ID to the output video device, but will take a second argument if you want to specify the target input device.

```bash
# ./funnycam <output_device_number> [input_device_number]
$ ./funnycam 10
# random ffmpeg bullshit
```
