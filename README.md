# 121-UCI-Datasets and Text datasets Partitions

Use abalone dataset as an example: 
- abalone are the original samples
- labels are the classes for these samples
- folds represent the train-test partitions (4-folds. 0 means train, and 1 means test). 
- For the training set, we divide it into 4 equal parts. 3 for validation train, and 1 for validation test (4-folds. 0 means train, and 1 means test). So there are totally 4* 4=16 parts (rows) in validation_train and validation_test.

For some datasets that already have train and test parts. No need for 4-folds train-test partition. The validation_train and validation_test also shrink to 4 rows.

[Download](https://drive.google.com/file/d/1jbE6tlX23lOFibRaqqaJQhGOJGfyWQAb/view?usp=sharing)
[Download](https://drive.google.com/file/d/1HKCtkRfnSMEX9TzGthBLVgX0c6O5ky8M/view?usp=sharing)
