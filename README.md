# Wraith - Dockerfile for for wraith Visual Regression Testing tool

## Usage

### (optional) Create an alias to run wraith

`alias wraith="docker run --rm -v $PWD:/wraithy -w='/wraithy' lopezs/wraith"`

### Test docker image is working

`wraith`  should display a list of wraith commands

### Initialiase Wraith

`wraith setup`

This will create folders  `configs` and `javascript` 

### Further reading
https://pantheon.io/docs/guides/visual-diff-with-wraith