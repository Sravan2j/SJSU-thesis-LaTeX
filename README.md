<h2>SJSU Thesis Template</h2>

I am not the original author of this template.  It is modified from a template created by the University of Rhode Island (URI).  A link to their original template is: http://egr.uri.edu/ele/thesisguide/step2/

I am not even the original author of the SJSU version of the template.  I got it from Dr. Thomas Austin (https://github.com/taustin).  When I used the original template as is, it was rejected by San Jose State's GUP department for no compliance with the thesis guidelines.  I modified the template to conform with the rules as of December 2016.  You should refer to their latest guidelines (http://www.sjsu.edu/gup/gradstudies/thesis/) as their requirements are updated regularly.

As part of my thesis, I switched to BibTex.  The requirements needed to use BibTex are below.  These should be done after the thesis is successfully built.

1. Rather than building with standard BibTex, use the file "uribibtex.bat" that is bundled with this repository.  If you are using a Tex editor (which I highly recommend), you should have it point to this file instead of the standard BibTex executible.

2. To rebuild the references file used by the tool in #1, you should double click on the file "genbib.bat" in the "build" subdirectory.

The example steps for BibTex were debugged on a Mac. Given the "*.bat" files, the approach above probably will not work out of the box on a Mac.  Here is a link with more general information on using BibTex.

I am also including a Texmaker session so you can load it into Texmaker directly.  You need to modify the session file to match the local path on your machine.  If you can get TexStudio working instead, it is a better tool in my humble opinion.
