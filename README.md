# YetAnotherUSBHub
A 4-port low cost USB 2.0 hub with upstream USB-C and downstream USB-A x2, USB-C, and microSD.
wip onshape: https://cad.onshape.com/documents/d3076bcf5bdf960a68612e95/w/1076ab7133259d721c6eb065/e/0b541aa8461793eb55190b47?renderMode=0&uiState=6a0653a430b61269bd2de70a

## Motivation
This is not meant to be a commercially viable or even usefully viable project for most people; I made this project mainly to learn about how to use USB and microSD,
routing differential pairs, etc. This was a fun project, not a thing that you would probably want to be using.

## Repo Structure
`cad`: CAD files\
`pcb`: The KiCad PCB design files, and gerbers in `pcb/production`\
`bom.csv`: The BOM needed to assemble the PCB\

## BOM
|Item                               |Unit Price (AUD)|Quantity|Extended Price (AUD)|Extended Price (USD)       |Notes      |Link                                                 |
|-----------------------------------|----------------|--------|--------------------|---------------------------|-----------|-----------------------------------------------------|
|100nF 0402 capacitor               |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C60474.html      |
|10uF 0402 capacitor                |0               |7       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C315248.html     |
|onsemi NSR0320MW2T1G               |0.16            |10      |1.6                 |1.18                       |MOQ 10     |https://www.lcsc.com/product-detail/C48192.html      |
|Green 0402 LED                     |0               |1       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C598352.html     |
|Molex 67643-2911                   |1.34            |2       |2.68                |1.92                       |N/A        |https://www.lcsc.com/product-detail/C293351.html     |
|Molex 104031-0811                  |1.05            |1       |1.05                |0.75                       |N/A        |https://www.lcsc.com/product-detail/C585350.html     |
|Korean Hroparts Elec TYPE-C-31-M-12|0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C165948.html     |
|1K 0402 resistor                   |0               |1       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C106235.html     |
|5.1K 0402 resistor                 |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C105872.html     |
|56K 0402 resistor                  |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C114756.html     |
|CoreChips SL2.1A                   |1.65            |1       |1.65                |1.18                       |N/A        |https://www.lcsc.com/product-detail/C192893.html     |
|GENESYS GL823K-HCY04               |0.64            |1       |0.64                |0.46                       |N/A        |https://www.lcsc.com/product-detail/C284879.html     |
|TPD2E2U06DCK                       |0.21            |3       |1.05                |0.76                       |MOQ 5      |https://www.lcsc.com/product-detail/C1855726.html    |
|TPD6F003                           |0.93            |1       |0.93                |0.67                       |N/A        |https://www.lcsc.com/product-detail/C2863873.html    |
|2mm acrylic sheet                  |6.25            |1       |6.25                |4.53                       |200x200x2mm|https://www.aliexpress.com/item/32817321651.html     |
|PCB                                |-               |5       |-                   |5.3                        |N/A        |https://jlcpcb.com                                   |

## Cost
BOM (1 board + case): LCSC[6.92 USD + 3 USD handling + 9.38 USD shipping = 19.3 USD] + AliExpress[4.53 USD] = 23.83 USD\
PCB: 2 USD + 3.3 USD shipping = 5.3 USD\
Total: 29.13 USD (1 board + case)

## Assembly
Prerequisites: soldered PCB and printed case (PRINT THE CASE WITH +1-2% SCALE FOR TOLERANCES)

1. Mark out the dimensions of the acrylic window and use a scoring tool to cut it
2. From the sides, glue the acrylic window into the top case
3. Wait for glue to set
4. Place completed PCB into bottom case (optionally, affix it with double sided tape, but it should be held in place by friction anyway
5. Glue the top half onto bottom half (I tried, with this kind of size its not very feasible to use screws or anything)

## Images
### Schematic
<img width="1919" height="1069" alt="image" src="https://github.com/user-attachments/assets/2b1e823b-9b6c-452f-95c5-dd407f91a08f" />

### PCB layout
<img width="1928" height="867" alt="image" src="https://github.com/user-attachments/assets/f1fbdf30-a1ba-47c2-9c87-27be6118d292" />

### PCB render
<img width="1455" height="694" alt="image" src="https://github.com/user-attachments/assets/7ec15230-7ca1-4d80-8cb0-1a8aaca63bd4" />

### Full render
<img width="933" height="621" alt="image" src="https://github.com/user-attachments/assets/cac46d55-a1c9-45f1-a4b1-9049f79ea7c8" />
The model may appear not to fit, but this was due to the export being messed up. it fits fine according to all my calculations and two braincells

### Zine
<img width="696" height="992" alt="image" src="https://github.com/user-attachments/assets/96951f64-cadd-4a4e-9b3d-44349c946a8c" />

