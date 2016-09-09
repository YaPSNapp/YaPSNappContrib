

# ![logo][imgLogo] &nbsp;&nbsp;YaPSNapp - How to contribute ?

Welcome to the contributed project for YaPSNapp.
You can collaborate to this project by
* Translating the app *(if you want to see your favorite app in your native language)*
* Define some new application theme(s) for future releases.

## Translation

Several things to do for each language:

* Select the language for which you want to contribute, here are the priority languages:
	* English [en_US](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/en_US) *(Credits: Drakfly)*
	* Français [fr_FR](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/fr_FR) *(Credits: Drakfly)*
	* Español [es_ES](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/es_ES) *(Credits: Drakfly)*
    * Português [pt_PT](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/pt_PT) *(Credits: Diogo Vidigal)*
    * Arabic [ar_AR](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/ar_AR) *(Credits: Hazanberg)* 
	* Deutsch [de_DE](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/de_DE) *(Credits: Xaosthings)* 
	* Nederlands [nl_NL](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/nl_NL) *(Credits: Lastminuteguy)* 
    * Italiano [it_IT](https://github.com/YaPSNapp/YaPSNappContrib/tree/master/Localization/it_IT) *(Credits: Felix)* 
    * 中国 zh_CN `--- Not yet translated`

    
	
You can amend this language list by adding additional languages (by creating sub-folder accordingly)
	
* There are 2 files by language
    + 1 page `Localization.strings` where you must change the labels / messages used in YaPSNapp iOS App
    + 1 page `AppStore.txt` where you must specify the application description for the Application store (AppStore / PlayStore)

## Design

To create a new YaPSNapp theme, copy an existing "Stock" theme file (XML format) and edit it.
The color format is `#AAAAAAFF` where: 
* 6 first alpha-digits, are used for color in hexa format
* 2 last alpha-digits, are used for alpha transparency in hexa format

**Currently, it is not possible to test your theme directly in the app.** In a future release, we will add an app scheme extension that will permit to load the file in the app to test it.


---

To see your changes and if you have a jailbroken phone, you can browse the YaPSNapp Documents/theme directory and edit a "Stock" XML theme file.

> Note that with a jailbroken phone you can browse the YaPSNapp Documents/theme directory 
> to retrieve the XML file you have customized through the App settings screen.


![logodrakfly][imgDrakfly]

[imgLogo]:https://raw.githubusercontent.com/YaPSNapp/YaPSNappContrib/master/logo.png
[imgDrakfly]:https://raw.githubusercontent.com/YaPSNapp/YaPSNappContrib/master/drakfly.png
