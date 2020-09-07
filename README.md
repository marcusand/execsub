# Execsub

Execute a command in each subdirectory. 

## Installation

Drop `execsub` somewhere where it is accessible through the PATH variable and make it executable (`chmod +x`).

## Usage 
```sh
cd <parent folder>
execsub "<command>"
```

## Configuration
In order to exclude certain subdirectories create a `.env` file with 
```
SKIP=<folderToSkip>/,<folderToSkip>/,<...>
```

