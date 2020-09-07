# Execsub

Execute a command in every subdirectory. 

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

