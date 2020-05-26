# impossibility-global-convergence
Accompanying code for the paper: *On the Impossibility of Global Convergence in Multi-Loss Optimization*. Implements a number of multi-loss optimization methods that are shown to enter limit cycles instead of converging, for almost-all initialisations, even in a zero-sum game. This includes GD, [EG](https://arxiv.org/pdf/1906.05945.pdf), [OMD](https://arxiv.org/pdf/1711.00141.pdf), [CO](https://arxiv.org/pdf/1705.10461.pdf), [SGA](https://arxiv.org/pdf/1802.05642.pdf), [LA](https://openreview.net/pdf?id=SyGjjsC5tQ), [LOLA](https://arxiv.org/pdf/1709.04326.pdf), [SOS](https://openreview.net/pdf?id=SyGjjsC5tQ), [CGD](https://arxiv.org/pdf/1905.12103.pdf) and [LSS](https://arxiv.org/pdf/1901.00838.pdf).

The notebook runs in ~2 minutes in colab (without GPU accelerator). Use this link to open directly: https://colab.research.google.com/github/aletcher/impossibility-global-convergence/blob/master/impossibility_global_convergence.ipynb

Please find the bibtex citation for each algorithm in the bibtex.md file.
