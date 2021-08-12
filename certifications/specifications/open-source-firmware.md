<h2>Open Source Firmware Spec</h2>

Hardware should run only open-source boot firmware (aka “the BIOS”), such as [coreboot](https://coreboot.com).  
The only exception is the use of (properly authenticated) CPU-vendor-provided blobs for silicon and memory initialization (see Intel FSP) as well as other internal operations (see Intel ME). However, we specifically require all code used for and dealing with the System Management Mode (SMM) to be open-source.
