# MixStick-Arcade-Controller
Compact, universal 12-button WASD layout USB arcade controller compatible with Mac, PC, MiSTer, and more. The MixStick is a hybrid of a mechanical keyboard and budget arcade fight stick, but forced into the constraints of economical parts and versatility. Unlike all the dedicated things it’s inspired by, it doesn’t do anything particularly well, but at the cost of parts I can confidently say it punches above its weight combared to the $250+ mixbox-like alternatives. Can also be a macro keyboard when paird with AntiMicroX. Enclosure design files are available to remix/ suite whatever application you need. Gerber files are available to make your own. PCB design files will come a bit later.
![P1060787](https://user-images.githubusercontent.com/68818321/212553394-0e48235a-5490-4d9f-be8c-41be95293a85.JPG)
![P1060708](https://user-images.githubusercontent.com/68818321/212557968-38b07a62-f7fd-4913-84a2-b25c9e890b5a.JPG)
Detailed about.
The circuit board is discrete input (not a row column matrix) arduino pro micro arcade controller. Or just a generic USB HID game controller with a modular enclosure. The circuit is designed as pin to pin compatible with the open source and awesome daemon byte arcade encoder firmware by MickGyver. I’ve added RGB leds for clout. Set your IDE to an Arduino Leonardo or Pro Micro, and upload MickGyver Firmware. Plug this into a Mac or PC and that’s it. You’ve got a nice compact gaming controller with more buttons than you need.  
The backside of PCB has jumpers to move (or duplicate) two buttons from the top function to adjacent of WASD cluster.
![P1060691](https://user-images.githubusercontent.com/68818321/213032196-9bbc947e-6b4a-49e2-9225-2174489e088e.JPG)

CAD files have two main variatations, the Straight Layout or the Angled Offset layout. This orientiation influnces the location of the cordpass through. Pick the correct 3D model or change the dimension in the solidworks model. 
![MixStick 3D print Base](https://user-images.githubusercontent.com/68818321/213031976-b297f7ba-33ca-431a-bc8b-4ee8374dc661.PNG)
![MixStick 3D print Base overview](https://user-images.githubusercontent.com/68818321/213032332-95dafbf8-f9ac-4670-842b-e598eefe9213.PNG)
![MixStick 3D control panel Dimensions](https://user-images.githubusercontent.com/68818321/213032525-d8025fd0-7d43-49c1-a285-e9bbc507570e.PNG)


![P1060748](https://user-images.githubusercontent.com/68818321/212553370-389729be-9778-4ef1-b344-f17f85a1ba21.JPG)
![P1060796](https://user-images.githubusercontent.com/68818321/212553407-39b4a8b8-f569-4cac-adcc-5e83542839b0.JPG)
![P1060783](https://user-images.githubusercontent.com/68818321/212553421-9607d3d5-ef52-45b9-9128-d86a8e6d689d.JPG)
![P1060782](https://user-images.githubusercontent.com/68818321/212553425-57b1f0da-b6d6-4d1e-b359-855fa12eb519.JPG)

![PCB view](https://user-images.githubusercontent.com/68818321/212560337-54bcd145-12ff-4df2-b9a5-0ececc3d845a.PNG)

Extra Notes:
Use the enclosure files with your own ideas. This arcade controller was  made from a salvaged 3rd-party universal DDR circuit board. 
![P1060760](https://user-images.githubusercontent.com/68818321/213032866-175302cf-768b-4258-afd8-7674765b9ca6.JPG)
![P1060758](https://user-images.githubusercontent.com/68818321/213032934-b722038c-d006-46c9-b7cc-0af371ef134b.JPG)


If using the WASDjoy modular PCBs see repository for laser cutable templates here: https://github.com/retrobuiltRyan/WASDjoy
![P1060714](https://user-images.githubusercontent.com/68818321/212561554-c8b53924-a5d4-4e13-a642-809e52fbd1a6.JPG)
