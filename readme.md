# An elementary os theme for Firefox / Un theme elementary pour Firefox

In this version, all buttons are moved to the right (windows layout or ubuntu layout)
tested in dark mode too. 
<img src="firefox layout windows.png"/>

Dans cette version les boutons de fenêtre sont placés à droite comme sur windows ou ubuntu. 
<img src="firefox dark theme.png"/>

## Thanks /Remerciements

Thanks to [Harvey Cabaguio](https://github.com/harveycabaguio/firefox-elementary-theme) for 
inspiring me and for his great elementary's theme.

## Install / Installation

**Firefox does not support userChrome.css by default. Here are the steps to make it work:**
  1. Load **about:config** in the Firefox address bar. 
  2. Confirm that you will be careful.
  3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` using the search at the top.
  4. Toggle the preference by double clicking. True means Firefox supports the CSS files, False that it ignores them.

**Firefox ne prend pas les themes par défaut, pour les activer :**
  1. Taper **about:config** directement dans la barre d'adresse de Firefox. 
  2. Confirmez que vous serez attentif à vos modifications.
  3. Activez le paramètre `toolkit.legacyUserProfileCustomizations.stylesheets` à true.

**To install userChrome.css:**

  1. Go to **about:support** in Firefox
  2. Application Basics > Profile Directory > Open Directory
  3. Create a folder named `chrome`
  4. Paste the userChrome.css in this folder
  5. Disable Title bar in the customization panel in Firefox.
  5. Choose the Windows Layout panel with elementary-tweaks (and Dark mode if you want).
  6. Close and run Firefox.

**Pour installer votre theme userChrome.css:**
  1. Tapez **about:support** directement dans la barre d'adresse de Firefox. 
  2. Ouvrir le dossier Répertoire de profil 
  3. Créez un dossier `chrome` (oui même pour Firefox)
  4. Collez le fichier userChrome.css que vous avez téléchargé dans ce dossier
  5. Disable Title bar in the customization panel in Firefox.
  5. Sélectionnez Layout: Windows avec elementary-tweaks (passez en Dark variant si vous le souhaitez ).
  6. Relancez Firefox.
