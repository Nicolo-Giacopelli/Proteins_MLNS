# Protein classification and generation

This project draws its interest in bioinformatics and the innovations brought by the AI revolution in what concerns the
study of the primary sources of Life. In particular, our objective has been to predict protein structures’ enzymatic functions starting from their graph representation, before trying to
design graph structural approximations of enzymes through the use of generative models. </br> </br> Indeed, function prediction and function design are both considered as key tasks in the domain
of protein engineering and are at the core of several real life applications such as drug discovery, gene editing, and antibodies
therapeutics. In that regard, 2 graph classification and 1 graph generation tasks were performed on the PROTEINS and ENZYMES datasets and a total of 7 graph Neural Network models
were designed and compared in the process. The generated proteins were then evaluated using the best performing classifier
to assess the quality of the developed generation process.

## Main files
```*.ipynb```: notebooks addressing the different tasks, either classification on both datasets or generation only on PROTEINS, using Generative Adversarial networks for Graph generation 
as well as Variational Autoencoder models

```*.ipynb```: files containing the definitions of the functions and the models called in the different notebooks

```report.pdf```: written report containing the results and full explanation of the procedure followed

```models```: folder containing checkpoints of the best models


