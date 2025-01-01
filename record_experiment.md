## poli

### roberta

python run_self_training_experiment.py --experiment_name poli_roberta --dataset_name poli --base_model roberta-large-mnli

### narsil

python run_self_training_experiment.py --experiment_name poli_narsil --dataset_name poli --base_model Narsil/deberta-large-mnli-zero-cls

### facebook

python run_self_training_experiment.py --experiment_name poli_facebook --dataset_name poli --base_model facebook/bart-large-mnli

<!--
## feed

### roberta

python run_self_training_experiment.py --experiment_name feed_roberta_iter100 --dataset_name feed --base_model roberta-large-mnli --seed 0

### feed

python run_self_training_experiment.py --experiment_name feed_narsil_iter100 --dataset_name feed --base_model Narsil/deberta-large-mnli-zero-cls --seed 0

### facebook

python run_self_training_experiment.py --experiment_name feed_facebook_iter100 --dataset_name feed --base_model facebook/bart-large-mnli --seed 0

## fakeNews

(这个数据集太大了 ww 不要了算了)

### roberta

python run_self_training_experiment.py --experiment_name fakeNews_roberta_iter100 --dataset_name fakeNews --base_model roberta-large-mnli --seed 0

### feed

python run_self_training_experiment.py --experiment_name fakeNews_narsil_iter100 --dataset_name fakeNews --base_model Narsil/deberta-large-mnli-zero-cls --seed 0

### facebook

python run_self_training_experiment.py --experiment_name fakeNews_facebook_iter100 --dataset_name fakeNews --base_model facebook/bart-large-mnli --seed 0 -->

## fakeNews2

https://www.kaggle.com/datasets/iamrahulthorat/fakenews-csv

### roberta

python run_self_training_experiment.py --experiment_name fakeNews2_roberta --dataset_name fakeNews2 --base_model roberta-large-mnli

### narsil

python run_self_training_experiment.py --experiment_name fakeNews2_narsil --dataset_name fakeNews2 --base_model Narsil/deberta-large-mnli-zero-cls

### facebook

python run_self_training_experiment.py --experiment_name fakeNews2_facebook --dataset_name fakeNews2 --base_model facebook/bart-large-mnli

## fakeNews3

https://www.kaggle.com/datasets/ibrahimkaratas/fakenews/data

### roberta

python run_self_training_experiment.py --experiment_name fakeNews3_roberta --dataset_name fakeNews3 --base_model roberta-large-mnli

### narsil

python run_self_training_experiment.py --experiment_name fakeNews3_narsil --dataset_name fakeNews3 --base_model Narsil/deberta-large-mnli-zero-cls

### facebook

python run_self_training_experiment.py --experiment_name fakeNews3_facebook --dataset_name fakeNews3 --base_model facebook/bart-large-mnli

## fakeNews4

https://www.kaggle.com/datasets/vishakhdapat/fake-news-detection

### roberta

python run_self_training_experiment.py --experiment_name fakeNews4_roberta --dataset_name fakeNews4 --base_model roberta-large-mnli

### narsil

python run_self_training_experiment.py --experiment_name fakeNews4_narsil --dataset_name fakeNews4 --base_model Narsil/deberta-large-mnli-zero-cls

### facebook

python run_self_training_experiment.py --experiment_name fakeNews4_facebook --dataset_name fakeNews4 --base_model facebook/bart-large-mnli

# Model

## MoritzLaurer/deberta-v3-base-zeroshot-v1.1-all-33

https://huggingface.co/MoritzLaurer/deberta-v3-base-zeroshot-v1.1-all-33

- isear

python run_self_training_experiment.py --experiment_name isear_mor1 --dataset_name isear --base_model MoritzLaurer/deberta-v3-base-zeroshot-v1.1-all-33

- 20_newsgroup

python run_self_training_experiment.py --experiment_name 20_newsgroup_mor1 --dataset_name 20_newsgroup --base_model MoritzLaurer/deberta-v3-base-zeroshot-v1.1-all-33

- poli

python run_self_training_experiment.py --experiment_name poli_mor1 --dataset_name poli --base_model MoritzLaurer/deberta-v3-base-zeroshot-v1.1-all-33

## MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli

https://huggingface.co/MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli

- isear

  python run_self_training_experiment.py --experiment_name isear_mor2 --dataset_name isear --base_model MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli

-

## typeform/distilbert-base-uncased-mnli

https://huggingface.co/typeform/distilbert-base-uncased-mnli#how-to-get-started-with-the-model

- isear

python run_self_training_experiment.py --experiment_name isear_mor3 --dataset_name isear --base_model typeform/distilbert-base-uncased-mnli
