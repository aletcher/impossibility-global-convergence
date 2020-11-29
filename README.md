# impossibility-global-convergence
Accompanying code for the paper: [On the Impossibility of Global Convergence in Differentiable Games](https://arxiv.org/pdf/2005.12649.pdf). Implements a number of multi-loss optimization methods that are shown to enter limit cycles instead of converging in a two-parameter zero-sum game, *despite* being weakly-coercive, analytic and nondegenerate. This includes (simultaneous) GD, [AGD](https://arxiv.org/pdf/1907.04392.pdf), [EG](https://arxiv.org/pdf/1906.05945.pdf), [OMD](https://arxiv.org/pdf/1711.00141.pdf), [CO](https://arxiv.org/pdf/1705.10461.pdf), [SGA](https://arxiv.org/pdf/1802.05642.pdf), [LA](https://openreview.net/pdf?id=SyGjjsC5tQ), [LOLA](https://arxiv.org/pdf/1709.04326.pdf), [SOS](https://openreview.net/pdf?id=SyGjjsC5tQ), and [CGD](https://arxiv.org/pdf/1905.12103.pdf).

This undesirable phenomenom is shown to apply more generally to *any* 'reasonable' algorithm in the paper, ruling out the possibility of global convergence guarantees in multi-loss optimization.

The notebook runs in ~2 minutes (without GPU accelerator). Use this link to open directly: https://colab.research.google.com/github/aletcher/impossibility-global-convergence/blob/master/impossibility_global_convergence.ipynb

Please find the bibtex citation for each algorithm in the bibtex.md file.
