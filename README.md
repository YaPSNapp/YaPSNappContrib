

# ![logo][imgLogo] &nbsp;&nbsp;YaPSNapp - How to contribute ?

Welcome to the contributed project for YaPSNapp.
You can collaborate to this project by
* Translating the app *(if you want to see your favorite app in your native language)*
* Define some new application theme(s) that we will be able to release for everyone

## Translation

Several things to do for each language:

* Select the language for which you want to contribute, here are the priority languages:
	* English [en_US](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/en_US) *(Credits: Drakfly)*
	* Français [fr_FR](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/fr_FR) *(Credits: Drakfly)*
	* Español [es_ES](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/es_ES) *(Credits: Drakfly)*
    * Português [pt_PT](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/pt_PT) *(Credits: Diogo Vidigal)*
    * zh_CN `--- Not yet translated`
    * it_IT `--- Not yet translated`
    * de_DE `--- Not yet translated`
	
You can amend this language list by adding additional languages (by creating sub-folder accordingly)
	
* There are 2 files by language
    + 1 page `Localization.strings` where you must change the labels / messages used in YaPSNapp iOS App
    + 1 page `AppStore.txt` where you must specify the application description for the Application store (AppStore / PlayStore)

## Design

If you want to create a new YaPSNapp theme for a future release, you can create a new Theme with its schemes by creating a new XML file.
Just copy an existing "Stock" theme file and change what you want.
The color format is in `#AAAAAAFF` format where 
* 6 first alpha-digits, are used for color in Hexa format
* 2 last alpha-digits, are used for alpha transparency in Hexa format

**Currently, it is not possible to test it, in the app**, in a future release, we will add an app scheme extension that will permit to load the file in the app to test it.
To see your changes and if you have a jailbroken phone, you can browse the YaPSNapp Documents/theme directory and edit a "Stock" XML theme file.

> Note that with a jailbroken phone you can browse the YaPSNapp Documents/theme directory 
> to retrieve the XML file you have customized through the App settings screen.


![logodrakfly][imgDrakfly]

[imgLogo]:https://raw.githubusercontent.com/YaPSNapp/YaPSNappContrib/master/logo.png
[imgDrakfly]:https://raw.githubusercontent.com/YaPSNapp/YaPSNappContrib/master/drakfly.png