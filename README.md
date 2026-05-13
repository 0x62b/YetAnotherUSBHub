# YetAnotherUSBHub
A 4-port low cost USB 2.0 hub with upstream USB-C and downstream USB-A x2, USB-C, and microSD.

## Motivation

## Repo Structure
`cad`: CAD files\
`pcb`: The KiCad PCB design files, and gerbers in `pcb/production`\
`bom.csv`: The BOM needed to assemble the PCB\
`lcsc.csv`: My LCSC cart export

## BOM
|Item                               |Unit Price (AUD)|Quantity|Extended Price (AUD)|Extended Price (USD approx)|Notes      |Link                                            |
|-----------------------------------|----------------|--------|--------------------|---------------------------|-----------|------------------------------------------------|
|100nF 0402 capacitor               |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C60474.html |
|10uF 0402 capacitor                |0               |7       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C315248.html|
|onsemi NSR0320MW2T1G               |1.18            |1       |1.18                |0.86                       |N/A        |https://www.lcsc.com/product-detail/C48192.html |
|Green 0402 LED                     |0               |1       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C598352.html|
|Molex 67643-2911                   |0.89            |2       |1.78                |1.29                       |N/A        |https://www.lcsc.com/product-detail/C293351.html|
|Molex 104031-0811                  |0.62            |1       |0.62                |0.45                       |N/A        |https://www.lcsc.com/product-detail/C585350.html|
|Korean Hroparts Elec TYPE-C-31-M-12|0.85            |2       |1.7                 |1.23                       |N/A        |https://www.lcsc.com/product-detail/C165948.html|
|1K 0402 resistor                   |0               |1       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C106235.html|
|5.1K 0402 resistor                 |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C105872.html|
|56K 0402 resistor                  |0               |2       |0                   |0                          |Owned      |https://www.lcsc.com/product-detail/C114756.html|
|CoreChips SL2.1A                   |1.18            |1       |1.18                |0.86                       |N/A        |https://www.lcsc.com/product-detail/C192893.html|
|GENESYS GL823K-HCY04               |0.46            |1       |0.46                |0.33                       |N/A        |https://www.lcsc.com/product-detail/C284879.html|
|2mm acrylic sheet                  |6.25            |1       |6.25                |4.53                       |200x200x2mm|https://www.aliexpress.com/item/32817321651.html
|1mm*1mm magnets                    |5.66            |1       |5.66                |4.1                        |pack of 100|https://www.aliexpress.com/item/1005010129861409

## Cost
BOM (1 board + case): LCSC[7.17 USD + 3 USD handling + 9.38 USD shipping = 19.55 USD] + AliExpress[4.53 + 4.1 = 8.63 USD] = 28.18 USD
PCB: 2 USD + 1.5 USD shipping = 3.5 USD
Total: 31.68 USD (1 board + case)

## Assembly
### Soldering the PCB
1. Solder the small passives. Smallest is 0402, making it easily achievable with a normal soldering iron
2. Solder the 2 ICs
3. Solder the Type-C ports
4. Solder the Type-A ports

### Assembly
Prerequisites: soldered PCB and printed case

1. Glue magnets into the holes in the both parts of the case
2. Mark out the dimensions of the acrylic window and use a scoring tool (or other method) to cut it
3. Glue the acrylic window in place from the sides
4. Place the PCB into the bottom case
5. Once the glue holding the magnets has dried, place the top case onto the bottom case to complete the build

## Images
### Schematic
<img width="1811" height="1004" alt="image" src="https://github.com/user-attachments/assets/b119971e-4e9b-4646-b3ad-1f7e04e5f507" />

### PCB layout
<img width="1651" height="768" alt="image" src="https://github.com/user-attachments/assets/692d26eb-3566-41c1-94e7-2b437b3f0449" />

### PCB render
<img width="1401" height="663" alt="image" src="https://github.com/user-attachments/assets/f2c9b152-c192-4936-bbc1-8783eb814260" />

### Full render

### Cart screenshots
<img width="1301" height="809" alt="image" src="https://github.com/user-attachments/assets/820835a0-0af5-422c-ad08-33c8d8ea4684" />
<img width="1261" height="868" alt="image" src="https://github.com/user-attachments/assets/3c0fee77-7b41-4a79-b8fd-47d0a49c9045" />

### Zine
