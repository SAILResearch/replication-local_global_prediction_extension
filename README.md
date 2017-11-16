# Replication Package for "Towards Improving Statistical Modelling of Software Engineering Data: Think Locally, Act Globally!"

Nicolas Bettenburg, Meiyappan Nagappan, Ahmed E. Hassan  
[Empirical Software Engineering Journal, vol. 20, issue 2, 2015](https://doi.org/10.1007/s10664-013-9292-6)

Abstract: Much research energy in software engineering is focused on the creation of effort and defect models. Such models are important means for practitioners to judge their current project situation, optimize the allocation of their resources, and make informed future decisions. However, software engineering data contains a large amount of variability. Recent research demonstrates that such variability leads to poor fits of machine learning models to the underlying data, and suggests splitting datasets into more fine-grained subsets with similar properties. In this paper, we present a comparison of three approaches for creating statistical models for software defects and development effort. Global models are trained on the whole dataset. In contrast, local models are trained on subsets of the dataset. Last, we build a global model that takes into account local characteristics of the data. We evaluate the performance of these three modelling approaches on several datasets and find that local modelling leads to a considerably improved fit to the data compared to global models. We further demonstrate substantial improvements of local modelling over global modelling with respect to prediction performance. Such improvements are due to learning from homogeneous local sub regions of the data, and not due to over-fitting. Furthermore, we find that for the clustering algorithms used to build local models, careful calibration of their parameters, as well as the data itself, are important factors in the success of local modelling. Finally, our experiments suggest that for practical considerations, a hybrid approach such as global models with local considerations combines the benefits of local modelling with the simplicity of global modelling. 

## Bibtex

```bibtex
@Article{Bettenburg2015,
author="Bettenburg, Nicolas
and Nagappan, Meiyappan
and Hassan, Ahmed E.",
title="Towards improving statistical modeling of software engineering data: think locally, act globally!",
journal="Empirical Software Engineering",
year="2015",
month="Apr",
day="01",
volume="20",
number="2",
pages="294--335",
issn="1573-7616",
doi="10.1007/s10664-013-9292-6",
url="https://doi.org/10.1007/s10664-013-9292-6"
}
```

## Data and Scripts
You can download all data and R scripts used for this study [here](https://github.com/SAILResearch/replication-local_global_prediction_extension/releases/latest)
