The state of the art in protein structure prediction (PSP) is currently achieved 
by complex deep learning pipelines that require several input features. In this paper, 
we demonstrate the relevance of Geometric Algebra (GA) for modelling protein features in PSP. 
We do so by proposing a novel GA metric based on the relative orientations of amino acid residues.
We then employ this metric as an additional input feature to a Graph Transformer (GT)
to aid the prediction of the 3D coordinates of a protein. Adding this GA-based 
orientational information improves the accuracy of the predicted coordinates 
even after few learning iterations and on a small dataset.


The notebook "Generating-Cost-Maps.ipynb" is used to generate cost maps per chain for each .pdb file in path
The notebook "Graph-Transformer.ipynb" defines the transformer, loads the PDNET dataset and adds cost maps to the features. Training and testing are then performed.
