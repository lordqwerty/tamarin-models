TAMARIN from Chapter 6 ECC DAA
==============================

This is the README for the Tamarin files associated with my
thesis in chapter 6.

Please see the sub-directory `observatonalEquivalence`
for the model with the `diff` terms which performs the observational
equivalence analysis.

Additionally, we have stored the proved models in the `analysed`
folder.

Running Tamarin on the models
-----------------------------

To run the verification on the models from within this folder you may:

* Load the models in the GUI mode and run the proofs yourself.
```bash
$ tamarin-prover interactive .
```
and then point your browser to [http://localhost:3001/](http://localhost:3001/).

* Run the autoprover from the terminal without loading the GUI. Note, this will need to be done for each model.
```bash
$ tamarin-prover --prove ./ISOIEC_20008_2013_2_ECC_DAA.spthy
```

* To load and run the observational equivalence model see the README in the `observationalEquivalence` folder.

* To load and run the proved models see the README in the `analysed` folder.
