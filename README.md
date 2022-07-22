# remove_ubuntu_from_dual_boot
Here you can get info about how to remove ubuntu from dual boot



step1: diskpart

step 2: list disk

step 3: select disk 0(as the grub and the booting file for windows i.e efi files are found in local disk C://(in System panel) where windows is installed)

step 4: list part

step 5 : select partition 1(1 is usually system, if not select System Partition)

step 6: assign letter=x

>exit

after exiting----------------------------

>x:
dir
check in image in the same file



<----------------THANKS------------------>
