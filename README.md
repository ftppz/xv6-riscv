## u need tmux

```bash
$ make bear # generate compile_commands.json for using vscode 
```
```bash
$ make # compile xv6-riscv
```
if u want to debug for else, please delete two hard breadpoints in init.py and add new hard breakpoint.
```bash
$ make qemu-gdb # in left window run it
```
```bash
$ make debug # in right window run it
```
## learn tools
```
$ make -nB qemu | vim - # get makefile runtime parameters
 :set nowrap # not wrap in vim 
 :%s/ /\r /g # convert all apaces to line breaks
 :w expand_make.txt
```
