<p align="center">
  <a href="https://careamics.github.io/">
    <img src="https://github.com/CAREamics/.github/blob/main/profile/images/banner_careamics.png">
  </a>
</p>


## CAREamics

CAREamics is a PyTorch library aimed at simplifying the use of Noise2Void and its many variants and cousins (CARE, Noise2Noise, N2V2, P(P)N2V, HDN, muSplit etc.).

### Why CAREamics?

Noise2Void is a widely used denoising algorithm, and is readily available from the n2v python package. However, n2v is based on TensorFlow and Keras, and our more recent methods (PPN2V, DivNoising, HDN) are all implemented in PyTorch, but are lacking the extra features that would make them usable by the community.

The aim of CAREamics is to provide a PyTorch library reuniting all the latest methods in one package, while providing a simple and consistent API. The library relies on PyTorch Lightning as a back-end. In addition, we will provide extensive documentation and tutorials on how to best apply these methods in a scientific context.

- [CAREamics source code](https://github.com/CAREamics/careamics)
- [CAREamics documentation](https://github.com/CAREamics/careamics.github.io): published online [here](https://careamics.github.io/)
- [CAREamics Examples](https://github.com/CAREamics/careamics-examples): code snippets used in the documentation and application examples
- [CAREamics Portfolio](https://github.com/CAREamics/careamics-portfolio): a simple Python package to download AI-ready datasets used by CAREamics
