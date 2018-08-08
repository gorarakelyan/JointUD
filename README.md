# JointUD
### Multitask neural model for Part-of-Speech tagging, Morphological parsing and Lemmatization
### Implemented in Keras 2.1.5

## Usage
### Training
```
usage: train.py [-h] [--model_name MODEL_NAME] [--nb_epochs NB_EPOCHS]
                [--early_stopping EARLY_STOPPING] [--batch_size BATCH_SIZE]
                [--optimizer OPTIMIZER] [--classifier CLASSIFIER]
                [--loss LOSS] [--dump_prefix DUMP_PREFIX] [--lstm LSTM]
                [--lstm_size LSTM_SIZE] [--dropout DROPOUT]

optional arguments:
  -h, --help            show this help message and exit
  --model_name MODEL_NAME
                        Model name
  --nb_epochs NB_EPOCHS
                        Number of Epochs
  --early_stopping EARLY_STOPPING
                        Early Stopping
  --batch_size BATCH_SIZE
                        Batch Size
  --optimizer OPTIMIZER
                        Optimizer
  --classifier CLASSIFIER
                        Classifier
  --loss LOSS           Loss
  --dump_prefix DUMP_PREFIX
                        Model dump name prefix
  --lstm LSTM
  --lstm_size LSTM_SIZE
  --dropout DROPOUT
```

### Parsing
```
usage: parse.py [-h] [--model_path MODEL_PATH] [--mapping_path MAPPING_PATH]
                [--input_path INPUT_PATH] [--output_path OUTPUT_PATH]

optional arguments:
  -h, --help            show this help message and exit
  --model_path MODEL_PATH
                        Model path
  --mapping_path MAPPING_PATH
                        Mapping path
  --input_path INPUT_PATH
                        Input path
  --output_path OUTPUT_PATH
                        Output path
```