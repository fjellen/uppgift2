# uppgift2
Jag började med att titta på skiss.jpg och se vad som skulle göras. Jag började med att öppna skiss.jpg i paint 3d och klippte ut mina bilder/banners.
Sen skapade jag ett nytt projekt och skapade en index.html fil samt en style.css. I min style.css så imoprterade jag bara andra .css filer för att göra layouten enklare.
Jag började med att göra en header som bara skulle synas i mobilt läge och sen började jag med att göra en div över hela sidan (content med två divar i sig (left & right).
Jag stylade storleken på mina divar i varsin css fil, left.css, right.css, top.css och general.css.
I general.css la jag in styling regler för .content som ska innehålla både left.css och right.css, regler som (margin-top:2.5rem; width:80rem; height:49rem; border:solid; display:flex;)
Nu har jag regler över min arbetsyta samt att jag har flyttat den så det ser trevligare ut.
I min left.css la jag bara in bilden samt storleken på höjd och bredd.
I right.css la jag in storleken på höjd och bredd.
Sen kollade jag på skiss.jpg för att se vad som jag skulle göra. Överst på den högra sidan var en rubrik som var förskjuten neråt, så jag använde en h1.
Sen skulle det vara en mindre text med en länk i sig så jag använde en h2 med en a href="#" i sig, jag la in en class i h2 taggen för att kunna styla den med en margin-bottom.
Nästa steg var att fixa mina tre buttons, en lång med både bild och text och sen två mindre med bara bild.
Så jag gjorde en div class="formsection" som jag skulle använda till först mina knappar och sen till samtliga forms.
Först så gick jag in på google.se och sökte upp logotyp bilder till facebook, google och apple. Jag sparade bilderna och drog in dem i min img mapp.
Sen gjorde jag a href="#" med en klass för knappen och en klass för bilden.
Med de klasserna kunde jag styla både knapparna samt bilderna i dem.
Nästa sak var en liten centrerad text "-or-" så jag gjorde en ny h2 med en klass för att kunna centrera just den.
Nästa del var att ha tre inlognings formulär med varsin label över, så jag använde min tidigare div class="formsection" och la in label samt input för alla tre raderna.
Efter jag hade fixat regler angående form och label så började jag med att fixa fyra utdragna ruto under min password form, som skulle symbolisera passwordstrenght.
Nästa sak var en checkbox med text efter sig, så jag skapade en input type="checkbox" och skrev den vanliga texten med p.
Nu var desktop versionen klar och jag skapade en ny .css fil som jag döpte till media.css och importerade den i min style.css.
Där satte jag två olika huvudregler, bredd mindre än 600px och bredd mer än 600px.
Jag la in en header i början av min body, den hade min banner-bild som jag la i en klass (.header-asgard)
I @media (min-width: 600px sa jag att .header-asgard inte skulle synas (display:none;)
I @media (max-width: 600px sa jag att min .left inte skulle synas samt styling regler för att det skulle bli finare, tex att min text inte skulle vara lika inskjuten som på desktop verionen.
Jag fick även styla om min .content i höjd så att allt fick plats på sidan utan att man behövde scrolla.
Jag la in en animation på den sista rutan i min passwordbar så att den skiftar färg,6 olika färger på loppet av 10 sekunder i all oändlighet, la även in en alternate så att den skiftar tillbaka och inte bara börjar om.
Jag la in meta taggar för viewport, description, keywords, author, charset, compitable. Jag la även in alt taggar på samtliga bilder. Jag hade kunnat länka in min sida ifrån andras sidor, samt lägga in google analytics.
