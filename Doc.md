# RLua Documentation

just a simple doc that helps me code i guess

## Print

print() is a lua/luau function that prints something to the console.

### Code Sample:

``` lua
print("Hello World!"); --> Hello World!
```


### Math Questions:

``` lua
print(1+1) --> 2
print(10-8) --> 2
print(8*8) --> 64
```

press f9 to open the console.
Your console should look something like this once you have run the script above.
![ConsolePrint](https://github.com/Owner1213/Rlua-doc/assets/137589536/af77a826-c314-4255-a0c1-f5c4032e8828)
## Warn
warn() is a lua/luau function similar to print() except that it prints something in a different color, looking like a warning.
### Code Sample:
``` lua

warn("Your car ran out of gas!"); --> Your car ran out of gas!
```
Your console should look like this:
![ConsoleWarn](https://github.com/Owner1213/Rlua-doc/assets/137589536/d587c91e-ba3b-4095-830f-ab1f51109b6b)
## Error
error is a different type of print, but instead it acts as a real error, stopping all the lines below it.
### Code Sample:
```lua
error("failed to load the script!")
```
if you try to print something after the error, it would look like this:
![ConsoleError](https://github.com/Owner1213/Rlua-doc/assets/137589536/2981c3b1-b6e8-48e7-b1f7-37a3c07a5e83)
## Variables
Variables are values to store things to make code a little easier.
### Code Sample:
```lua
local MyVariable = "Hi!"
print(MyVariable) --> Hi!
```
