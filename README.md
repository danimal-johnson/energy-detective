# Logging for The Energy Detective 1001

The Energy Detective (TED) 1001 was a device made by ______ to analyze your household power consumption and display the information on its built-in display, and over USB to a computer.

It suffered from a few limitations:
1. Communications used a proprietary protocol over USB. The TED device would only respond when polled.
2. The logging software was available only for Windows and had to be running 24 hours a day to be useful.
3. Some versions of the firmware require software with a registered serial number to run.
4. The company discontinued production and support, and has since removed all references to TED from its website.

## Goals

The ultimate goal of this project is to be able to attach a low-powered device such as a Raspberry Pi, Arduino, or ESP8266 to the TED through its USB port (or directly to the UART if necessary) to log the data and serve it over a wifi connection so power consumption can be tracked over time and analyzed.

## Resources

### Websites

### Hardware modification

### Protocol

## Challenges

* Converting polling software from Python 2 to Python 3.
* Determining how to store data and when to prune details.
* Finding best way to serve data (API or http server?)
