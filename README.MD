# Ricoh MP C4503 macOS compatible PXL driver

Since the school printer does not have a PS language extension card, this
driver provides PCL XL support for macOS users in school, based on
[pxlcolor-Ricoh](http://www.openprinting.org/driver/pxlcolor-Ricoh/)
from [openprinting.org](http://www.openprinting.org/). MIT Licensed

### Supported Printers in GDS

Theoretically, the driver should work fine on any of the following printers:
(Data from school's iPrint)

| Printer Name                   | Printer Location               |
|--------------------------------|--------------------------------|
| Library Color                  | Media Center Library           |
| Lower School 3rd Grade         | Lower School 3rd Grade         |
| Lower School 4th Think Tank    | Lower School 4th Think Tank    |
| Teacher Workroom Middle School | Teacher Workroom Middle School |
| US Commons                     | Upper School Commons Up        |
| Writing Center                 | Writing Center Upper School    |

We've only tested the driver on the printers below

| Printer Name                   | Printer Location               |
|--------------------------------|--------------------------------|
| Library Color                  | Media Center Library           |
| US Commons                     | Upper School Commons Up        |
| Writing Center                 | Writing Center Upper School    |

### Download

Check the [Releases](https://github.com/GreensboroDaySchool/MP-C4503-macOS-pxlcolor/releases)
for stable versions. We recommend everyone to use the .pkg installer, it will
guide you through installing dependencies to add printer drivers.

### Install

1.  Secondary click (right click) on `MP-C4503-macOS-pxlcolor.pkg`, then click
    *Open*
2.  Follow the steps of the installer and complete the wizard

### Add Printers

1.	Open "System Preference"
2.	Click "Printers & Scanners"
3.	Click the "+" button on the bottom left of the printer list area
4.	If a selection list appeared, click "Add Printer or Scanner..." if not,
    jump to 5
5.	You should see a new dialog titled "Add". Click the "IP" button with a glob
    icon on the top of the dialog
6.	Enter the IP address of the printer into the "Address" text field, you can
    find the IP address on each printer. It is usually blinking on the bottom
    left area of the screen on the printer, and formatted like "10.35.0.18"
7.	Select "Line Printer Daemon - LPD" as the Protocol
8.	Fill the "Queue" text field with "lp"
9.	Fill the "Name" and "Location" with whatever text you like
10.	Choose "Ricoh MP C4503 PXL" in the "Use" selection menu
11.	Click "Add"

### Printer IP Addresses

Here is a list of the IP addresses found on the printers.

| Printer Name                   | Printer IP Address             |
|--------------------------------|--------------------------------|
| Library Color                  | 10.35.0.18                     |
| US Commons                     | 10.20.0.95                     |
| Writing Center                 | 10.20.0.92                     |
