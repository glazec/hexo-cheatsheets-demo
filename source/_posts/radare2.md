---
title: Radare2
categories: 
  - Binary Reverse
date: 2019-11-19
---

## get started

### run radare
``` bash
# to debug
r2 -d
```

### Analysis
```bash
#auto analysis functions
aaa
```

```bash
#print all functions
afl

#print the disassembly of current function
pdf
```

```bash
#control graph of the function
vv

# change different view
p 
```

### Navigation
```bash
#change current location
s sys.main
```
## debug

### Breakpoint
```bash
#set breakpoint
db <address>
```

### Instruction flow
```bash
#run program
dc

# step into [instructions]
s

#step over [instructions]
shift+s
```

### Help
```bash
#To get help,append ? to the end of any command
?
```