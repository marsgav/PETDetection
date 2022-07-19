# PETDetection
This is the accompanying code for Searching for PETs: An Analysis on Using Distributional and Sentiment-Based Methods to Find Potentially Euphemistic Terms.

# How to download the code
To download the code, there are two options:
- Using `git clone` may be the most straightforward. The word2vec models used are over the Github size limit (~3GB combined), so I used Git LFS (Large File Storage) to upload them. This means that if you just download the repository as a .zip file, some of the files will only be pointers to where they're stored on the Git cloud storage. On the other hand, using `git clone` seems to automatically download the files from the cloud storage during the cloning process.
- If `git clone` doesn't work for you, the files can also be found [here](https://drive.google.com/drive/folders/1g8vvBNlInExIxd0bbULMVvUiyT9PYlyZ?usp=sharing). Unzip them into the `data` file, and it should work.

# How to use the code
There are two notebooks. `Single_Sentence_Euph_Detection.ipynb` is the one which is intended for users to try. To use it, run the first 3 chunks, and then use the fourth chunk to test out your input text. Note that there are some required packages, which I note (along with these instructions) in the notebook. 

The other notebook, `Euph_Detection_6-11.ipynb`, is the one used to generate the results shown in the paper, and is mostly for reference.

# Feedback
Please let us know if anything doesn't work for you. If it's needed, the code will be continuously updated to improve performance/ease of use.
