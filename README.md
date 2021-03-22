# CPS2 Modchip
Modchip for suicide free CPS2

Burn on a PIC12F675 or PIC12F629 the HEX file of your romset.

# Pinout for the PIC :

```text
           +---\/---+
     +5V   |1*     8|  GND
     DATA  |2      7|  SETUP2
           |3      6|  CLOCK
           |4      5|  SETUP1
           +--------+
```

# Romset vs Game name corresponding table :

| Romset | Game name  |
| :---:   | :-: |
|   1944  |   1944: The Loop Master (USA 000620)  |
|   1944j  |   1944: The Loop Master (Japan 000620)  |
|   19xx  |   19XX: The War Against Destiny (USA 951207)  |
|   19xxa  |   19XX: The War Against Destiny (Asia 960104)  |
|   19xxar1  |   19XX: The War Against Destiny (Asia 951207)  |
|   19xxb  |   19XX: The War Against Destiny (Brazil 951218)  |
|   19xxh  |   19XX: The War Against Destiny (Hispanic 951218)  |
|   19xxj  |   19XX: The War Against Destiny (Japan 960104  |
|   19xxjr1  |   19XX: The War Against Destiny (Japan 951225)  |
|   19xxjr2  |   19XX: The War Against Destiny (Japan 951207)  |
|   armwar  |   Armored Warriors (Euro 941024)  |
|   armwara  |   Armored Warriors (Asia 941024)  |
|   armwarar1  |   Armored Warriors (Asia 940920)  |
|   armwarr1  |   Armored Warriors (Euro 941011)  |
|   armwaru  |   Armored Warriors (USA 941024)  |
|   armwaru1  |   Armored Warriors (USA 940920)  |
|   avsp  |   Alien vs. Predator (Euro 940520)  |
|   avspa  |   Alien vs. Predator (Asia 940520)  |
|   avsph  |   Alien vs. Predator (Hispanic 940520)  |
|   avspj  |   Alien vs. Predator (Japan 940520)  |
|   avspu  |   Alien vs. Predator (USA 940520)  |
|   batcir  |   Battle Circuit (Euro 970319)  |
|   batcira  |   Battle Circuit (Asia 970319)  |
|   batcirj  |   Battle Circuit (Japan 970319)  |
|   choko  |   Janpai Puzzle Choukou (Japan 010820)  |
|   csclub  |   Capcom Sports Club (Euro 971017)  |
|   csclub1  |   Capcom Sports Club (Euro 970722)  |
|   cscluba  |   Capcom Sports Club (Asia 970722)  |
|   csclubh  |   Capcom Sports Club (Hispanic 970722)  |
|   csclubj  |   Capcom Sports Club (Japan 970722)  |
|   csclubjy  |   Capcom Sports Club (Japan 970722  |
|   cybots  |   Cyberbots: Fullmetal Madness (Euro 950424)  |
|   cybotsj  |   Cyberbots: Fullmetal Madness (Japan 950420)  |
|   cybotsu  |   Cyberbots: Fullmetal Madness (USA 950424)  |
|   ddsom  |   Dungeons & Dragons: Shadow over Mystara (Euro 960619)  |
|   ddsoma  |   Dungeons & Dragons: Shadow over Mystara (Asia 960619)  |
|   ddsomar1  |   Dungeons & Dragons: Shadow over Mystara (Asia 960208)  |
|   ddsomb  |   Dungeons & Dragons: Shadow over Mystara (Brazil 960223)  |
|   ddsomh  |   Dungeons & Dragons: Shadow over Mystara (Hispanic 960223)  |
|   ddsomj  |   Dungeons & Dragons: Shadow over Mystara (Japan 960619)  |
|   ddsomjr1  |   Dungeons & Dragons: Shadow over Mystara (Japan 960206)  |
|   ddsomjr2  |   Dungeons & Dragons: Shadow over Mystara (Japan 960223)  |
|   ddsomr1  |   Dungeons & Dragons: Shadow over Mystara (Euro 960223)  |
|   ddsomr2  |   Dungeons & Dragons: Shadow over Mystara (Euro 960209)  |
|   ddsomr3  |   Dungeons & Dragons: Shadow over Mystara (Euro 960208)  |
|   ddsomu  |   Dungeons & Dragons: Shadow over Mystara (USA 960619)  |
|   ddsomur1  |   Dungeons & Dragons: Shadow over Mystara (USA 960209)  |
|   ddtod  |   Dungeons & Dragons: Tower of Doom (Euro 940412)  |
|   ddtoda  |   Dungeons & Dragons: Tower of Doom (Asia 940412)  |
|   ddtodar1  |   Dungeons & Dragons: Tower of Doom (Asia 940113)  |
|   ddtodh  |   Dungeons & Dragons: Tower of Doom (Hispanic 940412)  |
|   ddtodhr1  |   Dungeons & Dragons: Tower of Doom (Hispanic 940125)  |
|   ddtodhr2  |   Dungeons & Dragons: Tower of Doom (Hispanic 940113)  |
|   ddtodj  |   Dungeons & Dragons: Tower of Doom (Japan 940412)  |
|   ddtodjr1  |   Dungeons & Dragons: Tower of Doom (Japan 940125)  |
|   ddtodjr2  |   Dungeons & Dragons: Tower of Doom (Japan 940113)  |
|   ddtodr1  |   Dungeons & Dragons: Tower of Doom (Euro 940113)  |
|   ddtodu  |   Dungeons & Dragons: Tower of Doom (USA 940125)  |
|   ddtodur1  |   Dungeons & Dragons: Tower of Doom (USA 940113)  |
|   dimahoo  |   Dimahoo (Euro 000121)  |
|   dimahoou  |   Dimahoo (USA 000121)  |
|   dstlk  |   Darkstalkers: The Night Warriors (Euro 940705)  |
|   dstlka  |   Darkstalkers: The Night Warriors (Asia 940705)  |
|   dstlkh  |   Darkstalkers: The Night Warriors (Hispanic 940818)  |
|   dstlku  |   Darkstalkers: The Night Warriors (USA 940818)  |
|   dstlkur1  |   Darkstalkers: The Night Warriors (USA 940705)  |
|   ecofghtr  |   Eco Fighters (World 931203)  |
|   ecofghtra  |   Eco Fighters (Asia 931203)  |
|   ecofghtrh  |   Eco Fighters (Hispanic 931203)  |
|   ecofghtru  |   Eco Fighters (USA 940215)  |
|   ecofghtru1  |   Eco Fighters (USA 931203)  |
|   gigawing  |   Giga Wing (USA 990222)  |
|   gigawinga  |   Giga Wing (Asia 990222)  |
|   gigawingb  |   Giga Wing (Brazil 990222)  |
|   gigawingh  |   Giga Wing (Hispanic 990222)  |
|   gigawingj  |   Giga Wing (Japan 990223)  |
|   gmahou  |   Great Mahou Daisakusen (Japan 000121)  |
|   hsf2  |   Hyper Street Fighter II: The Anniversary Edition (USA 040202)  |
|   hsf2a  |   Hyper Street Fighter II: The Anniversary Edition (Asia 040202)  |
|   hsf2j  |   Hyper Street Fighter II: The Anniversary Edition (Japan 040202)  |
|   hsf2j1  |   Hyper Street Fighter II: The Anniversary Edition (Japan 031222)  |
|   jyangoku  |   Jyangokushi: Haoh no Saihai (Japan 990527)  |
|   megaman2  |   Mega Man 2: The Power Fighters (USA 960708)  |
|   megaman2a  |   Mega Man 2: The Power Fighters (Asia 960708)  |
|   megaman2h  |   Mega Man 2: The Power Fighters (Hispanic 960712)  |
|   mmancp2u  |   Mega Man: The Power Battle (CPS2  |
|   mmancp2ur1  |   Mega Man: The Power Battle (CPS2  |
|   mmatrix  |   Mars Matrix: Hyper Solid Shooting (USA 000412)  |
|   mmatrixj  |   Mars Matrix: Hyper Solid Shooting (Japan 000412)  |
|   mpang  |   Mighty! Pang (Euro 001010)  |
|   mpangj  |   Mighty! Pang (Japan 001011)  |
|   mpangr1  |   Mighty! Pang (Euro 000925)  |
|   mpangu  |   Mighty! Pang (USA 001010)  |
|   msh  |   Marvel Super Heroes (Euro 951024)  |
|   msha  |   Marvel Super Heroes (Asia 951024)  |
|   mshb  |   Marvel Super Heroes (Brazil 951117)  |
|   mshbr1  |   Marvel Super Heroes (Brazil 951024)  |
|   mshh  |   Marvel Super Heroes (Hispanic 951117)  |
|   mshj  |   Marvel Super Heroes (Japan 951117)  |
|   mshjr1  |   Marvel Super Heroes (Japan 951024)  |
|   mshu  |   Marvel Super Heroes (USA 951024)  |
|   mshvsf  |   Marvel Super Heroes Vs. Street Fighter (Euro 970625)  |
|   mshvsfa  |   Marvel Super Heroes Vs. Street Fighter (Asia 970625)  |
|   mshvsfa1  |   Marvel Super Heroes Vs. Street Fighter (Asia 970620)  |
|   mshvsfb  |   Marvel Super Heroes Vs. Street Fighter (Brazil 970827)  |
|   mshvsfb1  |   Marvel Super Heroes Vs. Street Fighter (Brazil 970625)  |
|   mshvsfh  |   Marvel Super Heroes Vs. Street Fighter (Hispanic 970625)  |
|   mshvsfj  |   Marvel Super Heroes Vs. Street Fighter (Japan 970707)  |
|   mshvsfj1  |   Marvel Super Heroes Vs. Street Fighter (Japan 970702)  |
|   mshvsfj2  |   Marvel Super Heroes Vs. Street Fighter (Japan 970625)  |
|   mshvsfu  |   Marvel Super Heroes Vs. Street Fighter (USA 970827)  |
|   mshvsfu1  |   Marvel Super Heroes Vs. Street Fighter (USA 970625)  |
|   mvsc  |   Marvel Vs. Capcom: Clash of Super Heroes (Euro 980123)  |
|   mvsca  |   Marvel Vs. Capcom: Clash of Super Heroes (Asia 980123)  |
|   mvscar1  |   Marvel Vs. Capcom: Clash of Super Heroes (Asia 980112)  |
|   mvscb  |   Marvel Vs. Capcom: Clash of Super Heroes (Brazil 980123)  |
|   mvsch  |   Marvel Vs. Capcom: Clash of Super Heroes (Hispanic 980123)  |
|   mvscj  |   Marvel Vs. Capcom: Clash of Super Heroes (Japan 980123)  |
|   mvscjr1  |   Marvel Vs. Capcom: Clash of Super Heroes (Japan 980112)  |
|   mvscjsing  |   Marvel Vs. Capcom: Clash of Super Heroes (Japan 980123) (Single PCB)  |
|   mvscr1  |   Marvel Vs. Capcom: Clash of Super Heroes (Euro 980112)  |
|   mvscu  |   Marvel Vs. Capcom: Clash of Super Heroes (USA 980123)  |
|   mvscur1  |   Marvel Vs. Capcom: Clash of Super Heroes (USA 971222)  |
|   nwarr  |   Night Warriors: Darkstalkers' Revenge (Euro 950316)  |
|   nwarra  |   Night Warriors: Darkstalkers' Revenge (Asia 950302)  |
|   nwarrb  |   Night Warriors: Darkstalkers' Revenge (Brazil 950403)  |
|   nwarrh  |   Night Warriors: Darkstalkers' Revenge (Hispanic 950403)  |
|   nwarru  |   Night Warriors: Darkstalkers' Revenge (USA 950406)  |
|   pfghtj  |   Pocket Fighter (Japan 970904)  |
|   pgear  |   Powered Gear: Strategic Variant Armor Equipment (Japan 941024)  |
|   pgearr1  |   Powered Gear: Strategic Variant Armor Equipment (Japan 940916)  |
|   progear  |   Progear (USA 010117)  |
|   progeara  |   Progear (Asia 010117)  |
|   progearj  |   Progear no Arashi (Japan 010117)  |
|   pzloop2  |   Puzz Loop 2 (Euro 010302)  |
|   pzloop2j  |   Puzz Loop 2 (Japan 010226)  |
|   pzloop2jr1  |   Puzz Loop 2 (Japan 010205)  |
|   qndream  |   Quiz Nanairo Dreams: Nijiirochou no Kiseki (Japan 960826)  |
|   ringdest  |   Ring of Destruction: Slammasters II (Euro 940902)  |
|   ringdesta  |   Ring of Destruction: Slammasters II (Asia 940831)  |
|   ringdesth  |   Ring of Destruction: Slammasters II (Hispanic 940902)  |
|   ringdestb  |   Ring of Destruction: Slammasters II (Brazil 940902)  |
|   rmancp2j  |   Rockman: The Power Battle (CPS2  |
|   rockman2j  |   Rockman 2: The Power Fighters (Japan 960708)  |
|   sfa  |   Street Fighter Alpha: Warriors' Dreams (Euro 950727)  |
|   sfa2  |   Street Fighter Alpha 2 (Euro 960229)  |
|   sfa2u  |   Street Fighter Alpha 2 (USA 960430)  |
|   sfa2ur1  |   Street Fighter Alpha 2 (USA 960306)  |
|   sfa3  |   Street Fighter Alpha 3 (Euro 980904)  |
|   sfa3b  |   Street Fighter Alpha 3 (Brazil 980629)  |
|   sfa3h  |   Street Fighter Alpha 3 (Hispanic 980904)  |
|   sfa3hr1  |   Street Fighter Alpha 3 (Hispanic 980629)  |
|   sfa3u  |   Street Fighter Alpha 3 (USA 980904)  |
|   sfa3ur1  |   Street Fighter Alpha 3 (USA 980629)  |
|   sfa3us  |   Street Fighter Alpha 3 (USA 980616  |
|   sfar1  |   Street Fighter Alpha: Warriors' Dreams (Euro 950718)  |
|   sfar2  |   Street Fighter Alpha: Warriors' Dreams (Euro 950627)  |
|   sfar3  |   Street Fighter Alpha: Warriors' Dreams (Euro 950605)  |
|   sfau  |   Street Fighter Alpha: Warriors' Dreams (USA 950627)  |
|   sfz2a  |   Street Fighter Zero 2 (Asia 960227)  |
|   sfz2al  |   Street Fighter Zero 2 Alpha (Asia 960826)  |
|   sfz2alb  |   Street Fighter Zero 2 Alpha (Brazil 960813)  |
|   sfz2alh  |   Street Fighter Zero 2 Alpha (Hispanic 960813)  |
|   sfz2alj  |   Street Fighter Zero 2 Alpha (Japan 960805)  |
|   sfz2b  |   Street Fighter Zero 2 (Brazil 960531)  |
|   sfz2br1  |   Street Fighter Zero 2 (Brazil 960304)  |
|   sfz2h  |   Street Fighter Zero 2 (Hispanic 960304)  |
|   sfz2j  |   Street Fighter Zero 2 (Japan 960430)  |
|   sfz2jr1  |   Street Fighter Zero 2 (Japan 960227)  |
|   sfz2n  |   Street Fighter Zero 2 (Oceania 960229)  |
|   sfz3a  |   Street Fighter Zero 3 (Asia 980904)  |
|   sfz3ar1  |   Street Fighter Zero 3 (Asia 980701)  |
|   sfz3j  |   Street Fighter Zero 3 (Japan 980904)  |
|   sfz3jr1  |   Street Fighter Zero 3 (Japan 980727)  |
|   sfz3jr2  |   Street Fighter Zero 3 (Japan 980629)  |
|   sfza  |   Street Fighter Zero (Asia 950627)  |
|   sfzar1  |   Street Fighter Zero (Asia 950605)  |
|   sfzb  |   Street Fighter Zero (Brazil 951109)  |
|   sfzbr1  |   Street Fighter Zero (Brazil 950727)  |
|   sfzh  |   Street Fighter Zero (Hispanic 950718)  |
|   sfzhr1  |   Street Fighter Zero (Hispanic 950627)  |
|   sfzj  |   Street Fighter Zero (Japan 950727)  |
|   sfzjr1  |   Street Fighter Zero (Japan 950627)  |
|   sfzjr2  |   Street Fighter Zero (Japan 950605)  |
|   sgemf  |   Super Gem Fighter Mini Mix (USA 970904)  |
|   sgemfa  |   Super Gem Fighter: Mini Mix (Asia 970904)  |
|   sgemfh  |   Super Gem Fighter: Mini Mix (Hispanic 970904)  |
|   smbomb  |   Super Muscle Bomber: The International Blowout (Japan 940831)  |
|   smbombr1  |   Super Muscle Bomber: The International Blowout (Japan 940808)  |
|   spf2t  |   Super Puzzle Fighter II Turbo (Euro 960529)  |
|   spf2ta  |   Super Puzzle Fighter II Turbo (Asia 960529)  |
|   spf2th  |   Super Puzzle Fighter II Turbo (Hispanic 960531)  |
|   spf2tu  |   Super Puzzle Fighter II Turbo (USA 960620)  |
|   spf2xj  |   Super Puzzle Fighter II X (Japan 960531)  |
|   ssf2  |   Super Street Fighter II: The New Challengers (World 931005)  |
|   ssf2a  |   Super Street Fighter II: The New Challengers (Asia 931005)  |
|   ssf2ar1  |   Super Street Fighter II: The New Challengers (Asia 930914)  |
|   ssf2h  |   Super Street Fighter II: The New Challengers (Hispanic 930911)  |
|   ssf2j  |   Super Street Fighter II: The New Challengers (Japan 931005)  |
|   ssf2jr1  |   Super Street Fighter II: The New Challengers (Japan 930911)  |
|   ssf2jr2  |   Super Street Fighter II: The New Challengers (Japan 930910)  |
|   ssf2r1  |   Super Street Fighter II: The New Challengers (World 930911)  |
|   ssf2t  |   Super Street Fighter II Turbo (World 940223)  |
|   ssf2ta  |   Super Street Fighter II Turbo (Asia 940223)  |
|   ssf2tb  |   Super Street Fighter II: The Tournament Battle (World 931119)  |
|   ssf2tba  |   Super Street Fighter II: The Tournament Battle (Asia 931005)  |
|   ssf2tbh  |   Super Street Fighter II: The Tournament Battle (Hispanic 931005)  |
|   ssf2tbj  |   Super Street Fighter II: The Tournament Battle (Japan 931005)  |
|   ssf2tbj1  |   Super Street Fighter II: The Tournament Battle (Japan 930911)  |
|   ssf2tbr1  |   Super Street Fighter II: The Tournament Battle (World 930911)  |
|   ssf2th  |   Super Street Fighter II Turbo (Hispanic 940223)  |
|   ssf2tu  |   Super Street Fighter II Turbo (USA 940323)  |
|   ssf2tur1  |   Super Street Fighter II Turbo (USA 940223)  |
|   ssf2u  |   Super Street Fighter II: The New Challengers (USA 930911)  |
|   ssf2xj  |   Super Street Fighter II X: Grand Master Challenge (Japan 940311)  |
|   ssf2xjr1  |   Super Street Fighter II X: Grand Master Challenge (Japan 940223)  |
|   ssf2xjr1r  |   Super Street Fighter II X: Grand Master Challenge (Japan 940223 rent version)  |
|   uecology  |   Ultimate Ecology (Japan 931203)  |
|   vampj  |   Vampire: The Night Warriors (Japan 940705)  |
|   vampja  |   Vampire: The Night Warriors (Japan 940705 alt)  |
|   vampjr1  |   Vampire: The Night Warriors (Japan 940630)  |
|   vhunt2  |   Vampire Hunter 2: Darkstalkers Revenge (Japan 970929)  |
|   vhunt2r1  |   Vampire Hunter 2: Darkstalkers Revenge (Japan 970913)  |
|   vhuntj  |   Vampire Hunter: Darkstalkers' Revenge (Japan 950316)  |
|   vhuntjr1  |   Vampire Hunter: Darkstalkers' Revenge (Japan 950307)  |
|   vhuntjr1s  |   Vampire Hunter: Darkstalkers' Revenge (Japan 950307 stop version)  |
|   vhuntjr2  |   Vampire Hunter: Darkstalkers' Revenge (Japan 950302)  |
|   vsav  |   Vampire Savior: The Lord of Vampire (Euro 970519)  |
|   vsav2  |   Vampire Savior 2: The Lord of Vampire (Japan 970913)  |
|   vsava  |   Vampire Savior: The Lord of Vampire (Asia 970519)  |
|   vsavb  |   Vampire Savior: The Lord of Vampire (Brazil 970519)  |
|   vsavh  |   Vampire Savior: The Lord of Vampire (Hispanic 970519)  |
|   vsavj  |   Vampire Savior: The Lord of Vampire (Japan 970519)  |
|   vsavu  |   Vampire Savior: The Lord of Vampire (USA 970519)  |
|   xmcota  |   X-Men: Children of the Atom (Euro 950331)  |
|   xmcotaa  |   X-Men: Children of the Atom (Asia 950105)  |
|   xmcotaar1  |   X-Men: Children of the Atom (Asia 941217)  |
|   xmcotab  |   X-Men: Children of the Atom (Brazil 950331)  |
|   xmcotah  |   X-Men: Children of the Atom (Hispanic 950331)  |
|   xmcotahr1  |   X-Men: Children of the Atom (Hispanic 950105)  |
|   xmcotaj  |   X-Men: Children of the Atom (Japan 950105)  |
|   xmcotaj1  |   X-Men: Children of the Atom (Japan 941222)  |
|   xmcotaj2  |   X-Men: Children of the Atom (Japan 941219)  |
|   xmcotaj3  |   X-Men: Children of the Atom (Japan 941217)  |
|   xmcotajr  |   X-Men: Children of the Atom (Japan 941208 rent version)  |
|   xmcotar1  |   X-Men: Children of the Atom (Euro 950105)  |
|   xmcotau  |   X-Men: Children of the Atom (USA 950105)  |
|   xmvsf  |   X-Men Vs. Street Fighter (Euro 961004)  |
|   xmvsfa  |   X-Men Vs. Street Fighter (Asia 961023)  |
|   xmvsfar1  |   X-Men Vs. Street Fighter (Asia 961004)  |
|   xmvsfar2  |   X-Men Vs. Street Fighter (Asia 960919)  |
|   xmvsfar3  |   X-Men Vs. Street Fighter (Asia 960910)  |
|   xmvsfb  |   X-Men Vs. Street Fighter (Brazil 961023)  |
|   xmvsfh  |   X-Men Vs. Street Fighter (Hispanic 961004)  |
|   xmvsfj  |   X-Men Vs. Street Fighter (Japan 961023)  |
|   xmvsfjr1  |   X-Men Vs. Street Fighter (Japan 961004)  |
|   xmvsfjr2  |   X-Men Vs. Street Fighter (Japan 960910)  |
|   xmvsfjr3  |   X-Men Vs. Street Fighter (Japan 960909)  |
|   xmvsfr1  |   X-Men Vs. Street Fighter (Euro 960910)  |
|   xmvsfu  |   X-Men Vs. Street Fighter (USA 961023)  |
|   xmvsfur1  |   X-Men Vs. Street Fighter (USA 961004)  |
|   xmvsfur2  |   X-Men Vs. Street Fighter (USA 960910)  |


You can also check inside mame source to get romset name by eprom label :

https://github.com/mamedev/mame/blob/master/src/mame/drivers/cps2.cpp

A huge thanks to Eduardo Cruz, without him, nothing would have happened.
His blog and informations about wiring to your CPS2 :

http://arcadehacker.blogspot.com/2016/09/capcom-cps2-security-programming-guide.html
