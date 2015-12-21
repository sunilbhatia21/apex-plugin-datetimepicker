#Oracle APEX Item Plugin - pDateTimePicker
Just another jQuery DateTimePicker.
It is based on JS Framework jQuery Plugin Date and Time Picker (https://github.com/xdan/datetimepicker).

##Changelog
####1.1 - APEX5 - Validation

####1.0 - Initial Release

##Install
- Import plugin file "item_type_plugin_de_pragmatis_sc_datetimepicker.sql" from source directory into your application
- (Optional) Deploy the CSS/JS files from "server" directory on your webserver and change the "File Prefix" to webservers folder.

##Plugin Settings
The plugin settings are highly customizable and you can change:
* Language of datetimepicker => possible values: de, en, es; default:  Application Primary Language
* Show datepicker 				=> possible values: yes, no; default: yes)
* Format date						=> Date format with moment.js format
* Show week number				=> possible values: yes, no; default: no
* Enable weekends				=> Weekends are enabled, possible values: yes, no; default: no
* Default date					=> Enter a default date
* Minimum date					=> Enter a minimum date
* Maximum date					=> Enter a maximum date
* Show timepicker				=> possible values: yes, no; default: yes
* Format time						=> Time format with moment.js format
* Default time					=> Enter a default time
* Step time						=> For timepicker only: Step time - minute interval between hours (possible values: all numbers larger than 0; default: 60)
* Round time						=> For timepicker only: round time (possible values: round, ceil, floor; default: round)

##Preview
![](https://github.com/pr49sc/apex-plugin-datetimepicker/master/preview.png)
---
