# GDB stuff

## getting the contents of a register

info registers REGISTER

## reading bytes from memory

x/Xxb ADDRESS

X is number of bytes to read

xb => hex rep
c => char rep
s => read until hit the 0x0

## Get list of functions

info functions

## find the section of a symbol

info symbol SYMBOL

## Get adderss of a symbol

info adderss SYMBOL

disassemble SYMBOL (for functions)

## p/ formats

| Command   | Meaning                       |
| --------- | ----------------------------- |
| `p num`   | normal/default representation |
| `p/d num` | decimal                       |
| `p/u num` | unsigned decimal              |
| `p/x num` | hexadecimal                   |
| `p/t num` | binary                        |
| `p/o num` | octal                         |
| `p/c num` | character                     |
| `p/a num` | address                       |

## format specification

x/\[COUNT\]\[FORMAT\]\[SIZE\] address

## x sizes

b = byte       1 byte
h = halfword   2 bytes
w = word       4 bytes
g = giant word 8 bytes

## Notes

Endians matter bro
