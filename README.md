# simulations-tools
This projects aims to wrap all the necessary tools for parametric simulations using codes as Sixtrack and MAD-X.


## Get started
In order to work with the simulations-tools package, please clone the project in your own machine, using SSH:

```
git clone git@github.com:apoyet/simulations-tools.git
```

Please add a SSH publickey in your own machine (under ~/.ssh). You can use the command 

```
ssh-keygen -t rsa
```

and upload the key on your github profile. In the upper-right corner of any page, click your profile photo, then click Settings. In the user settings sidebar, click SSH and GPG keys and follow the instructions.

## A first example
In order to run your first example, please go first in the repo 'mask' and run the madx input file:
```
cd mask
madx<dummy_examples/first_example.madx
```
This example will call two sequences, corresponding to the two beams in the LHC (ATS Round Optics, 30 cm, 130 urad) and will install a wire on B2. See the effect on the tune. 

You can now play with the wire installation. 


## Contribution

Please do not hesiate to contribute to this toolkit, by commiting changes, opening issues, or contacting me at: 

axel.poyet@cern.ch


Thanks! 
