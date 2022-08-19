# GoldenAge
A SMuFL update to a handwritten style of music font.


The GoldenAge music notation font was written by Don Rice in the early 90s, and has been a very popular exemplar of the hardwritten style often found in Jazz and Pop sheets.

Don Rice has kindly allowed me to update the font to the SMuFL standard for Unicode music glyph layout. It remains a work in progress, but should be usable. 

The original ("legacy") package contained four fonts: two music fonts "Music" and "Xtra"; and two text fonts "Title" and "Text". The characters of the two text fonts are stylistically identical, just with different bounding box heights; the Xtra music font contains a small number of alternative and additional symbols. 

Because the SMuFL character range does not conflict with the standard text font characters, I have decided to merge all the characters, text and music, into one font. The text characters have been expanded, with extra diacritic-vowel combinations, and improved kerning.

The font is consequently given a different name (including PostScript name) from the legacy package. This allows the old fonts can continue to be used in old documents. Documents updated to the new font will need to be checked to ensure that nothing has moved!

### BOXES  
The font uses glyphs to create boxes around text. There are left and right ends, and zero-width horizontal lines that can be interspersed between each character inside the box.

**Complete Box:**  
Integral, Delta: Left right ends.  
Infinity: top and bottom (used between each character)  

**Bottomless box:**   
Guillemot Left, Right: Ends  
Section: Top  

**Topless Box:**  
Guillemot Single Left right  
Double dagger: Bottom line  


### INSTALLATION 
Install the font in the usual way. The JSON file must be added to the following location:

Windows: `C:\Program Files\Common Files\SMuFL\Fonts\Golden Age\Golden Age.json`  
Mac: `/Library/Application Support/SMuFL/Fonts/Golden Age/Golden Age.json`

### LICENCE

This font is © Don Rice, revised by Ben Byram-Wigfield, and released under the SIL Open Font Licence. See the accompanying OFL.txt file.
