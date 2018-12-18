TAMARIN models
==============

This is the README for the Tamarin files associated with my
thesis "Formal Analysis and Applications of Direct Anonymous
Attestation".

Tamarin Installation
--------------------

To run these files, you will need the Tamarin Prover tool installed,
git hash `44d5ecbc2097ee99a22a01876e445047f2a31c54` or later, and
its dependencies.

Please follow the [instructions within the Tamarin Manual (link)](https://tamarin-prover.github.io/manual/book/002_installation.html).


Running Tamarin on the models
-----------------------------

To run the verification on the models navigate to the folder containing
the TAMARIN models (*.spthy):

* Load the models in the GUI mode and run the proofs yourself.
```bash
$ tamarin-prover interactive .
```
and then point your browser to [http://localhost:3001/](http://localhost:3001/).

* To run the autoprover from the terminal without loading the GUI. Note,
  this will need to be done for each model. Run the following command
```bash
$ tamarin-prover --prove ./path/to/model.spthy
```
