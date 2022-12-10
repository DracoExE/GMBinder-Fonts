# GMBinder-Fonts
Custom fonts for the GMBinder



Add to the beginning of the Brew (before the <style> path):
``` css
<link rel = "stylesheet" type = "text/css" href = "https://dracoexe.github.io/GMBinder-Fonts/Fonts_v1.css"/>

 ```
 
 Then, you can add this code to the Style part for configuring the fonts automatically:
  
 ``` css
 /* Configure Fonts */
.phb { font-family: 'BookinsanityRemakeRegular'; }
.phb p { font-family: 'BookinsanityRemakeRegular'; }
.phb em { font-family: 'BookinsanityRemakeItalic'; }
.phb strong { font-family: 'BookinsanityRemakeBold'; }
.phb li { font-family: 'BookinsanityRemakeRegular'; }
.phb table { font-family: 'Scaly Sans'; }
.phb .descriptive { font-family: 'Scaly Sans';}
.phb .descriptive p { font-family: 'Scaly Sans';}
.phb .descriptive em { font-family: 'Scaly Sans Italic'; }
.phb .descriptive strong { font-family: 'Scaly Sans Bold'; }
.phb blockquote { font-family: 'Scaly Sans';}
.phb blockquote p { font-family: 'Scaly Sans';}
.phb blockquote li { font-family: 'Scaly Sans'; }
.phb blockquote em { font-family: 'Scaly Sans Italic'; }
.phb blockquote strong { font-family: 'Scaly Sans Bold'; }
.phb .spellList { font-family: 'Scaly Sans';}
.phb .spellList ul { font-family: 'Scaly Sans';}
.phb .spellList li { font-family: 'Scaly Sans';}
.phb hr+section blockquote h3 {font-family: 'Scaly Sans'; }
.phb h1, .phb h2, .phb h3, .phb h4, .phb h6 { font-family: 'Mr Eaves Small Caps'}
.phb h5 { font-family: 'Scaly Sans Caps Bold'; color: #000 }
.phb a { color: #003d66; }
.phb h6 { font-weight: bold; margin-bottom: 0.3em; }
.phb strong { letter-spacing: inherit; }
