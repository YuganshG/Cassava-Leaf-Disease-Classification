# COMP-6771: Image Processing - Project

## Cassava Leaf Disease Classification

Cassava is a crucial crop for ensuring food security in Africa, as it is a significant source of carbohydrates that can thrive in harsh environmental conditions. Smallholder farmers cultivate cassava due to its resilience, and it is grown in at least 80% of household farms in Sub-Saharan Africa. Despite its popularity, viral diseases remain a major challenge that leads to poor yields. This study aims to evaluate the effectiveness of Convolutional Neural Networks (CNNs) in identifying prevalent diseases in cassava leaves and providing timely treatment. Two pre-trained models ResNet-50 and VGG-16 were used for transfer learning and to assess the benefits of transfer learning in this application domain, a network was developed from scratch as a performance measure. The performance of the three models was compared using various evaluation metrics, and a comprehensive report was produced to summarize the results.

### Directory Structure

<pre>
├── data/                       <- Top directory for project data files
│  ├── input/                   <- Dataset used in the project
│  ├── output/                  <- All project outputs
├── notebooks/                  <- Jupyter notebooks of the project
├── LICENSE                     <- Project's License
├── README.md                   <- The top-level README for the project
</pre>

### Usage Instructions

1. Place the dataset in the ./data/input folder
2. Update the following variables in the notebook:
   <pre> path = "../data/input"
   outpath = "../data/output" </pre>
3. Run the notebook in ./notebooks
4. Trained models can be accessed in the root directory.
