TAMARIN Models from Chapter 4
=============================

This is the README for the Tamarin files associated with my thesis
Chapter 4. Additionally, we have stored the proved models in the `analysed`
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
$ tamarin-prover --prove ./REWIRE_plain.spthy
```

* To load and run the proved models see the README in the `analysed` folder. 
