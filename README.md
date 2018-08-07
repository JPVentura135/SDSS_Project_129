# SDSS Projects 73 & 129

This repository hosts all the information necessary for getting set up to work on this project. Included will be all the information dedicated to data querying, downloading, structuring and analysis procedures as well as functions and software necessary for project 129. 

First thing is first, lets get you started on your SDSS journey.

## Getting Started with SDSS

### About the Survey:

Please take some time to read about the current SDSS-IV survey [here](https://www.sdss.org/surveys/#eBOSS). Be generally familiar with the SDSS subprojects and what their scientific objectives are, particularly eBOSS, TDSS and SEGUE-1, since these are the data campaigns that deal most with research projects 73 & 129. Also briefly read over the telescopes and instruments noting the sections on the Apache point and the Irénée du Pont Telescopes. 

### Getting on the email list + setting up trac account: 

Before getting into the particulars of the project, lets get plugged into the SDSS information stream. You'll want to get signed up with the SDSS-IV mailing list at this [link](https://mailman.sdss.org/mailman/listinfo/sdss4-general) and the SDSS trac page (basically the SDSS blog/wiki page) at this [link.](https://trac.sdss.org/register) The wiki is super important, as there's a lot of collaboration information that's only available there (for example, links to the places where data is hiding and future meeting schedules). I also think that with the wiki registration comes access to the SDSS collaboration-only pages.

### Introductory exercises:

Here is a dropbox [link](https://www.dropbox.com/sh/m54iqkb9hbqrqtj/AABEXjMDEza_ixzNG9Pa-qKqa?dl=0) to a folder containing exercises that will closely reflect the work you will be doing as part of the projects and relevant literature.


## Project details:

You will be using SEGUE,SEQUELS and TDSS data to Examine the Magnetic Variability on the Coolest Stars on the [main sequence](https://en.wikipedia.org/wiki/Main_sequence) (M-dwarfs)

M and L dwarfs(substellar objects, not on the main sequence) are well known for their magnetic activity, which can be observed at optical wavelengths through rotational/spot modulation, dramatic flare events, and atomic emission (often using the H-alpha emission line). One key element to understanding the formation and evolution of magnetic fields on these dwarfs is their variability, in both photometric and spectroscopic observations. Using data from the Time Domain Spectroscopic Survey (TDSS),you will examine magnetic variability on cool (M) and ultracool (late-M and early-L) dwarfs in two ways.

Each target in the main TDSS survey is selected based on photometric variability criteria, then follow-up spectra are obtained to understand the cause of variability. In the SDSS-III TDSS pilot survey, 1% of the sample (2310 objects) were variable M dwarfs, and those M dwarfs were more likely to show H-alpha in emission. The expansion of the M dwarf sample by an order of magnitude during the SDSS-IV TDSS main survey provides the opportunity to examine the differences between variability-selected and non-variable M dwarfs as a function of spectral type and Galactic height, probing the variability of M dwarfs with respect to both age and mass.

The Few-Epoch Spectroscopy (FES) component of TDSS probes spectroscopic variability through repeat observations of targets with previous spectroscopy. Through TDSS FES, we are obtaining spectra of approximately 1000 ultracool dwarfs previously observed in DR7 to examine the differences in their chromospheres over time using the H-alpha emission line. Due to the timing of initial SDSS spectroscopy and TDSS, these observations provide a unique opportunity to examine variability on timescales of 1-10 years. Long-timescale variability may trace changes in the underlying magnetic field (similar to the solar cycle), providing constraints on the dynamo operating in these low-mass objects.


## Spectral Typing I: 

In order to do these analyses we must issue spectral types to the entire sample of variable objects. This is a procedure done by eye whereby an objects spectrum is plotted against spectral type standards, or templates, for various spectral types. The spectral type template (also a wavelength vs flux plot) which overlaps most closely with the object spectrum thus identifies the spectral type of the object. Bear in mind this is not an exact science. The object spectrum rarely overlaps perfectly with the spectral type template but the idea is to choose/issue the spectral type that most closely fits the object spectrum. Below is an image for instruction.

![Spectral type overplot](/Users/jventura/BDNYC/SDSS_FAST/SDSS_Project_129/EarlynMins652.png)

![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")

It is encouraged for you to try to do this with a couple of objects in the Python programming language for an exercise in coding. The complete research sample to be analyzed between both projects is very large. It would be an enormous task to plot the objects one-by-one, plot-by-plot this way. Thankfully we have the [*Pyhammer*](https://github.com/BU-hammerTeam/PyHammer) at our disposal. Read the README page behind the link and clone the pyhammer repository into your computer.

Before we get to anything, lets go over some Python things:

### Python & Anaconda:
Download the [Anaconda distribution](https://www.anaconda.com/download/#macos). This link is for a mac download but if you're a windows user make sure you choose the appropriate file version on the same page. Also be SURE to click on the download link for the '''Python 3.6''' Version. The Anaconda distribution is an assembly of function and code libraries widely used and applicable to analysis in the sciences. It's a must for any data analysis.

after the installation is done make sure everything is running as it should by going to your command line and typing:

`conda info`

You should then see a quick rundown on the version and specs of the distribution you downloaded. Although you just essentially downloaded python 3.6, the pyhammer program must be run on version 3.5. Because it requires a different version, Anaconda will be useful in creating an 'environment' which is a python version bubble. A bubble which you can customize with whichever packages you'd like and more importantly any python version you'd like.

Create an environment for python 3.5 by reading the documentation pages [here](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands) and paying particular attention to the sections:

  * creating an environment with commands
    * "To create an environment with a specific version of Python and multiple packages:"
    Note: You don't have to specify any packages only the python version and the name you wish to give the environment.
  * Activating an environment
  * Deactivating an environment  

## Spectral Typing (continued)





  

  








