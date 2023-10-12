# Self-organization experiments in discrete approximations of complex continuous systems

Checkout [the project page](https://rivesunder.github.io/DisContinuous) for an outline of the project, links to code illustrating discretization effects on _Scutium gravidus_ and _Orbium_ Lenia gliders, and preliminary results (animations).

## Quick setup

This repo uses the [yuca](https://github.com/rivesunder/yuca) cellular automata simulator. 

To get started you can clone this repo and run `clone_install.sh` from within your virtual environment. This will install `yuca`. 

```
git clone https://github.com/riveSunder/DiscoGliders.git disco_gliders
cd disco_gliders

virtualenv disco_env --python=python3.8
source disco_env/bin/activate

sh clone_install.sh

# try and run yuca tests
python -m testing.test_all
```

For examples of gliders, check out the [glider gallery](gallery.md).

# Notebooks

Find notebooks for recreating Disco Gliders figures and introductions to each glider-supporting system in the `notebooks` folder.

# Experiments

Experiments can be replicated using the scripts in `scripts`
