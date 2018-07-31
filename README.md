# istanbul-tools-docker

## Usage
`docker run -ti councilbox/istanbul-tools [global options] command [command options] [arguments...]`
```
COMMANDS:
     extra    Istanbul extraData manipulation
     setup    Setup your Istanbul network in seconds
     help, h  Print this message

GLOBAL OPTIONS:
   --help, -h  show help
```

## Decode extraData
```
docker run -ti councilbox/istanbul-tools extra decode --extradata 0x...
```
```
./decode-extradata.sh 0x...
```
