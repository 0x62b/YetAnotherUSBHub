# YetAnotherUSBHub
A 4-port low cost USB 2.0 hub with upstream USB-C and downstream USB-A x2, USB-C, and microSD.

## Motivation

## Repo Structure
`cad`: CAD files
`pcb`: The KiCad PCB design files, and gerbers in `pcb/production`
`bom.csv`: The BOM needed to assemble the PCB
`lcsc.csv`: My LCSC cart export

## BOM
|Item                               |Unit Price (AUD)|Quantity|Extended Price (AUD)|Extended Price (USD approx)|Notes|Link                                            |
|-----------------------------------|----------------|--------|--------------------|---------------------------|-----|------------------------------------------------|
|100nF 0402 capacitor               |0               |2       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C60474.html |
|10uF 0402 capacitor                |0               |7       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C315248.html|
|onsemi NSR0320MW2T1G               |1.18            |1       |1.18                |0.86                       |N/A  |https://www.lcsc.com/product-detail/C48192.html |
|Green 0402 LED                     |0               |1       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C598352.html|
|Molex 67643-2911                   |0.89            |2       |1.78                |1.29                       |N/A  |https://www.lcsc.com/product-detail/C293351.html|
|Molex 104031-0811                  |0.62            |1       |0.62                |0.45                       |N/A  |https://www.lcsc.com/product-detail/C585350.html|
|Korean Hroparts Elec TYPE-C-31-M-12|0.85            |2       |1.7                 |1.23                       |N/A  |https://www.lcsc.com/product-detail/C165948.html|
|1K 0402 resistor                   |0               |1       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C106235.html|
|5.1K 0402 resistor                 |0               |2       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C105872.html|
|56K 0402 resistor                  |0               |2       |0                   |0                          |Owned|https://www.lcsc.com/product-detail/C114756.html|
|CoreChips SL2.1A                   |1.18            |1       |1.18                |0.86                       |N/A  |https://www.lcsc.com/product-detail/C192893.html|
|GENESYS GL823K-HCY04               |0.46            |1       |0.46                |0.33                       |N/A  |https://www.lcsc.com/product-detail/C284879.html|

## Cost
BOM (1 board): 7.17 USD + 3 USD handling + 9.38 USD shipping = 19.55 USD
BOM (5 boards): 16.80 USD + 10.19 USD shipping = 26.84 USD
PCB: 2 USD + 1.5 USD shipping = 3.5 USD
Total: 23.05 USD (1 board) / 30.34 USD (5 boards)

## Assembly
### Soldering the PCB
1. Solder the small passives. Smallest is 0402, making it easily achievable with a normal soldering iron
2. Solder the 2 ICs
3. Solder the Type-C ports
4. Solder the Type-A ports

### Assembly
Prerequisites: soldered PCB and printed case
[todo]

## Images
### Schematic

### PCB layout


### PCB render


### Full render

### Cart screenshots

### Zine# YetAnotherUSBHub
