
# Make a random folder to keep all this

# Check if Cmake is installed
```
https://cmake.org/install/
```

# Download ITK library
```
git clone https://github.com/InsightSoftwareConsortium/ITK.git
```

## Create a folder called 
```
\ITK\build
```

### Go to build
```
cd \ITK\build
```

### Cmake the files (prepping the C files)
```
ccmake .. 
```

### Once successful, make the binaries
```
make 
```
## Bin folder will be made in the root ITK folder.  See if .exe files are there.

###################################################

# Download RTK library
```
git clone https://github.com/SimonRit/RTK.git
```
## Create a folder called 
```
\RTK\build
```
### Go to build
```
cd \RTK\build
```

### Cmake the files (prepping the C files)
```
ccmake .. 
```

### Once successful, make the binaries
```
make 
```

## Bin folder will be made in the root RTK folder.  See if .exe files are there.


## License
[MIT](https://choosealicense.com/licenses/mit/)
