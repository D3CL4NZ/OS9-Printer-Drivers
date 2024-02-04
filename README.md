# OS9 Printer Descriptions
Custom ported printer descriptions for modern printers to be used on Classic MacOS.

More printer descriptions coming soon!

## Instructions:
1. Download the description for your printer.
2. UnStuff the archive on the target computer.
> IMPORTANT: Don't do this step on your modern computer as this will corrupt the resource fork
3. Place the expanded printer description in `Macintosh HD:System Folder:Extensions:Printer Descriptions:`.
4. Open **Desktop Printer Utility**
> Usually located in `Macintosh HD:Apple Extras:Apple LaserWriter Software:`
5. Create a new printer and select **Line Printer Daemon (LPD)**.
6. Select the downloaded printer description and enter the IP address and queue for your printer.
> The queue is usually called something like `BINARY_P1` or `POSTSCRIPT_P1`
7. Print using the newly added printer.
