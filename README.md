Two examples optimising an SVM using Mind Foundry's [Optimiser-as-a-Service](https://mindfoundry.ai/optaas/) (OPTaaS)

# Manual Parameter Optimisation: optaas-svm-manual.py

Optimises an SVM using OPTaaS naively - this is the way I implemented before I learned about the inbuilt methods in OPTaaS to do this with a lot less code. However, the benefit of this method is that it could apply to non-sklearn classifiers.

# Automatic Pipeline Optimisation: optaas-svm-inbuilt.py

Optimises an SVM on an sklearn pipeline using in-built OPTaaS functionality - far less code!
