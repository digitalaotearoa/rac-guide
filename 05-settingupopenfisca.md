---
layout: page
title: Setting up OpenFisca
navigation: 6
---

This content 

## Setting up and using Open Fisca

* What is OpenFisca Mauko
* How to setup OpenFisca Mauko
* Tutorials on committing rules to open fisca MaukoThree tutorials following and associated video walkthroughs
* What can you do with an operational OpenFisca instance?

We built this Rules as Code demonstrator to be easily deployed as a package, providing an exampple to play with as part of learning how to encode legislation or regulation in your own country. Anyone can create a coded interpretation of legislation or regulation, but your work to codify these rules in your jurisdictions would be greatly benefitted by having people with policy and legal backgrounds in your team if you can. This is because even plainly written rules can require interpretation. 

## Installing this Country Package (Aotearoa New Zealand)

Supported platforms:
- GNU/Linux distributions (in particular Debian and Ubuntu);
- Mac OS X;
- Microsoft Windows (we recommend using [ConEmu](https://conemu.github.io/) instead of the default console).

Other OS should work if they can execute Python and NumPy.

Pick option (A) or (B)

### A. Minimal Installation - for users running the rules

Follow this installation if you wish to:
  - run calculations on a large population;
  - run your own instance of OpenFisca-Aotearoa
  - run your own instance of the OpenFisca-Aotearoa rules package, as an OpenFisca Web API.
  - **not** modify the rules

There are 3 documented ways to do this - Pick your tech:
  * [Run in docker](SETUP-docker.md) to run on an instance or your laptop
  * [Setup pew and install from pip](SETUP-pew.md) to manage virtualenvs
  * [Run on heroku's PaaS cloud](https://heroku.com/deploy)

### B. Advanced Installation - for devs, modifying the rules and code

Follow this tutorial if you wish to change the OpenFisca-Aotearoa rules or contribute to the source code.

Read the [Setup OpenFisca Aotearoa in vscode with devcontainer](SETUP-devcontainer.md) instructions to setup a development environment in Visual Studio Code using the VSCode Development container approach.

Or

Read the [Setup Aotearoa Open Fisca in pyenv](SETUP-pyenv.md) instructions to manage python runtimes and eggs

`pyenv` is simular to rbenv/rvm (for ruby) and nvm (for nodejs).

## Next Steps

- To contribute to the code, read our [contribution doc](https://github.com/ServiceInnovationLab/openfisca-aotearoa/blob/master/CONTRIBUTING.md).
