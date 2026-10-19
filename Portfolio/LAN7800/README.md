# LAN7800 — USB 3.0 to Gigabit Ethernet Adapter

**Four-layer Altium PCB | High-speed interface routing | Design review | Manufacturing handover**

[Back to the engineering portfolio](../../README.md) · [Detailed LAN7800 project and engineering evidence](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio)

This case study illustrates the development of a Microchip LAN7800-based USB 3.0 to Gigabit Ethernet adapter, from board-level architecture and component selection through PCB design, review, manufacturing preparation and document control. **Hardware revision: Rev A.**

![LAN7800 Rev A Altium 3D PCB view](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/raw/main/Images/PCB_3D.PNG)

*Rev A board design shown in Altium Designer; a CAD view, not a claim of assembled-hardware validation.*

## Engineering process

![Six-stage LAN7800 engineering workflow](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/raw/main/Images/Portfolio/LAN7800_Engineering_Workflow.svg)

The project documents six stages: system definition, component engineering, hardware development, design review, manufacturing preparation, and document control and handover. [Explore the detailed workflow and evidence](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio#engineering-workflow--process).

## Architecture and PCB implementation

The adapter connects a USB 3.0 host interface to Gigabit Ethernet using the **Microchip LAN7800**. The Altium schematic is organized into USB/power and LAN7800/Ethernet sections. The four-layer PCB brings together the USB connector, LAN7800 circuitry, Ethernet MagJack and power distribution.

![LAN7800 top-layer PCB layout](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/raw/main/Images/PCB_Layout_Top.PNG)

High-speed design considerations include differential-pair rules, impedance profiles, matched-length constraints and return-path planning. These are documented as **design constraints and implementation evidence**, not as measured signal-integrity or compliance results.

[Native Altium project](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Hardware/Altium) · [Stack-up and impedance documentation](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Manufacturing/07_Engineering/Stackup) · [Routing-rule screenshots](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Images/Design_Rules)

## Design review and verification records

Separate **schematic and PCB design reviews** document checks, comments, evidence and dispositions. The reviews are recorded as revision 1.1 with closed review status. Their completion does not imply that physical hardware qualification or compliance testing has been performed.

[Read the schematic and PCB review records](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Manufacturing/07_Engineering/Design_Review)

## Manufacturing preparation

The Rev A manufacturing evidence includes a component BOM/AVL, component placement workbook, Gerber X2 artwork, drill files, fabrication and assembly drawings, and inspection/test documentation templates.

| Engineering deliverable | Detailed evidence |
| --- | --- |
| Component selection and BOM | [Rev A BOM workbook](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/blob/main/Manufacturing/01_BoM/LAN7800_USB_Ethernet_RevA_BOM.xlsx) |
| PCB fabrication artwork | [Gerber X2 outputs](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Manufacturing/02_GerberX2) |
| Assembly placement | [CPL workbook](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/blob/main/Manufacturing/03_CPL/LAN7800_USB_Ethernet_RevA_CPL.xlsx) |
| Fabrication and assembly | [Manufacturing package](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Manufacturing) |
| Production test and quality | [Procedures and blank records](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/tree/main/Manufacturing/08_Test_Quality) |

These files demonstrate **manufacturing preparation and handover documentation**. Blank test records should not be interpreted as completed test results.

## Document control and traceability

A five-sheet **USBGE-CTRL-001** document-control register tracks engineering documents, manufacturing files, native source references and revision history. File references and SHA-256 checksums support traceability.

The register is **Rev 1.0 — For approval**; formal approval fields remain blank. It describes the *complete controlled Rev A package*, which includes some files intentionally excluded from the public GitHub subset. In particular, **USBGE-FAB-001 fabrication instructions are not publicly included**.

[View the document-control register](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio/blob/main/Manufacturing/USBGE-CTRL-001_Document_Control_Register.xlsx)

## Explore the complete project

For the complete six-stage write-up, CAD evidence, engineering reviews and curated manufacturing deliverables, visit the **[LAN7800 project repository](https://github.com/CDonohoe-Designs/USB3-Gigabit-Ethernet-Adapter-Portfolio)**.

[Back to portfolio documents](../README.md) · [Back to main portfolio](../../README.md)
