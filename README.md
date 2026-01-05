Beszélgetés megnyitva. 25 üzenet. 1 olvasatlan üzenet. 


Ugrás a tartalomra
A Gmail használata képernyőolvasóval
2 781/13.
paper on SLRs
Beérkező levelek

Maria Lugaro
Mellékletek
2025. máj. 9. 13:04
Dear all, a first complete draft of Benjamin (the young)'s paper is ready! As we both are busy until the end of May, we pass it over for you to check and send u
22

Benjámin Soós
2025. dec. 16. 8:46
Dear Andrés and Tom, Thank you for your replies! Thanks Andrés, I'll update the licence accordingly. Have a nice week, Benjámim

Andrés Yagüe
Mellékletek
2025. dec. 21. 6:25
címzett: én, Andres

Benjámin,

I am still looking at the paper, but I have one last comment for the code repository. I see that you tried to structure the README.md using some ascii characters which is not a bad idea, but it being a markdown file you can get something that renders a bit nicer. For example, if you use the attached README.md, you'll get the github page to show something like this:

image.png
I also have added installation instructions, which I think can be helpful. Let me know your opinion! If you want to see how markdown files are going to show up, you can use this very useful tool:

https://markdownlivepreview.com/

It gives you tips and lets you try things live.

Cheers,
Andrés
 Egy melléklet
  •  A Gmail által ellenőrizve
# SLRs vs Meanlife plotting script

## Description

This Python script can create plots similar to the ones in Soós et al. 2025

Co-authored-by: Andrés Yagüe López (https://github.com/AndresYague) 
                Affiliation: Los Alamos National Laboratory, Los Alamos, NM 87545, USA 
                ORCID: https://orcid.org/0000-0002-7294-9288

Co-authored-by: Benjámin Soós (https://github.com/bsos212)
                Affiliation: Konkoly Observatory, HUN-REN, Konkoly Thege Miklós út 15-17, Budapest, H-1121, Hungary.
                ORCID: https://orcid.org/0000-0002-2503-4181

## How to use

Simply run the script:

```sh
python3 SLRsVSmeanlife.py
```

This script plots the predicted and observed radioactive-to-stable abundance ratios in the early Solar System (ESS) divided by their stellar production ratios, against the respective mean life of the SLRs (for a more detailed description of the plot see Soós et al. 2025).

The `isotope_data.yaml` file contains all the necessary data for the code `SLRsVSmeanlife.py`, such as the name of the isotope, it's ESS abundance (with error bars), production ratio, mean life (with error bars), label specifics, and other information. 

## Installation and requirements

You need at least `Python 3.8`, the dependencies for the code can be installed with `pip`:

```sh
python3 -m pip install -r requirements.txt
```
README.md
README.md megjelenítése. 
