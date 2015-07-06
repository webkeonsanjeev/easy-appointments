# Introduction #

---

Easy!Appointments supports the addition of custom translations in order to display the user interface into many languages and therefore be more user friendly. This page will guide you through the addition of a new translation and the configuration of the application. You can also modify or even set the default translation for the application.

# Details #

---

Easy!Appointments is based upon CodeIgniter (PHP Framework) and it uses its build in libraries in order to translate the content into many languages. Version 1.0 of the application comes with English, German, Greek, Hungarian and Portuguese already included, but there is also the ability to add you own translation and change the user interface strings and captions. To add a new translation you must do the following:

  1. **CREATE A TRANSATION FOLDER INSIDE "/APPLICATION/LANGUAGE/" DIRECTORY.** If you want for example to translate the application into French then you will need to create a new folder named "French" inside the "/application/language/" directory and copy the contents of the "English" folder. You must also copy the "migration\_lang.php" file from another translation directory (e.g. "German") because CodeIgniter searches for it, when the version migration algorythm gets to work.<br><br>
<ol><li><b>TRANSLATE EACH STRING FROM YOUR "TRANSLATION_LANG.PHP" FILE INTO YOUR LANGUAGE.</b> You will just have to replace the english strings with your translation. Example >> $lang['page_title'] = 'Write your translation here!';<br><br>
</li><li><b>TELL EASY!APPOINTMENTS THAT YOU'VE JUST ADDED A NEW TRANSLATION.</b> When you are finished with the translation you will need to make some changes into the core config file of Easy!Appointments located at "/application/config/config.php" in order to tell the application that there is a new translation available. Find line 90 and add your language to the array. Example >> $config['available_languages'] = array('english', 'german', 'greek', 'hungarian', 'portuguese', <b>'french'</b>); Then go to line 90 and change the default language, though this is optional (e.g. $config['language'] = 'english';).</li></ol>

Follow these steps in order to add or adjust your translations and modify the message of the user interface of Easy!Appointments. If you want contribute to the translation process of Easy!Appointments please read the <a href='https://code.google.com/p/easy-appointments/wiki/GetInvolved'>GetInvolved</a> wiki page for more information. Please share your translations in order to help the user community.<br>
<br>
<table><thead><th><b>Available Custom Translations</b></th></thead><tbody>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/english.zip?dl=1'>English (Alex Tselegidis)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/german.zip?dl=1'>German (Stefan Tselegidis)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/greek.zip?dl=1'>Greek (Alex Tselegidis)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/hungarian.zip?dl=1'>Hungarian (Zsolt Zala)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/portuguese.zip?dl=1'>Portuguese (Andre Tavares)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/spanish-hallar.zip?dl=1'>Spanish (Karim Hallar)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/spanish-silva.zip?dl=1'>Spanish (Cristian Silva)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/spanish-yoruba.zip?dl=1'>Spanish (Obalogun Yoruba)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/dutch.zip?dl=1'>Dutch (Marco Tielen)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/japanese.zip?dl=1'>Japanese (Masashi Nakane)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/french.zip?dl=1'>French (Bernard Sylvie)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/french%20-%20for%20beauty%20salons.zip?dl=1'>French - For Beauty Salons (Bernard Sylvie)</a></td></tr>
<tr><td><a href='https://dl.dropboxusercontent.com/u/27545985/easyappointments/translations/chinese.zip?dl=1'>Simplified Chinese (Aaron Wong)</a></td></tr>