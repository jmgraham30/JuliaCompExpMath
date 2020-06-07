# Julia: A Tool for Computational and Experimental Mathematics?
Jason M. Graham

[GitHub](https://github.com/jmgraham30)

[Homepage](https://sites.google.com/site/jasonmgrahamus/)

## Obtaining Repository Contents

This repository contains material corresponding to a talk, "Julia: A Tool for Computational and Experimental Mathematics?" given
as part of the 2020 REU [Research Challenges of Computational and Experimental Mathematics](https://www.moravian.edu/mathematics/reu).

To access and use the material in this repo you will need to install Julia and Jupyter notebooks. [This video](https://www.youtube.com/watch?v=oyx8M1yoboY) explains how to get up and running with Julia and Jupyter. Alternatively, you can access Julia and Jupyter notebooks through the cloud via [JuliaBox](https://juliabox.com/).

In order to obtain the material in this repository, you may either

1) clone the repository (you will need [git](https://git-scm.com/) for this) by entering the following command in your terminal (after changing to the directory where you want to store the files from this repo as a sub-directory)

`git clone https://github.com/jmgraham30/JuliaCompExpMath.git`

This will create a new directory called JuliaCompExpMath that contains all of the files from this repo.

2)  Select the green "Clone or download" icon [here](https://github.com/jmgraham30/JuliaCompExpMath) then choose "Download ZIP", then unzip this repo on your computer.

If you are working in JuliaBox you should be able to add this repo by selecting the git icon and then entering the url `https://github.com/jmgraham30/JuliaCompExpMath.git`.

Once you have obtained Julia, Jupyter, and the files from this repository you can easily install all of the necessary dependencies by doing one of the following:

1) In the Julia REPL, enter the package manager by typing `]` you should see a command prompt that looks like

`pkg>`

run the following:

`activate .`

(for this to work correctly you will need to set your working directory to the JuliaCompExpMath folder)

`instantiate`

This should install all of the packages used in the notebooks from this repository.

2) In a Jupyter notebook run the following:

using Pkg
Pkg.activate(".")
Pkg.instantiate()

(for this to work correctly you will need to set your working directory to the JuliaCompExpMath folder)

This should install all of the packages used in the notebooks from this repository.

If you want to install individual packages in Julia, see the [package manager documentation](https://docs.julialang.org/en/v1/stdlib/Pkg/index.html).

## Description of Contents Relevant for the Talk

1) REU Talk slides - REUtalk.ipynb
2) Notebook on modeling with differential equations in Julia - ModelingDifferentialEquations.ipynb
3) Notebook on modeling probability and randomness - ModelingProbability.ipynb
4) Notebook on sybolic algebra - JuliaAlgebra.ipynb

## Some Useful Links

1) [Julia](https://julialang.org/)
2) [JuliaBox](https://juliabox.com/)
3) [Atom](https://atom.io/)
4) [Juno](https://junolab.org/)
5) [Jupyter](https://jupyter.org/)
6) [Weave](https://github.com/JunoLab/Weave.jl)
7) Packages
    1) [JuliaHub](https://juliahub.com/ui/Home)
    2) [JuliaPackages](https://juliapackages.com/)
