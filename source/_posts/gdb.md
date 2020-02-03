---
title: GDB
categories: 
  - Binary Reverse
date: 2019-10-02
version: 8.3.1
---

## get started

### Configuration

```bash
# the configuration file is ~/.gdbinit
set disassembly-flavor intel
```

### Analysis
```bash
#disassemble main function
disassemble main
```

```bash
#look at the register
info registers
```

```bash
#change register's value
set $eax=0
```
### Instruction flow

```bash
#run the program with given argument
run <argument>

#step into one instructions
#(will step into function calls)
si

#step over one instructions
#(will *not* step into function calls)
ni
```

### Breakpoint
```bash
#set breakpoint at main function
break *main
```

examin win function
x win

print win fucntion
f win