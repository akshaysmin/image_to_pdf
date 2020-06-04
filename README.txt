----------How to use----------

Usage in terminal/command prompt:
	python image_to_pdf.py <imagefolder> <imageformat> <outfile>

This selects all files in <imagefolder> with filenames ending with <imageformat>, sorts them in logical order of names using "sensible_sort.py", and combine them to form a single pdf, in the path <outfile>

NOTE:
<imageformat> must be an image format like .jpg, .png, etc.
<outfile> must end in .pdf

---------Requirements---------
PIL,os,sys,sensible_sort
------------------------------