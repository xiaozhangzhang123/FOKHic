# FOKHic
FOKHic is a framework of k-mer based hierarchical classification.<br>
## Description<br>
FOKHic is a powerful framework for virus sequence classification using a k-mer frequency based machine learning method. By combining  principal component analysis, feature fusion and Bayesian optimization, FOKHic is able to accomplish rapid classification of metagenomic viral sequences. 

## Usage
The usage of FOKHic is:<br>
``` cd bin
./FOKHic -f <input fasta file> -o <output_directory> -k <the length of k-mer> -db <run BLAST with provided database> -m <the directoty of best model>
```
## Retraining model
The trained model may have different effects in different databases. You can use the provided model_training retrains the model with custom data. To use the retrained classifier, replace the model path in FOKHic.
The usage of model_training is:<br>
``` 
./model_training -k <the length of k-mer> -o <output_directory> -t <data used for training model>
```
## Contack Information
If you have any questions or concerns, please feel free to contact zystudy2022@outlook.com
