# Process documentation

---------------------------------------------------------------

<h2>first changes</h2>

1.  first of all i added some personality to the different characters by changing the position of voice1 (the intercom voice) and voice2 (the main character) and the styling to their text (color, padding, background-color).
2.  Then i added styling to the cursing voice halfway through the clip, this is an intense part so i made the color to this text blood-red with an animation that shifts between normal red and dark red. The text is way bigger than any other text we have seen because it is aggresive, instead of the passive aggressive tone we might get in other places in this clip.
3.  then i started te listen to background noises and how they impact the viewing experience. In the opening scene the shots are very dark, and we dont know too much about what is going on, i made the background similar to the colors in the shot to simulate this mystery of not knowing what is goin on. I did this with a CSS animation based on percentages. The background colors shift between darker versions of teal and darkslategray.
4.  next we hear a buzzer, the buzzer repeats a couple times and clearly indicates the intense situation and the pressure the main character is under. he is clearly being disrespected and discriminated by other people in the hallway, the screen flashes red and black every time the buzzer rings (once again with an animation). The main character want to get out of there.
5.  we enter the interrogation chamber. The main character seems way more comfortable, the background color changes to a light blue, but a sharp tones creeps in, becoming more and more present over the coming 30 seconds, the light blue slowly changes to a bright turqouise, the color of the intercoms text, the intercom bein the one in control here, he puts more pressure on the main character when the scene progresses.
6.  suddenly the voice says they are done and tells the main character he can pick a bonus, he clearly passed this test, the background color is back to white and the intercoms voice is no longer in bright turqouise but a soothing blue.

7. in the next scene the main character does not pass this test, the pressure is a lot higher and the mian character has a lot less control and is overshadowed by the voice in the intercom. the backgorund color in this scene starts with a light red and gets darker and darker the more the main character fails the test.

<h2>summary first changes</h2>
 - voices have been given a personality based on the amount of control they have in the scene and the tone they have in their voice.
 - background noises impact the background color of the page in a way that simulates the feeling it gives the main character.

---------------------------------------------------------------

<h2>Second changes</h2>

1. Added font-family variations for the different voices to add to their character. The voice trough the intercom gets the typewriter-like brenner mono to simulate its robotic personality, the main character gets Brenner Sans, the straight, emotionless font that matches his cyborg personality, the man in the hallway gets Brenner Slab, a more stylized version of Sans, to show his humanity. In the following scene, where the main characted thinks of himself as human, while being a cyborg, he will also adapt the Slab font.
2. Changed the background color of the interrogation scene and of the intercom voice to Yellow. Yellow showcases more stress than Turqouise while still being less tense than Red.

<h2>Summary second changes</h2>
 - voices have matching font-families
 - changed interrogation scene background to yellow
 - changed background of intercom voice text to yellow

---------------------------------------------------------------

<h2>changes after first feedback</h2>

1. I changed to background color of .voice4 to look more like .voice1, but lightened the colors to imply that the voice speaks much less intense, and more calm.
2. changed the size and place of the video player, this is now more in the middle with a bigger screen, i also changed the locations of the text to match with this change.
3. changed .voice3 text size and place. The font was too big, the man didnt scream at the main character, he whispered the slur in his ear. so an intense red with small letters is more accurate.
4. added background animations for more background noises in the beginnen of the scene.
5. added background animations to match the atmosphere of the hallway scene, a hostile area where the main character is not appreciated and even discriminated on. The room slowly flashes a dark red.

<h2>Summary changes 3</h2>
 - changed the styling of some voices to match their tone more.
 - added more background animations
 - changed the size and place of the video player
 
---------------------------------------------------------------

<h2>changes after second feedback</h2>

1. Changed the background effect used in the interrogation scene. After Feedback form Darice she told us that darkening a scene would simulate intensity, which was exactly what i needed for this scene, the background, text and video player darken in color.
2. After the feedback i added text to show the user the name of the person talking, and a description of the sounds in the background, next to the color sound-effects in the background.
3. tweaked some text-sizes and places to match the size of the extra text.

<h2>Summary changes</h2>
 - changed background effect interrogation scene after feedback.
 - added text to clarify who is talking and what noise is in the background.
 - tweaked text styling
 
--------------------------------------------------------------- 
  
# Web Typography, 2020/2021

Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. Nu bestaat er zoiets als *closed caption*, wat een type ondertiteling is waarbij ook dingen als omgevingsgeluiden en de muziek beschreven worden. Hierdoor krijgt een kijker die informatie wel binnen.

Alleen wordt die auditieve informatie nogal neutraal beschreven. Het geluid van huilend persoon zou bijvoorbeeld beschreven kunnen worden als *snikgeluid op de achtergrond*. En iemand die lacht zou geschreven kunnen worden als *iemand lacht.* Heel neutraal, bijna zakelijk, en bovendien allebei in precies hetzelfde neutrale lettertype. Terwijl het toch echt over twee heel verschillende emoties gaat. 

Dat kan visueel sterker. 

En dat gaan jullie doen.

## Leerdoelen

- Je kan de kennis over vormgeving die je hebt opgedaan tijdens de minor technisch toepassen met behulp van CSS
- Je kan verborgen nuance uit een audiotrack overtuigend vertalen naar visuele (typografische) beelden
- Je kan je typografische keuzes onderbouwen.
- Je hebt de exclusive design principles gebruikt.

## Oplevering

Je levert een werkende versie op, gemaakt met HTML, CSS en JavaScript. Deze staat op Github. In een duidelijke readme documenteer en onderbouw je je ontwerpkeuzes. Je developmentgeschiedenis is terug te vinden op GitHub.

Je levert ook een *screen recording* met audio op van je fragment. Dit is een video van de definitieve versie, gemaakt van jouw browserscherm.

De beoordeling is mondeling en volgt [de rubric uit het beoordelingsformulier](web-typografie-beoordeling.pdf).

## Typografische restricties

Je *moet* een van deze twee opties kiezen, en je keuze moet je onderbouwen. In je readme staat een uitleg over je overwegingen om de ene of de andere restrictie te kiezen.

### Optie 1: Systeemfont

De eerste optie is dat je gebruik maakt van het zogenaamde *systeemfont* van degene die naar jouw werk kijkt. Dit font verschilt per operating system, en het verschilt soms zelfs per versie van het operating system. Het is ook aan te passen door de gebruiker zelf. 

Je hebt dus geen controle over welk lettertype er precies gebruikt wordt. Het levert dus een onzeker, en beperkt typografisch palet op. Je hebt geen *light* versies, of *extrabold*. En ook geen serif en sans-serif versie van dezelfde familie. In dit geval heb je alleen de beschikking over normal, **bold** en _italic_. Dit heeft natuurlijk ook zijn voordelen!

### Optie 2: Brenner

Je kan er ook voor kiezen om gebruik te maken van de complete Brenner familie. Dit is een zeer uitgebreid en uiterst flexibel font. [Hier kan je je verdiepen in dit font](https://www.typotheque.com/blog/brenner_an_unusual_typeface_family_with_distinct_voices). Als je kiest voor dit font dan heb je de beschikking over een *sans serif*, een *condensed*, een *serif*, een *monotype*, een *slab*, een *display* en een *script* versie. En veel van deze versies hebben varianten van *light* tot *bold*, en allemaal zowel *bold* als *italic*.

Met Brenner zijn er natuurlijk veel en veel meer mogelijkheden dan met systeemfonts. Dat kan zowel een voordeel als een nadeel zijn. 

Voor een overzicht, zie [de brenner.pdf](brenner.pdf).

## Het fragment

Ik heb een fragment voorbereid. Het gaat om twee scenes uit *Blade Runner 2049*. De captions staan in de HTML, en ze verschijnen in sync met de video. [Kijk maar](closed-captions/index.html).

### De captions

De captions staan in de html, in het bestand index.html. Je kan aan elke paragraaf eventueel een of meer classes toevoegen. Bijvoorbeeld `voice1` of `voice2 soft`. Classes voeg je handmatig toe in de html.

Met JavaScript worden er een paar dingen extra gedaan: 

- er wordt aan elke paragraaf een unieke class toegevoegd (`p0`, `p1`, etc)
- Elk woord wordt in een aparte `span` gezet. Hierdoor kan je elk woord apart stylen, en eventueel ook [na elkaar laten verschijnen](https://github.com/cmda-minor-vid/web-typography-18-19/blob/master/closed-captions/css.css#L41).

### Tijdens het afspelen

Tijdens het afspeelen wordt er een class `on` op de caption gezet als hij moet verschijnen, en een class `off` als hij klaar is. *Zowel class `on` als class `off` blijft op de caption staan!*

De timimg van de captions kan je aanpassen in [closed-captions/captions.js](closed-captions/captions.js).

Er verschijnen ook classes op de body op momenten dat er geluiden worden afgespeeld, zoals `sound1` en `sound2`. Je kan geluiden toevoegen in [closed-captions/sounds.js](closed-captions/sounds.js).

*let op,* de geluiden zijn niet compleet, dit zal je zelf moeten aanvullen.

## Een eigen fragment (afgeraden, uitgebreide onderbouwing is nodig)

Je kan er ook voor kiezen om een eigen, *beter* fragment te gebruiken. Dit wordt afgeraden. De tijd die je besteedt aan het zoeken naar dat fragment kan je beter besteden aan het werken aan de opdracht. Bovendien blijkt dat er vaak fragmenten worden gekozen die niet goed voldoen aan de opdracht. Als je een ander fragment kiest dan *moet* je dit goed onderbouwd voorleggen aan je docent. De deadline hiervoor is vrijdagochtend in de eerste week.

### Waar moet je op letten bij het kiezen van een eigen fragment.
Lees de opdracht nog eens goed door. Waar gaat het ook al weer precies om? 

Voor een goede onderbouwing van je keuze voor een ander fragment moet je deze vragen in elk geval beantwoorden:

- Welke informatie zit er in de audio die echt niet zichtbaar is?
- Welke rol speelt de audio in het fragment?
- Werkt de scene nog zonder geluid?
- Waarom is dit fragment beter dan het aangeboden fragment?

Je kan dan de nodige HTML en JavaScript genereren door gebruik te maken van [caption generator](https://cmda-minor-vid.github.io/web-typography-18-19/generator/) (in Google Chrome). 

Als je de closed captions wil bewerken dan kan je een tool zoals [Amber Script](https://www.amberscript.com/en) gebruiken. Daar kan je exporteren als `.srt`, en die kan je weer door de generator halen.
