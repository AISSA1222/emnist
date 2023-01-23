# emnist
The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19  and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset . Further information on the dataset contents and conversion process can be found in the paper available at https://arxiv.org/abs/1702.05373v1.


Dataset Summary
There are six different splits provided in this dataset. A short summary of the dataset is provided below:

EMNIST ByClass: 814,255 characters. 62 unbalanced classes.
EMNIST ByMerge: 814,255 characters. 47 unbalanced classes.
EMNIST Balanced:  131,600 characters. 47 balanced classes.
EMNIST Letters: 145,600 characters. 26 balanced classes.
EMNIST Digits: 280,000 characters. 10 balanced classes.
EMNIST MNIST: 70,000 characters. 10 balanced classes.
The full complement of the NIST Special Database 19 is available in the ByClass and ByMerge splits. The EMNIST Balanced dataset contains a set of characters with an equal number of samples per class. The EMNIST Letters dataset merges a balanced set of the uppercase and lowercase letters into a single 26-class task. The EMNIST Digits and EMNIST MNIST dataset provide balanced handwritten digit datasets directly compatible with the original MNIST dataset.
