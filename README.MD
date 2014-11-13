TEST KERNEL

NEW EDIT:
NEW zImage FILE PRESENT IN THE FOLDER IS THE NEW KERNEL APPENDED WITH MTK HEADERS :D
ALL THAT IS LEFT IS REPACKING IT WITH A BOOT.IMG

EDIT:
BOOT.IMG PACKING HAS TO BE DONE USING BOOTIMGTOOLS.. NOT MANUALLY
IT IS HIGHLY UNRECOMMENDED FOR DEVS TO USE THIS KERNEL :D

PS.
old_zImage_without_header is not yet appended with mediatek headers, so it isnt usable for flashing with roms
Once appended, repack it with a boot.img and then flash

Features: (supposed)

SELinux support added
New Schedulers added

Kernel source used :
BQ Aquaris 5 HD :D