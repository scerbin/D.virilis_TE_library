# D.virilis_TE_library
Assemblage of TE libraries for _D. virilis_

These files are from TE libriaries in the Blumentstiel lab
https://www.blumenstiellab.org/

The library was created using Repeat Masker and a custom program to extend, align and find the termini of repeats. 
This was developed by Hubley and run by colloabators David Ray at the University of Texas A&M.

See https://doi.org/10.3390/biology11101480 for more information.

The library from 03_22_2021 has 18 annotated TEs 

The library from 01_25_2022 has 639 annotated TEs

The library from 01_16_2023 has 630 annotated TEs

The process to curate was tohe following.

Visualize the TE in Genious looking for duplications, internal nested repeats and other indicators of poor annoatation as a candidate library TE.

Then CDhit was run on the library.

This resulted in the 01_25_2022 library

Further libraries are curated using Censor and other homology searches. 

I prioritized mannually curating the library starting with the unknown elements i.e. >9_rnd-6_family-1736__Unknown

If there was a Repbase hit to this element I checked if there was a similar element elsewhere in the library.

If yes I removed it. If no I renamed the element adding in the annotation from Repbase + _like eg. >9_rnd-6_family-1736__Gypsy_like

This was repeated and files added from the date they were constructed.

