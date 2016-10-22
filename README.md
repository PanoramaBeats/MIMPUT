# MIMPUT
Peach Untold Tale

PLEASE READ!!!
For now, the files are related to XML (i18n), that is, translation of the game assets.
- ENGLISH already done! Its here in case people want to improve it. The game already has ENGLISH as default inside the engine. 
- GERMAN: 0%
- RUSSIAN: 1%
- SPANISH: 4%
- PORTUGUESE: 10%
- FRENCH : 12%
- (put your XML language here): 0%

Version 0.2! This work was one of the BIGGEST of the game! You can finally translate it! We surely should be proud of this control! But due to Mario and other fonts, characters like '㡢 ࡧ' are not supported! 

Although too early, it already covers up 99% of the game (more than 5,000 lines!), and ALL creature scenes (well, perhaps some exceptions might appear)! Certain screens, scene names in the gallery and buttons are NOT in the XML yet.
UPDATE: DESCRIPTION (tale) texts of the achievements and diary items ARE now in the XML!

=> You are encouraged to make pull requests of updated files you are translating!

=> You are also encounraged to test your changes in the game! You just click in CHANGE LANGUAGE, then put your XML and check if the text you changed is aligned well (not cutted out) in the screens,  dialogues, etc.

- UTF8 chars supported for HEART char (just type \u2665 in the XML), latin (now with accents!) like French, German, Spanish, Portuguese, and cyrilic (for now, RUSSIAN!)
- You should use a good XML editor. Notepad++ is great because it will be colored differently, easing your work.
- You DONT need to translate text inside <!-  ->
- Please BE CAREFUL about not closing tags or other misses. Incomplete or errors in XML will give a'XML load error' message or give unexpected behavior in the game!
- Its not possible to change some text, like Princess and Creature names (e.g. if you want to call Peach as 'P�ssego' or Goomba as 'Gumpa', you wont be able to do so). This is due to XML and the game limitations. If I figure it out in the future, I can implement it.
- \\u is UNICODE character. It works only with the charset above (latin, cyrilic, and the heart char). 
- Please translate observing the placement of \n. Its the line breaker. I use them many times just to adjust (centralize) text better. If you translate a given phrase and you see the text is trespassing the balloon, you can force its break by adding a \n. Dont use < br/>!
You can live without \n, but certain balloons will be 'very empty' without them, or the first line might trespass it a bit because of the curve of the balloon.
- I use 'loop="1a", "1b"', etc (that is, variations) to give ALTERNATIVE words according to the logic inside the scene, like if Peach is a nymph or if her...asshole is swollen.
- There are scenes with same messages. This can occur. You can also make them different, if you want more variety.
- Please DONT change variables (those inside { } ), or the game will malfunction!
- If any errors (or something in the game that doesnt have a tag here to be able to translate), please contact me on Legend of Krystal site (ivanaedler). 

Thank you!
