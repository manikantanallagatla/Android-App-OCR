***Android App OCR:***

----------
##*Aim*:

----------

To make an Android app which can capture or select image from gallery then run OCR on the selected image.

-------------
##*Softwares Used*:

-------------

Android Studio, Sublime text

-------------
##*Language Written*:

-------------

Android Studio, PHP, Python 


-------------
##*Introduction*:

-------------
Optical Character Recognition(OCR) is the mechanical  or electrical conversion of images of typewritten or printed text into machine-encoded text. It is widely used as a form of data entry from printed paper data records, whether passport documents, invoices, bank statements, computerized receipts, business cards, mail, printouts of static-data, or any suitable documentation. It is a common method of digitizing printed texts so that it can be electronically edited, searched, stored more compactly, displayed on-line, and used in machine processes such as machine translation, text-to-speech, key data and text mining. OCR is a field of research in pattern recognition, artificial intelligence and computer vision. So making an Android App for using OCR will be very useful in dayto day life.



-------------
##*Algorithm*:

-------------

Here I have used a hack. Instead of coding everything in Amdroid Studio, I have made a webapp using PHP and python and opened the url in android using webview. Using PHP image is taken as input and this image is processed for OCR using python and python module pyteserract is used for OCR. Then output is shown using PHP.

-------------
##*Usage*:

-------------

Insert the Android App folder into the www server folder and run the local server using wampp or apache. Deploy OS file up master into the android device.
P.S: Edit the urls in RunOCR.php and Main Activity.java to link to the local server. OS file up is cloned form https://github.com/mgks/Os-FileUp

This code is edited using Sublime text.
