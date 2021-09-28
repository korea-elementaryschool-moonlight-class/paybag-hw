### Paybag

##### Hardware, Database Notification

***

This repository has 4 folders (barcode_ecobag, barcode_user, data, sound), two .py files and other files

##### 1. Folders

+ barcode_ecobag<br/>
  :arrow_right: new created ecobag barcode images are saved in this folder

+ barcode_user<br/>
  :arrow_right: new created unique user batcode images are saved in this folder

+ data<br/>
  :arrow_right: containing haarcascade.xml file

+ sound<br/>
  :arrow_right: containing sound files that are used at barcode_recognition.py



##### 2. Files

+ barcode_generator.py<br/>
  :arrow_right: generate barcode<br/> 
  + def : generate_number_user
  + def : generate_number_ecodbag
  + def : locate_user_barcode
  + def : locate_ecobag_barcode
  + def : generate_barcode_user_png
  + def : generate_barcode_user_svg
  + def : generate_barcode_ecobag_png
  + def : generate_barcode_ecobag_svg 
<br/><br/>
+ barcode_recognition.py<br/>
  :arrow_right: recognition barcode<br/>
  + https://github.com/korea-elementaryschool-moonlight-class/paybag-hw/blob/master/bracode_recognition.py
