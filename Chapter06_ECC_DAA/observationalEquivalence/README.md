DIFF: TAMARIN from Chapter 6 ECC DAA
====================================

This is the README for the Tamarin files associated with my
thesis in chapter 6. using Observational Equivalence.

Additionally, we have stored the proved model in the `../analysed/ObservationalEquiv` folder.

Running Tamarin on the model
----------------------------

To run the verification on the model from within this folder it in the GUI mode and run the proofs:
```bash
$ tamarin-prover interactive . --diff --heuristic=o --oraclename=ISOIEC_20008_2013_2_ECC_DAA.unlinkability.oracle
```
and then point your browser to [http://localhost:3001/](http://localhost:3001/). There are a number of cases that will not autoprove using our oracle, and
these can be seen in the partial proof file `../analysed/ObservationalEquiv/ISOIEC_20008_2013_2_ECC_DAA.unlinkability.partial.spthy`. The partial proof then needs to be downloaded, and then run using Tamarin's defaults by entering the following command in the folder where the partial proof is stored:
```bash
$ tamarin-prover interactive . --diff 
```
