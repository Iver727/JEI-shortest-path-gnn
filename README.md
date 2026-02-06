# JEI-shortest-path-gnn
A repository of the code used for submission to the Journal of Emerging Investigators for an article investigating the effect various changes to training data has on a message-passing and edge-feature-convolution GNN.

For each results notebook, every cell must be run in the order included.
The installations will cause dependency errors, requiring a restart to the runtime; this does not break functionality.

Notebook correspondence to results sub-headers:
 - "GINETrainingGraphSizeAtExact.ipynb": "Assessment of the Generalization of Networks Trained on Graphs of Specific Sizes"
 - "GINETrainingGraphSizeUpToMax.ipynb": "Assessment of the Generalization of Networks Trained on Graphs of Varying Sizes"
 - "GINETrainingAndTestingSpecificNodeRadius.ipynb": "Assessment of the Generalization of Networks Trained only on Nodes at a Specific Radius"

For the materials and methods section "Hyperparameter Choice," the notebook "HyperParamChoice.ipynb" has 3 different hyperparemeter searches. The code beforehand should be run, while the code in these searches should be run separately with separate file saving paths.
