# blender-farm

## Running
The script will run in an infinite loop and monitor the directory $FARM_PATH/todo. If you want to stop the process, create a file called "kill" to the $FARM_PATH/todo directory.

## Configuration
By default the blender-farm script will use the `$HOME/blender-farm` directory for its activities, but this can be changed by setting the `FARM_PATH` environmental variable before calling the script.

## Installation
To install blender-farm to /usr/local/bin, run the following
```sh
make install
```
You can customize the installation prefix with the PREFIX variable like so
```sh
make PREFIX=/usr install
```

## Uninstall
```sh
make uninstall
```
