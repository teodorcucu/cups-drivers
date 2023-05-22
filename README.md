## Brother HL-1110 CUPS Driver, working on ARM for example an Raspberry Pi 

> Many thanks to the @oodolabs



1. Download the `install.sh` from Brother/BrGenPrintML2 
(`wget https://raw.githubusercontent.com/the-real-t30d0r/cups-drivers/master/Brother/BrGenPrintML2/install.sh`)

2. Set the right to permission in order to run the shell script.
3. Run the Script `sudo bash install.sh`
4. Restart CUPS `sudo systemctl restart cups`
5. Restart the Printer

Now you can set up the Brother HL-1110 in CUPS. If you have an older setup of the Brother HL-1110 delete it.
