# ghidra-notes

Notes for noobs about using/extending Ghidra

## Extract Source Code

To extract the Ghidra source code into a single directory, run the following script inside the Ghidra directory:

### Linux
```
find . -name "*-src.zip" -exec unzip -d <path to destination> \{\} \; -print
```
