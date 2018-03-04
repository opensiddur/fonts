This package contains a collection of fonts of ancient Semitic 
scripts related to the history of the Hebrew writing.
The collection contains the following fonts:

 1. Proto Canaanite	        Sarabit al-Kadim inscriptions  ~1500 BCE
 2. Phoenician Ahiram	        Ahiram of Gebel Sarcophagus    ~1200 BCE
 3. Hebrew Paleo Gezer	        The Gezer calendar               10C BCE
 4. Hebrew Paleo Mesha	        The Mesha stele (Moabite Stone)  850 BCE
 5. Hebrew Paleo Siloam	        The Siloam inscription           703 BCE
 6. Hebrew Paleo Lachish	Lachish ostraca                 ~500 BCE
 7. Hebrew Paleo Qumran	        Leviticus scroll, Qumran         ~2C BCE
 8. Hebrew Samaritan	        Samaritan Pentateuch             14C  CE
 9. Aramaic Early Br-Rkb	Bar Rkb   inscription             8C BCE
10. Aramaic VIIBCE		Gözne inscription                 7C BCE
11. Aramaic Imperial Yeb	Yeb (Elephantine) papyri         407 BCE
12. Hebrew Square Isaiah	Great Isaiah scroll, Qumran       2C BCE
13. Hebrew Square Habakkuk	Habakkuk Commentary, Qumran       ~0  CE
14. Hebrew Square BenKosba      Bar Kochba letters               ~130 CE
15. Hebrew Square Bet-Shearim   Bet Shearim Burial inscriptions    3C CE
16. Keter Aram Tsova	        Aleppo Codex                      10C CE
17. Hebrew Sofer Stam Ashkenaz  Traditional Torah scrolls letter forms

The next 2 fonts, although not really ancient, are based on ancient fonts
in the package and therefore I decided to add them to it as well.
  
18. Makabi YG                   Based on Isaiah scroll but modernized
19. Keter YG (4 weights)        Based on Aleppo Codex but modernized


The basic Canaanite alphabet consisted of 22 signs representing
consonants (in some languages like Ugarit up to 27 signs). 
The names of the signs are/were very similar to the still
used names of Hebrew letters.

All the fonts contain the glyphs in the Hebrew Unicode code range (0590-05FF).
Starting with Unicode standard 5.2, the Phoenician, Imperial Aramaic
and Samaritan languages have their own designated code ranges. 
Therefore, the relevant fonts have the glyphs encoded in their respective
Unicode designated ranges as well.

Fonts 1,2,3,4,5,6,7 and 9 contain the glyphs in the Phoenician
Unicode range (10900-1091F).

Font 8 contain the glyphs in the Samaritan code range (0800-083F).
Note: This font does not implement Samaritan vowel, punctuation and accent
marks. I hope to implement those in future versions

Fonts 10 and 11 contain the glyphs in the Aramaic Imperial
code range (10840-1085f)

Font  18 include and implement the Hebrew vowel punctuation.
Fonts 16 and 19 implement the full Hebrew punctuation (vowels and
cantillation marks)

Font 1, the Proto Canaanite, is unique since in the inscriptions,
more that one picture form was found that represent a single consonant.
I encoded several of this alternate forms into the font. To access
the alternate forms (when those exist) the following sequences should be used:
While in Hebrew code range:
    "Base letter" + "Dagesh (U+05BC)" will display first alternate form
    "Base letter" + "Rafe (U+05BF)"   will display second alternate form
While in Phoenician code range:
    "Base letter" + "Phoenician number 10 (U+10917)
                                      will display first alternate form
    "Base letter" + "Phoenician number 20 (U+10918)                             
                                      will display second alternate form
 
 
The accompanying documentation is in Hebrew. I hope to provide
English documentation in the future.

Yoram Gnat
