# extract
Simple script to extract the archives. Lazily selects a command and arguments based on the file extension.  
Supports:
* ```tar.gz```
* ```tar.bz2```
* ```tar.xz```
* ```tar.lz```
* ```tar.lzma```
* ```tar```
* ```zip```

## Installation
Run the install script
```bash
sudo ./install
```

## Usage
```bash
extract SOURCE [DEST]  
```
If no destination is given then extract to same directory

## Roadmap
Add support for additional file extensions

## License
[MIT](https://choosealicense.com/licenses/mit/)
