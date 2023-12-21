# Mathematical odeling of fluconazole resistance in the ergosterol pathway of *Candida albicans*
![badge][badge-jupyter]
![badge][badge-python]
![badge][badge-numpy]
![badge][badge-scipy]

## Abstract
Candidiasis is reported to be the most common fungal infection in the critical care setting. The causative agent of this infection is a commensal pathogen belonging to the genus *Candida*, the most common species of which is *Candida albicans*. The ergosterol pathway in yeast is a common target by many antifungal agents, as ergosterol is an essential component of the cell membrane. The current antifungal agent of choice for the treatment of candidiasis is fluconazole, which is classified under the azole antifungals. In recent years, the significant increase of fluconazole-resistant *C. albicans* in clinical samples has revealed the need for a search for other possible drug targets. In this study, we constructed a mathematical model of the ergosterol pathway of *C. albicans* using ordinary differential equations with mass action kinetics. From the model simulations, we found the following results: (i) a partial inhibition of the sterol-methyltransferase enzyme yields a fair amount of fluconazole resistance; (ii) the overexpression of the ERG6 gene, which leads to an increased sterol-methyltransferase enzyme, is a good target of antifungals as an adjunct to fluconazole; (iii) a partial inhibition of lanosterol yields a fair amount of fluconazole resistance; (iv) the C5-desaturase enzyme is not a good target of antifungals as an adjunct to fluconazole; (v) the C14α-demethylase enzyme is confirmed to be a good target of fluconazole; and (vi) the dose-dependent effect of fluconazole is confirmed. This study hopes to aid experimenters in narrowing down possible drug targets prior to costly and time-consuming experiments and serve as a cross-validation tool for experimental data.

## Citation
```
@article{yu2022mathematical,
  title={Mathematical Modeling of Fluconazole Resistance in the Ergosterol Pathway of Candida albicans},
  author={Yu, Paul K and Moron-Espiritu, Llewelyn S and Lao, Angelyn R},
  journal={Msystems},
  volume={7},
  number={6},
  pages={e00691--22},
  year={2022},
  publisher={Am Soc Microbiol}
}
```

## Environment
The source code is written in Python 3.7.14 using Google Colab (Oct. 4, 2022) in the Jupyter notebook environment with the following version:

Selected Jupyter core packages... <br>
IPython          : 7.9.0 <br>
ipykernel        : 5.3.4 <br>
ipywidgets       : 7.7.1 <br>
jupyter_client   : 6.1.12 <br>
jupyter_core     : 4.11.1 <br>
nbconvert        : 5.6.1 <br>
nbformat         : 5.4.0 <br>
notebook         : 5.3.1 <br>
traitlets        : 5.1.1

[badge-jupyter]: https://img.shields.io/badge/Jupyter-F37626.svg?&style=flat&logo=Jupyter&logoColor=white
[badge-python]: https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white
[badge-numpy]: https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white
[badge-scipy]: https://img.shields.io/badge/SciPy-654FF0?style=flat&logo=SciPy&logoColor=white
