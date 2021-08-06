# pyross-ifr-change
Code for the Bayesian inference of changes of Covid-19 using pyross

Supporting information for "Bayesian inference across multiple models suggests a strong increase in lethality of COVID-19 in late 2020 in the UK"
Patrick Pietzonka, Erik Brorson, William Bankes, Michael E. Cates, Robert L. Jack, Ronojoy Adhikari, medRxiv, https://doi.org/10.1101/2021.03.10.21253311

### Overview

This repository contains python code (jupyter notebook) for generation and processing of the results of medRxiv:2021.03.10.21253311. Results are obtained using the [PyRoss](https://github.com/rajeshrinet/pyross) library to analyse an epidemiological compartment model for COVID-19 in the UK.

Running the code requires `PyRoss`, see
<https://github.com/rajeshrinet/pyross>, or quick-install using
```bash
>> pip install -r requirements.txt
```

The notebook BC1.ipynb shows the setup and the results for the model variant BC1, which is one of the most detailed model variants. Other model variants follow by removing details.

(see medRxiv:2021.03.10.21253311 for definitions of terms.)
