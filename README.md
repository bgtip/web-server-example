# An example, not entirely stable, web server

## Installing dependencies

### Debian based distributions
`sudo apt-get install git cmake make g++ libboost-thread-dev libboost-regex-dev libboost-date-time-dev`

### Arch Linux based distributions
`sudo pacman -S git cmake make boost`

### MacOS
`brew install cmake boost`

## Download source
```sh
git clone https://github.com/ntnu-idri2004/web-server-example
```

## Build
```sh
cd web-server-example
mkdir build
cd build
cmake ..
make
```

## Run
```sh
./web_server
```

### See web page
#### Alternative 1
Open `http://localhost:8080` in a web browser

#### Alternative 2
In a terminal:
```sh
telnet localhost 8080
GET / HTTP/1.1
                       # Press enter twice

```
