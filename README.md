## u need tmux

```bash
$ make bear # generate compile_commands.json for using vscode 
```
```bash
$ make # compile xv6-riscv
```
```bash
$ make qemu-gdb # in left window  
```
```bash
$ make debug # in right window
```
## learn tools
```
$ make -nB qemu | vim - # get makefile runtime parameters
 :set nowrap # not wrap in vim 
 :%s/ /\r /g # convert all apaces to line breaks
 :w expand_make.txt
```
