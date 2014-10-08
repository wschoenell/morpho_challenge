Following our discussions last week in Teruel, we are pleased to
announce the J-PAS Morphology Challenge.

The goal of the challenge is to calibrate the automated methods and
algorithms available to carry out the morphological analysis of J-PAS
galaxies as well as to estimate the amount of computer time required. As
a reminder, at the last meeting, we decided that we will use the new
Sextractor version (once it is properly tested ) as a first guess for
the morphological parameters since it is easy to include it the J-PAS
reduction pipeline. In a second step, we will run a more complete code.

Given the similarity between J-PAS and ALHAMBRA data, we will use one
ALHAMBRA field to test the codes. All members of the galaxy evolution
working group are invited to participate.

All the information below as well as the data needed for the challenge
is available at the J-PAS wiki:
http://wiki.j-pas.org/index.php/TG2_Morphology#J-PAS_Morphology_Challenge

Challenge rules for all participants:

DEADLINE: December 1st 2014

Rules: - Run your favorite code on AT LEAST the 579 objects from the
catalog: All the objects fall in the ALH04 field, pointing 01, CCD4, so
you need to download only one field. - Run your code on at least 2
filters: 613 and the detection synthetic filter 814W. - If you need to
estimate a PSF you can use the public ALHAMBRA catalog to select stars
in the field (http://svo2.cab.inta-csic.es/vocats/alhambra/).

Outputs expected: - Catalog of at least 579 objects containing all the
parameters your code has measured. - Time spent by your code to run
(without source detection, PSF estimation etc...) and computer ressources
used.

Provided data products: All data products required o participate in the
challenge can be downloaded here:
https://upload.obspm.fr/get?k=GCqfoL25mrw73LyKT6k
- Catalog of 579 objects with measured morphologies and sersic fits with
HST-COSMOS data - ALH04-p01-CCD4 field in 2 bands (613-814). Zeropoints
are in the mage headers (keyword: ZPTSYNTE I think)

For those teams willing to test their codes in more filters
simultaneously (e.g MMorph), please contact us so that we can give you
access to the other ALHAMBRA images.

FINAL NOTE: If you want to participate in the challenge, we would
appreciate if you could send us (Marc and Yolanda) an email specifying
the names of people involved as well as the code you will be running to
keep track of interested teams and update the wiki pages.