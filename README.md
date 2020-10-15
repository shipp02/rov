# ROV Controller

This will use zmq to communicate over tcp in order to provide reliabel communication with **Remotely Operated Vehicle** (ROV)

## How to build

- Install conan using ``pip3 install conan``
- Install cmake using ``brew install cmake``
- If you do not have Homebrew install it using 
``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"``


```` 
mkdir build && cd build 
conan install .. 
cmake ..
make
````

