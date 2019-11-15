# PoolEdit (distributable for users)

PoolEdit XML Graphical User Interface Editor for creating ISOBUS
object pools. In the ISO 11783 standard, the term _object pool_ refers
to a collection of graphical user interface objects which make up the
GUI. So to create ISOBUS user interfaces a tool is needed to edit the
object pool, hence the name PoolEdit.

As the standard defines only a binary format, a second tool called
[PoolEditParser](https://github.com/moehman/PoolEdit) is used to read
the XML files and write binary ISOBUS object pools.

The editor uses XML format internally as an editable data structure
and externally as a file format. The PoolEdit XML format is based on
the IsoAgLib format with some minor changes.

![Drive screen](drivescreen.png)

Please read the manual for more information!

Current development environment:
* OS: Windows 7 (but should work on Windows 10 as well)
* IDE: NetBeans 11.2
* Java: jdk-13.0.1