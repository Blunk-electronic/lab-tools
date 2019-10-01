# LAB-TOOLS
Various tools to access lab equipment such as meters, oscilloscopes, power supplies ...
Currently there is only one tool in the collection.

## HARDCOPY
This is a shell script that accesses a Tektronix scope and saves the screen in a BMP file.
Please find details in the script itself and the manuals [here](osc/manuals/).

### Installation
Just copy the script 'hardcopy' from directory 'osc' to $HOME/bin or somewhere else where your executables live.

### Usage
From the command line run this command to dump the current screen of your scope in a bitmap file:

```sh
$ sh hardcopy test.bmp
```

