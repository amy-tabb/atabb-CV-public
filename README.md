# atabb-CV-public

This repository provides an example CV in one .tex file, without the use of a class, in latex, suitable for ECE or CS researchers.  The repo is a companion to [this post](https://amytabb.com/ts/2018_11_01/).

*August 4, 2019* 

Updated
*March 18, 2020*

- Most recent version: `TabbCV_Jul2019_public`
- 2018 version: `Tabb_public_release`
- early grad student: `EarlyProfCVTemplate`

I created this repository back in late 2018, but less than a year later my CV has changed a lot and I added some new things.  I've added my current document `TabbCV_Jul2019_public`, but also kept the original one.  Note that how to order your CV, and what to put on it, seems to have no standard.  I've seen ones with the reverse order of mine (excepting education, which for academics, seems to always be first)!

There's more commentary about this on my website:
- [general post](https://amytabb.com/ts/2018_11_01/)
- [getting started, for graduate students](https://amytabb.com/ts/2019_02_02/)
- [personal information on CVs and EEO in the USA](https://amytabb.com/ts/2019_02_20/)

You may also want to check out Igal Tabachnik's [CV repository](https://github.com/hmemcpy/cv) for non-academic positions.

*March 18, 2020*

I added another template, but this one for a hypothetical person -- you're an early career professional, interested in research-type jobs and/or graduate school.  I was helping a friend with his CV, and when looking for templates, I realized there weren't really good options out there.  So I hacked together Igal Tabachnik's CV and added some items from mine.  The result is `EarlyProfCVTemplate.tex`.  As with any CV template, if a section doesn't apply to you -- delete it.  Also, you can create your own headings.  Look at other CVs of those in your field to get a sense of what might make sense to put on your own CV.

For any of these templates, if you are a latex newbie, you can go to [overleaf](overleaf.com) and use a cloud-based service to edit and compile the document.  Create an account, create a blank document, and copy all of the text from a .tex file in, and try to compile.  You should see the result on the right side of the screen.

For local compilation (what I do), on Ubuntu:

`sudo apt-get install texlive-full texlive-science texlive-fonts-extra texstudio`

The last item is optional -- I like texstudio, others like texmaker.  Experiment.  Ok!  Walk away, because this will take an age. (Technically, you may not need all of these packages, but this for sure will get you through scientific paper writing AND compiling this CV.)

Then, open the `.tex` file of interest with texstudio, press F5 to compile.  On the right side, you'll see the preview of the document, and in the directory where you have the `.tex` file, there will be a `.pdf` of your document.  

