# SparkX GNSS Antenna Splitter (Power Divider) with DC Pass

<p align="center">
  <a href="https://github.com/sparkfunX/GNSS_Splitter/issues" alt="Issues">
    <img src="https://img.shields.io/github/issues/sparkfunX/GNSS_Splitter.svg" /></a>
  <a href="https://github.com/sparkfunX/GNSS_Splitter/actions" alt="Actions">
    <img src="https://github.com/sparkfunX/GNSS_Splitter/actions/workflows/mkdocs.yml/badge.svg" /></a>
  <a href="https://github.com/sparkfunX/GNSS_Splitter/blob/main/LICENSE.md" alt="License">
    <img src="https://img.shields.io/badge/license-CC%20BY--SA%204.0-EF9421.svg" /></a>
  <a href="https://twitter.com/intent/follow?screen_name=sparkfun">
    <img src="https://img.shields.io/twitter/follow/sparkfun.svg?style=social&logo=twitter" alt="follow on Twitter"></a>
</p>

[![SparkX GNSS Antenna Splitter (Power Divider) with DC Pass](https://cdn.sparkfun.com//assets/parts/2/0/9/9/2/21223-SPX01.jpg)](https://www.sparkfun.com/products/21223)

*[SparkX GNSS Antenna Splitter (Power Divider) with DC Pass (SPX-21223)](https://www.sparkfun.com/products/21223)*

The [SparkX GNSS Antenna Splitter (Power Divider) with DC Pass (SPX-21223)](https://www.sparkfun.com/products/21223) lets you connect a single GNSS antenna to two boards or modules. It splits (divides) the antenna signal from Port S equally between Port 1 and Port 2. It is the perfect accessory for our [NEO-D9S correction data receiver](https://www.sparkfun.com/products/19390), allowing you to feed both the NEO-D9S and a separate GNSS module from a single antenna.

Our board is based on the BP2G1+ 2-way 50Ω DC Pass Power Splitter from Mini-Circuits. It covers the L-band frequencies from 1200 to 2000 MHz. The three ports are equipped with robust standard-polarity SMA sockets. We have an SMA Male-Male adapter available as an accessory should you want to change any or all sockets into plugs.

By default, the splitter will pass DC power from Port 1 to the antenna (Port S) so you can power your active antenna. However, it is easy to change this if required:

* By opening Jumper 1 and closing Jumper 2, you can provide DC power from Port 2 instead.
* With Jumper 1 open, you can also provide DC power from either the on-board Qwiic connector or via the VCC and GND breakout pads.
* With Jumper 1 open and both Qwiic and VCC disconnected, you can use our board as a passive 50:50 signal divider or combiner.

If your antenna needs 3.3V, Qwiic could be a good choice for you. The VCC and GND breakout pads will allow you to feed in a higher voltage (e.g. 5V) if required.

We have included a 10Ω current-limiting resistor for the Qwiic and VCC power connections, to help prevent damage if the antenna cable becomes shorted. If your antenna needs more than approx. 30mA, you can close the I<sub>lim</sub> jumper to bypass the resistor.

## Repository Contents

* **[/Documents](/Documents/)** - BP2G1+ datasheet
* **[/Hardware](/Hardware/)** - Eagle design files (.brd, .sch), Schematic, Board Dimensions

## Product Versions

* [SPX-21223](https://www.sparkfun.com/products/21223) - SparkX GNSS Antenna Splitter (Power Divider) with DC Pass - Initial SparkX Release

## License Information

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
