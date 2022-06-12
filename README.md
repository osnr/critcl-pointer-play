# critcl-pointer-play

more weird experiments with critcl... getting opaque pointer out of C
and passing it back in

kind of weird to me that they don't support this in critcl and i have
to hack it in, it feels like basic functionality if you want to
interop with C (LuaJIT can do something very similar with its FFI)

on my computer (need Tcl 8.6 and critcl):
```
$ /opt/homebrew/Cellar/tcl-tk/8.6.12_1/bin/tclsh critcl-pointer-play.tcl
got pointer from C: (void*) 0x100e07f83
text at pointer: [Hello]
```
