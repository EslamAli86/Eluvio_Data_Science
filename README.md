# This repository is my solution to the Elovio Data Science challenge

### In this repository, I apply LDA, one of the Topic Modeling models, on the given dataset 'Eluvio_DS_Challenge.csv' to discover topics related to some given entities. For example, I extract from the dataset all records related to 'Middle East' as an entity using a list of related keywords `['egypt', 'palestine', 'israel', 'iraq', 'iran', 'arab', 'saudi', 'gaza', 'turk']`.
### Then I train different LDA models on the extracted dataset and discover possible topics embedded within it. During the training process, I fine-tune the <span style="color:blue">`num_topics`</span> hyperparameter

### The notebook `Topic_Modeling.ipynb` explains all the steps performed starting from cleaning and preprocessing the data, till visualizing the discovered topics and drawing conclusions.

### `Topic_Modeling.html` is the html format of the notebook. I would recommend reading this file if you are having problem running the `Topic_Modeling.ipynb` notebook. Also, `Topic_Modeling.pdf` is a pdf compilation of `Topic_Modeling.ipynb`.
