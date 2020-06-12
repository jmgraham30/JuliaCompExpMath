# Julia: A Tool for Computational and Experimental Mathematics?
Jason M. Graham

[GitHub](https://github.com/jmgraham30)

[Homepage](https://sites.google.com/site/jasonmgrahamus/)

## Obtaining Repository Contents

This repository contains material (a detailed decscription of contents follows) corresponding to a talk, "Julia: A Tool for Computational and Experimental Mathematics?" given
as part of the 2020 REU [Research Challenges of Computational and Experimental Mathematics](https://www.moravian.edu/mathematics/reu).

To access and use the material in this repo you will need access to Julia and an ability to run Jupyter notebooks. [This video](https://www.youtube.com/watch?v=oyx8M1yoboY) demonstrates one way to get up and running with Julia and Jupyter. You can also install [Julia Pro](https://juliacomputing.com/products/juliapro), [this video](https://www.youtube.com/watch?v=ei-xnVid3QY&t=15s) explains how to do this. Alternatively, you can access Julia and Jupyter notebooks through the cloud via [JuliaBox](https://juliabox.com/).

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

1) REU Talk slides - [REUtalk.ipynb](https://github.com/jmgraham30/JuliaCompExpMath/blob/master/REUtalk.ipynb)
2) Notebook on modeling with differential equations in Julia - [ModelingDifferentialEquations.ipynb](https://github.com/jmgraham30/JuliaCompExpMath/blob/master/ModelingDifferentialEquations.ipynb)
3) Notebook on modeling probability and randomness - [ModelingProbability.ipynb](https://github.com/jmgraham30/JuliaCompExpMath/blob/master/ModelingProbability.ipynb)
4) Notebook on symbolic algebra - [JuliaAlgebra.ipynb](https://github.com/jmgraham30/JuliaCompExpMath/blob/master/JuliaAlgebra.ipynb)
5) Notebook [BasicNumberTheory.ipynb](https://github.com/jmgraham30/JuliaCompExpMath/blob/master/BasicNumberTheory.ipynb) that illustrates usage of [BasicNT.jl](https://github.com/jmgraham30/BasicNT.jl).

## Some Useful Links

1) [Julia](https://julialang.org/) for the Julia Language site.
2) [JuliaBox](https://juliabox.com/) for running Julia via the cloud.
3) [Atom](https://atom.io/) an open source IDE that supports Julia.
4) [Juno](https://junolab.org/) an package for Atom that sets up an IDE for Julia.
5) [Jupyter](https://jupyter.org/) notebook environment for interactive computing.
6) [JuliaPro](https://juliacomputing.com/products/juliapro) provides a Julia installation that comes with many packages including Jupyter notebooks preinstalled.
7) [Weave](https://github.com/JunoLab/Weave.jl) package for the integration of code and documentation. 
8) Helpful lists of Julia packages:
    1) [JuliaHub](https://juliahub.com/ui/Home)
    2) [JuliaPackages](https://juliapackages.com/)
