DynamicLoadDLL
==============
This is the class "dld : dynamic load dll" Documentation.

File
-------
```
dld.cs is the body class.
CV.cs is use to show how to use the dld class.
dll folder is use to show how to export a dll in C++.
```

The most important part of dll is the "Entry Point", 
you can use the command line tools : "dumpbin" in visual C++ to inquire the entry point.

In cpp file, if you want to export to C#, you should be export to \_stdcall. If you want to export to C or C++,
you should be export to \_cdecl(and you can use LoadLibrary API).