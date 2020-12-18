## Examples


Besides the examples provided in the user guides for the usage of [models](./user_guide_models) 
and [quantifiers](./user_guide_quantifiers), the following Jupyter notebooks explain 
specific tasks:


- **Creating a Stochastic Model using the Sequential API**  
    This shows the simplest, and recommended, way to create an uncertainty aware DNN which
    is capable of calculating uncertainties and confidences based on point prediction approaches
    as well as on stochastic samples based approaches (e.g. MC-Dropout)
    
    [View Jupyter Notebook](https://nbviewer.jupyter.org/urls/xblind.web.app/jupyter/MnistStochasticSequential.ipynb)
    or [Download as Source](./../jupyter/MnistStochasticSequential.ipynb)
    
- **Convert a traditional keras Model into an uncertainty-aware model**  
    This shows how you can use any keras model you may have, which was not created through uncertainty wizard,
    into an uncertainty-aware DNN.
    
    [View Jupyter Notebook](https://nbviewer.jupyter.org/urls/xblind.web.app/jupyter/LoadStochasticFromKeras.ipynb)
    or [Download as Source](./../jupyter/LoadStochasticFromKeras.ipynb)
    
    
- **Create a lazily loaded and highly parallelizable Deep Ensemble**  
    This show the fastest way to create an even faster implementation of the powerful Deep Ensembles -
    in a way which respects the fact that your PC and your GPU are powerful and your time is costly.
    
    [View Jupyter Notebook](https://nbviewer.jupyter.org/urls/xblind.web.app/jupyter/MnistEnsemble.ipynb)
    or [Download as Source](./../jupyter/MnistEnsemble.ipynb)
    

More examples will be added when we get feedback from our first users about the steps they found non-obvious.
In the meantime, you may want to check out the [Complete API Documentation](./complete_api).