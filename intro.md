# An introduction to causal inference for electricity markets

This **work in progress** book contains tutorials on causal inference methodologies, explaining key concepts in this rapidly growing research area and showcasing potential applications within the electricity markets. It is currently divided into four parts:

1. **Causal Discovery**: the process of identifying causal relationships from data. This involves uncovering the underlying causal structure without assuming prior knowledge of the direction or nature of causality. It typically uses statistical and computational methods to determine which variables influence which other variables.
   
2. **Causal Inference**: the process of estimating the strength and nature of causal relationships that have been identified. It involves using statistical techniques to quantify the effect of one variable on another, given the causal structure is known or assumed.
   
3. **Interpretability**: the ability to understand and explain how a model makes its predictions or decisions. It involves techniques that provide insights into the importance of different features, the effect of individual variables, and the overall behaviour of the model.
   
4. **Designs**: the structured and methodical approach to planning, conducting, analysing, and interpreting controlled experiments. It involves techniques for setting up experiments to ensure that the results are valid, reliable, and can be used to draw causal conclusions.


```{admonition} Note
:class: note

The examples are provided in **Python**. Each chapter can be downloaded as a **Jupyter Notebook**, allowing you to run the examples and reproduce the results.
```


```{admonition} References
:class: tip

This book is highly applied, aimed at providing essential intuitions and practical examples on applying causal inference methods to real-world problems. We currently focus primarily on semi-parametric approaches, inspired by the methodologies presented in [Statistical Causal Discovery: LiNGAM Approach](https://link.springer.com/book/10.1007/978-4-431-55784-5). Many examples are implemented using the LiNGAM Python package {cite}`ikeuchi2023python`.

For additional theoretical and technical explanations, we suggest:
- [Causality: Models, Reasoning and Inference](https://dl.acm.org/doi/book/10.5555/1642718)
- [Elements of Causal Inference](https://mitpress.mit.edu/9780262037310/elements-of-causal-inference/)
- [Introduction to Causal Inference from a Machine Learning Perspective](https://www.bradyneal.com/causal-inference-course)

```


```{admonition} $~$
Built with [Jupyter Book
2.0](https://beta.jupyterbook.org/intro.html) tool set, as part of the
[ExecutableBookProject](https://ebp.jupyterbook.org/en/latest/).  
```

If you have any inquiries, please contact [d.cacciarelli@imperial.ac.uk](d.cacciarelli@imperial.ac.uk).
