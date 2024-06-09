# Opencore-EFI-Samsung-NT370R5E-370R-Series-3-OC-1.0.0

<img src = "https://user-images.githubusercontent.com/101755125/192142671-2c953457-e0a6-43bc-b737-7bba7f898d5e.png" width="35%"></img>

⚠ Notice!
>This project will not be maintained for future versions of OpenCore as the developers no longer own the hardware.
>
>Switch to read-only archive as this repository will be deprecated in 2024


# Working Features

<img src = "https://user-images.githubusercontent.com/101755125/192142209-282e1a6c-f735-44f0-a565-0567399c823c.png" width="45%"></img>
<img src = "https://user-images.githubusercontent.com/101755125/192142492-8439909f-b1aa-4dda-9d40-bf7095913ed2.png" width="45%"></img>

## Hardware Spec

    CPU : Intel Core(R) i5-3230M Dual-Core 2.60Ghz
    Memory : DDR3L 8GB 1600 MHz
    Graphics : Intel(R) HD Graphics 4000
    (AMD Radeon HD 8700M 2GB disabled)
    Display : Bulit-in Display HD TN 1366x768 resolutions
    SSD : Sata SSD 256GB ( ADATA SU900 )
    SMBIOS : MacbookPro 11,1
    ethernet : WIFI + BT Airport
 
<img src = "https://user-images.githubusercontent.com/101755125/192142609-71d9fe6b-c30e-4638-bca7-4c1793eac4a2.png" width="40%"></img>
<img src = "https://user-images.githubusercontent.com/101755125/192142622-e22e53ce-8a68-4d13-9026-23732070f9e2.png" width="40%"></img>
<img src = "https://user-images.githubusercontent.com/101755125/192142624-d8e57109-fed2-486e-9929-5ab04e21e99e.png" width="40%"></img>
<img src = "https://user-images.githubusercontent.com/101755125/192142615-82ecf0fe-6d2d-4b53-96eb-b3bb2a3b29f5.png" width="40%"></img>

 ## Working Functions
 
       Bulit-in Display HD TN 1366x768 resolutions ( Recommand to use ig-platform-id hex# 03006601 )
       HDMI Output
       Apple Communication Service ( Please Read important itlwm Note )
       USB 3.0 ( Used USBinjectall.kext )
       Screen Backlight ( If Disconnect AC Power, Fasten low brightness )
       Bulit-in Trackpad + Keyboard

## itlwm important Note

       Intel Centrino N Chipset dosen't support any version of airportitlwm on Big Sur
       Only itlwm can used in Mojave,Catalina
       But Airdrop doesn’t receive files and don’t search nearby airdrop devices + Doesn’t Support 
       Sidecar,Universal Control ( cuz SMBIOS is 2014” mid )

## Not Working Functions yet 

      ATIV Webcam ( disappeared on USB Map )
      Battery Percentage ( Battery Drain out )
      Sleep Mode Doesn’t wake ( Maybe Disable USB S3 AWAKE and Mapping USB )
      SD Card Reader
      Intel Speed Step ( Not need this )
       ̶R̶e̶a̶l̶t̶e̶k̶ ̶L̶A̶N̶ ̶(̶ ̶N̶o̶t̶ ̶w̶o̶r̶k̶i̶n̶g̶ ̶R̶T̶L̶8̶1̶1̶1̶.̶k̶e̶x̶t̶,̶i̶n̶t̶e̶l̶m̶a̶u̶s̶i̶,̶A̶p̶p̶l̶e̶E̶1̶0̶0̶0̶,̶A̶t̶h̶e̶r̶o̶s̶E̶2̶0̶0̶0̶ ̶)̶*̶ - Hardware Dead :(

