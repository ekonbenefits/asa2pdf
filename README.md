# asa2pdf
From http://www.urbanjost.altervista.org/LIBRARY/libGPF/EXE/ASA/srcc/asa_to_pdf.c

When you are using Microsoft Powerstation 4.0 in Powerstation 1.0 compat mode
and OPEN `LPT1` or `PRN` give you FILE NOT FOUND, and you have to resort to using `\\.\LPT1` or  `\\.\PRN`
which doesn't use the CARRIAGECONTROL since it's hardcoded in the older variant and instead you use NET USE LPTX to 
[Multi File Port Monitor](https://sourceforge.net/projects/mfilemon/) which passes it to this program to make a PDF.
