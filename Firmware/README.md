# Here is you can find firmware files  
## Down here is setup:  
## Step 1 — Flash CircuitPython onto the Pico


-   Download the [CircuitPython](https://circuitpython.org/board/raspberry_pi_pico/) UF2 for Raspberry Pi Pico

-   Hold the **BOOTSEL** button on your Pico and plug it into USB.  
-   A drive called **RPI-RP2** will appear on your computer.  

-    Drag and drop the .uf2 file onto that drive.  
-    The Pico will reboot and a new drive called **CIRCUITPY** will appear.  

## Step 2 — Install KMK

- 1 Go to [Kmk github](https://github.com/KMKfw/kmk_firmware) and click **Code → Download ZIP**
- 2 Unzip it
- 3 Copy the **`kmk/`** folder from inside the zip into the root of the **CIRCUITPY** drive

## Step 3 — Copy your keyboard config

Copy the **code.py** file into the root of the **CIRCUITPY** drive.

## Thats it  
**pico will automaticly run kmk on boot**
