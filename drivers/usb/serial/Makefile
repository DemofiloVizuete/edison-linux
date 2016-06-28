#
# Makefile for the USB serial device drivers.
#

# Object file lists.

obj-$(CONFIG_USB_SERIAL)			+= usbserial.o

usbserial-y := usb-serial.o generic.o bus.o

usbserial-$(CONFIG_USB_SERIAL_CONSOLE)	+= console.o

obj-$(CONFIG_USB_SERIAL_CH341)			+= ch341.o
