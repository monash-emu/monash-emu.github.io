# Monash-EMU
A collection of resources for the software packages produced by the [Monash Epidemiological Modelling Unit](https://www.monash.edu/medicine/sphpm/units/epidemiological-modelling).

## Software Packages

### Summer

Summer is a package for simple and expressive development of  [compartmental](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)
timeseries ODE models of infectious diseases.<br>
It uses [jax](https://jax.readthedocs.io) to compile these models to fast optimized code.

- [Code](https://github.com/monash-emu/summer2)
- [Documentation](https://summer2.readthedocs.io/) 
- [Pypi Package](https://pypi.org/project/summerepi2/) 

### Estival

Estival is a Bayesian modelling package for summer, allowing convenient expression of observations/likelihoods/priors.<br>
It includes tight integration with tools like [PyMC](https://www.pymc.io/) and [nevergrad](https://facebookresearch.github.io/nevergrad/)

- [Code](https://github.com/monash-emu/estival)
- [Pypi Package](https://pypi.org/project/estival/)

## Epidemiological applications

### Textbook

A summer based textbook of infectious disease modelling
- [Link](https://github.com/monash-emu/summer-textbook)

### Output validation

Reproduction of the [Vynnycky & White](https://anintroductiontoinfectiousdiseasemodelling.com/) models using summer
- [Link](https://github.com/monash-emu/summer-vynnycky-white-validation)

## Publications

A few selected publications using summer:
- [Understanding how Victoria, Australia gained control of its second COVID-19 wave](https://doi.org/10.1038/s41467-021-26558-4). Trauer JM, Lydeamore MJ, Dalton GW, Pilcher D, Meehan MT, McBryde ES, Cheng AC, Sutton B, Ragonnet R. *Nature Communications* 2021.
- [Estimating the long-term effects of mass screening for latent and active tuberculosis in the Marshall Islands](https://academic.oup.com/ije/article/51/5/1433/6552193?login=false). Ragonnet R, Williams BM, Largen A, Nasa J, Jack T, Langinlur MK, Ko E, Rahevar K, Islam T, Denholm JT, Marais BJ, Marks GB, McBryde ES, Trauer JM. *International Journal of Epidemiology* 2022.
- [Understanding COVID-19 dynamics and the effects of interventions in the Philippines: A mathematical modelling study](https://doi.org/10.1016/j.lanwpc.2021.100211). Caldwell JM, de Lara-Tuprio E, Teng TR, Estuar MRJE, Sarmiento RFR, Abayawardana M, Leong RNF, Gray RT, Wood JG, Le LV, McBryde ES, Ragonnet R, Trauer JM. *Lancet Regional Health Western Pacific* 2021.
- [Sustaining effective COVID-19 control in Malaysia through large-scale vaccination](https://doi.org/10.1016/j.epidem.2021.100517). Jayasundara P, Peariasamy KM, Law KB, Abd Rahim KNK, Lee SW, Ghazali IMM, Abayawardana M, Le LV, Khalaf RKS, Razali K, Le X, Chong ZL, McBryde ES, Meehan MT, Caldwell JM, Ragonnet R, Trauer JM. *Epidemics* 2021.


See more publications from our team [here](https://www.monash.edu/medicine/sphpm/units/epidemiological-modelling/publications). 