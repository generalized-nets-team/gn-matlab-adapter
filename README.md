# gn-matlab-adapter

GN Matlab Adapter allows GN characteristic functions and predicates to call Matlab functions. It is a Windows console application.

## Syntax

```
MatLabAdapter \<path to m file\> \<name of m file without .m\> \<output file\> [\<args file>\ [-d]]
```

## Requirements

Microsoft Windows and Matlab

Requires Administrator privileges in order to connect to MatLab engine. In Windows 7 you have to explicitly select "Run as Administrator" no matter what type of account you are using.

In Project Settings in VS or in MatLabAdapter.vcproj you should set correct paths to the MatLab directories.
