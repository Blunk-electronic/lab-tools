# LAB-TOOLS
Various tools to access lab equipment such as meters, oscilloscopes, power supplies ...
Currently there is only one tool in the collection.

## HARDCOPY
This is a shell script that accesses a Tektronix TDS320 scope and saves the screen in a BMP file.
Please find details in the script itself and the manuals [here](osc/manuals/). The scope must be
connected with your computer via a RS232 cable or an USB-to-RS232 adapter cable.

### Installation
Just copy the script 'hardcopy' from directory 'osc' to $HOME/bin or somewhere else where your executables live.

### Usage
From the command line run this command to dump the current screen of your scope in a bitmap file.
The argument right after 'hardcopy' is the interface (such as /dev/ttyS0 or /dev/ttyUSB0). The next argument is the file
you want to dump the screen into.

```sh
$ sh hardcopy /dev/ttyUSB0 test.bmp
```

If the permissions of 'hardcopy' are set so that it can be executed directly via a command like
```sh
$ chmod hardcopy 755
```

Then the 'sh' can be omitted:
```sh
$ hardcopy /dev/ttyUSB0 test.bmp
```


## COLLABORATION
Your feedback and contributions are highly welcome to extend this collection.

