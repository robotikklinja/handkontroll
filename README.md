# Handkontroll
En handkontroll med display basert på Arduino Nano

# BOM til handkontrollen

## Electronics components

Antal deler 27, 17 unike.
Totalt 185 NOK. Pris per elev inkludert frakt ekskludert moms når vi importerer til en klasse på 18 elever. 

## Alixpress linker
* [5PCS 20mm Shaft Potentiometer, 10K](https://www.aliexpress.com/item/1005001421294754.html)
* [8mm Metal Button Switch Normally Open Waterproof Antirust (GREEN)](https://www.aliexpress.com/item/1005002153423900.html)
* [8mm Metal Button Switch Normally Open Waterproof Antirust (RED)](https://www.aliexpress.com/item/1005002153423900.html)
* [8mm Metal Button Switch Normally Open Waterproof Antirust (BLUE)](https://www.aliexpress.com/item/1005002153423900.html)
* [8mm Metal Button Switch Normally Open Waterproof Antirust (YELLOW)](https://www.aliexpress.com/item/1005002153423900.html)
* [Arduino Nano 3.0 with usb cable](https://www.aliexpress.com/item/1005002509257579.html)
* [Usb  Male to Female Extension Cable 0.3m left-angle](https://www.aliexpress.com/item/4000819180471.html)
* [Wall Terminal Plug Type 5.08mm Pitch Connector Pcb Screw Terminal Block](https://www.aliexpress.com/item/4000907549303.html)
* [JST connector set, 2,54mm 20 mm wire. 2P](https://www.aliexpress.com/item/32954418743.html)
* [JST connector set, 2,54mm 20 mm wire. 4P](https://www.aliexpress.com/item/32954418743.html)
* [JST connector set, 2,54mm 20 mm wire. 5P](https://www.aliexpress.com/item/32954418743.html)
* [LCD module Blue Green screen IIC/I2C 1602](https://www.aliexpress.com/item/32685016568.html)
* [Battery clips 9V](https://www.aliexpress.com/item/1005003688602261.html)
* [Rocker Switch ON/OFF](https://www.aliexpress.com/item/4001165826718.html)
* [ 0.3A PPTC inline self recovery fuse/fuse 72V 300mA pin spacing 5mm](https://www.aliexpress.com/item/1005006054781697.html)
* [M3 6mm Standoff Nylon Plastic Hexagon Thread PCB ](https://www.aliexpress.com/item/1005004311987482.html)
* [15pin female header 2,54mm pitch](https://www.aliexpress.com/item/1005001621390463.html)
* [2.54 Wire Dupont Line female to  female 4P 20cm](https://www.aliexpress.com/item/1005003198478253.html)

[Excel BOM](handkontroll_ali_BOM.xlsx)

## Mekaniske deler
* 2 mm * 1000mm * 300 mm aluminium platemeteall per elev. Kjøp minst dobbel mengde.
* Popnagler
* Ø2.5 mm, Ø3 mm, Ø4mm maskinskruer og mutter
* Gummiføtter [$1,24 USD for 20pcs Conical Rubber Foot aliexpress](https://www.aliexpress.com/item/1005002995372007.html)

[Se denne for mekaniske tegninger](https://github.com/Jaknil/Arduino_material/tree/master/handkontroll)

## Verktøy
* Platesaks
* Plateknekker
* Filer
* Skrustikk
* Drill
* Gjengetapp
* Høreselvern
* Beskyttelsebriller

## 3D printer
* Elevene designer og printer knott til potentiometeren
* Fint å bruke til batteriholder [thingiverser, eksempel](https://www.thingiverse.com/thing:2144462)

## Kretstegning

Har laget en versjon med 2 knapper og en med 4. Knappene har innebygget LED lys i ulike ferger som kan dimmes med PWM. Alt er koblet til kortet med headers.

For at lage PCB-layout så har jeg måttet slettet knapper og LEDs fra koblingsskjema-vyen for at de ikke skall bli del av PCBen. 
Det finns forskjellige fritzing filer, noen viser alle deler, noen viser bare delene som er direkte på kretskortet, med headers for tilkobling.

### Two buttons
* [Koblingsskjema, alle deler PDF](handkontroll_full_schematic_all_components.pdf)
* [Fritzing fil med alle deler, OBS ikke riktig JST-header pin spacing for PCB på denne](handkontroll_full_schematic_all_components.fzz)
* [PCB, bare kortet, fritzing (riktig JST pin spacing)](handkontroll_full_schematic_pcb.fzz)
* 2 knapp PCB versjon. Bestillt fra fabrikk via deres integrerte tjenste [Se online](https://aisler.net/p/RCMDKGZY)

### 4 buttons
* Frtizing [PDF-koblingskjema bare kortet](handkontroll_full_schematic_pcb_4_buttons_schem.pdf)
* [PCB med 4 knapper bare kortet i fritzing ](handkontroll_full_schematic_pcb_4_buttons.fzz)
* 4 knapp versjon- Designet i fritzing,  Bestillt fra fabrikk via deres integrerte tjenste [Se kortet online](https://aisler.net/p/QSIZRARK)
  
|    Antall kort  | Totalpris i € | Stykkpis i € |
| ----------- | ----------- | ----------- |
| 3     | 16       | 5,3       |
| 6   | 24        | 4       |
| 12   | 34        | 2,8       |
| 108   | 232        | 2,1       |

Shipping kostet 22€ med tracking 0€ uten trakking men tok då veldig lang tid.    

## Eksempelkode
* [KubenKoder repository](https://github.com/KubenKoder/Arduino/tree/master/Egna%20exempel/handkontroll)
* [Jaknil repository](https://github.com/Jaknil/Arduino_material/tree/master/handkontroll)
