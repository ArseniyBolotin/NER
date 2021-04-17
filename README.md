# NER
Information extraction from unstructured documents

Google drive : https://drive.google.com/drive/folders/1zQpn149rHb-87AbmahSo9amlcCwq-Z53


Считывание в pandas.DataFrame из файлов
```
train = pd.read_csv('NER_PAD_agg_train.csv', converters={'tokens': eval, 'ner_tags': eval})
test = pd.read_csv('NER_PAD_agg_test.csv', converters={'tokens': eval, 'ner_tags': eval})
```
