# NER
Information extraction from unstructured documents

Агрегированные данные Google drive : https://drive.google.com/drive/folders/1zQpn149rHb-87AbmahSo9amlcCwq-Z53

Получить данные с Google drive в colab

## PAD
Full dataset
```
!gdown --id 1AnLqXtSyJNBK7YmwuW6L6z2OYhE4RPTV
```
Train
```
!gdown --id 1RFNBRcly96omdpNtYlEK6O1EuQs3ux7t
```
Test
```
!gdown --id 1cCXjHX9FAgouF0DWuWPO5qyBHVZDkXTQ
```

## RFQ
Full dataset
```
!gdown --id 1L6dd0FnYqgn-eoQ-gFnBiNji7R1ul9n_
```
Train
```
!gdown --id 1-5mE9XjocmyCKGlkpW1YGuCnNsGwQioD
```
Test
```
!gdown --id 1d4er4I7x4VIwy7BsWFpsPuC2z6aZ3P6s
```

Считывание в pandas.DataFrame из файлов

```
train = pd.read_csv('NER_PAD_agg_train.csv', converters={'tokens': eval, 'ner_tags': eval})
test = pd.read_csv('NER_PAD_agg_test.csv', converters={'tokens': eval, 'ner_tags': eval})
```

```
train = pd.read_csv('NER_RFQ_agg_train.csv', converters={'tokens': eval, 'ner_tags': eval})
test = pd.read_csv('NER_RFQ_agg_test.csv', converters={'tokens': eval, 'ner_tags': eval})
```