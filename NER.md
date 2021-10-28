https://github.com/Erlemar/Erlemar.github.io/blob/master/Notebooks/ner_sberloga.ipynb

```python
!pip install deeppavlov > /dev/null
from deeppavlov import configs, build_model

ner_model = build_model(configs.ner.ner_ontonotes_bert_mult_torch, download=True)
ner_model(['Когда Курт Кобейн родился в США заяц хрюкнул'])
```
