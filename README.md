# txt2chord
Input a song file with chords above lyrics, outputs in chordpro format

useage.. txt2chord [InFILE][OutFILE]

Mandatory arguement .. Input filename 
Optional .. Output filename (include the .cho extension)

Lots of songs are available online as text files, web pages, Word files,  pdf's or image files with chords written 
above the lyrics.

txt2chord (with some help from some outside utilities) converts pretty much anything that is text or can be converted to 
text more or less automatically to chordpro format.

On Ubuntu Linux, pdftotext -layout filename for pdf ==>text and tesseract for converting image files to text.

This does not handle every possible messy input file.  But at worst few minutes editing will clean things up. 


