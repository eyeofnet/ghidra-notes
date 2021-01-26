__toc__

# ghidra-notes

Notes to myself about using/extending Ghidra

## Extract Source Code

To extract the Ghidra source code into a single directory, run the following script:

### Linux
```
find . -name "*-src.zip" -exec unzip -d <path to destination> \{\} \; -print
```
