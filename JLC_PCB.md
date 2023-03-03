## Ordering from [jlcpcb.com](https://jlcpcb.com/)

### Printed Circuit Board

Go to https://cart.jlcpcb.com/quote to upload the PCB design files.

Upload the "gerber.zip" file by clicking the "Add Gerber File" button.

![Add Button](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/add_gerber.png)

The default settings should be ok. However you can choose 'PCB Color', any other color than green will add two days to the build time.

Option: To hide the order number being visable on the PCB change 'Remove Order Number' to 'Specify a location'.

![PCB Settings](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/pcb_settings.png)

### Surface Mount Assembly Service


Scroll down and Enable the SMD service and make sure the settings are as in the image.
* Accept the Terms and Conditions then click "Confirm".
* Then click "Next" on the right below the Calculated Price heading.

![SMD ON](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/smd_select.png)

Make sure the settings are as in the image.

![SMD Settings](https://github.com/computergeek1507/PB_16/raw/master/img/smd_settings.png)

Then click "Confirm" and then "Next" on the right below the Calculated Price heading.

On the Next page, you will select the BOM and Part Position Files.

![Add BOM POS](https://github.com/computergeek1507/PB_16/raw/master/img/add_bom_pos.png)

'xxxxx_SMD.csv' is the SMD BOM and 'xxxxx-all-pos.csv' is the SMD CPL position file.

The next page will confirm all the BOM parts in the SMD CSV file. Select "Next" to proceed to placement review. If they are incorrect, let me know and I will update the LCSC part numbers.

![BOM Review](https://github.com/computergeek1507/PB_16/raw/master/img/bom_review.png)

The final page will confirm all the part placements in the POS CSV file. The "dots" should match the pin 1 locations on the IC's. If they are incorrect, let me know and I will update the rotation values.

![POS Review](https://github.com/computergeek1507/PB_16/raw/master/img/placement_review.png)

Then Save to Cart and proceed to Checkout and Shipping like normal.