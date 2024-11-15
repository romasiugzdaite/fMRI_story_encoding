# fMRI_story_encoding

Chidren passivle listening to stories in MRI scanner.
Several language related features were encoded. 

## Fitting Models

The basic functionality for fitting encoding models can be found the script encoding.py, which takes a series of arguments such as subject id, feature space to use, list of training stimuli, etc. It will automatically use the preprocessed data from the location that get_data saves the data to.

To fit a semantic encoding model (dutch1000) for one subject (s001) and test it on held-out data:

$ python encoding/encoding.py --subject s001 --feature dutch1000


The python code was adapted from LeBel (2023) paper:
LeBel, A., Wagner, L., Jain, S. et al. A natural language fMRI dataset for voxelwise encoding models. Sci Data 10, 555 (2023). https://doi.org/10.1038/s41597-023-02437-z


