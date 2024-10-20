# Balthazar

Open-hardware laptop computer modules description and concept.

These are electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access. See the [main repository](https://github.com/balthazar-space/balthazar) for other designs.

# Unifying-PCB

Unifying PCB expansion for Balthazar 

Single PCB solution for connecting the three previously designed Balthazar modules (I/O, power supply, USB 2.0, 3.0 controllers, keyboard and adding Compute Module compatible FPGA boards. Aimed at setting a compatibility standard to widely accepted hardware standards.
It has standardized 100 pin accomodating module for adding standard CM HAT modules based on ARM or FPGA 
It has GPIO expansion port, HDMI,2x USB 3.0, Ethernet RJ45 and a microSD card slot.  

It is designed to accomodate ULX4M-CM4-HAT designed by Radiona.org using HDR 100 POS SMT board to board mezzanine connectors.

dimensions: 120x80 mm
placement: right back side of Balthazar casing

![TOP](/images/Unifying_v02_top.png)

![BOTTOM](/images/Unifying_v02_bottom.png)

## License

All resources except the keyboard firmware - which is licensed with with GPLv3 or later - licensed under the CERN Open Hardware Licence CERN-OHL W V.2.0

Version 2.0 of the CERN-OHL introduces three variants of the licence – strongly (S) reciprocal, weakly (W) reciprocal and permissive (P) – which aim to address specific constraints caused by different collaboration models currently used in open-hardware projects. 

The first two variants mean that if any product is made using an open hardware design, the design of that product, including any improvements or modifications, should be made available under the same licence as that of the original product. Permissive licences do not impose this condition.

See the [LICENSE.md](./LICENSE.md) file for more information.

## Funding

This project is funded through the [NGI Zero Entrust Fund](https://nlnet.nl/entrust), a fund
established by [NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) program. Learn more on the [NLnet project page](https://nlnet.nl/project/Balthazar-Casing/).

[<img src="https://nlnet.nl/logo/banner.png" alt="NLNet foundation logo" width="300" />](https://nlnet.nl)
[<img src="https://nlnet.nl/image/logos/NGI0Entrust_tag.svg" alt="NGI0 Entrust Logo" width="300" />](https://nlnet.nl/entrust)
