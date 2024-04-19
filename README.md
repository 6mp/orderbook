# C++ limit order book with python visualizer

## Features
- C++ build is fully automated from fetching grpc/protoc to compiling protobufs to then the final executable
- Communication between the orderbook and python is done using grpc

## Setup

### Clone repo
```
git clone https://github.com/6mp/orderbook/
cd orderbook
```

### Building and running orderbook server:
```sh
mkdir build
cd build
cmake ..
make

./engine
```

### Running python visualizer:
1) Ensure orderbook is already running

```sh
cd interface
chmod +x ./run.sh
./run.sh
```
