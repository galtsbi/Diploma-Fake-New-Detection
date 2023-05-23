# Обнаружение фейковых новостей с использованием методов машинного обучения

В данном репозитории располагаются ipynb файлы с кодом проведенного исследования по обнаружению фейковых новостей с использованием алгоритмов машиного обучения.
Обучение моделей производилось на сборном датасете NewsAggregator+KaggleFN, тестирование - на Fake and real news dataset.

В папке "ML Algorithms" располагаются файлы с кодом применения алгоритмов машинного обучения в задаче детектирования фейковых новостей, а также строятся ROC кривых обучения.
В папке "Deep Learning Algorithms" располагаются файлы с кодом алгоритмов глубокого обучения, таких как LSTM, BiLSTM и модификации архитектуры BERT.
- В файле "LSTM + BiLSTM" рассматриваются одноименные архитектуры, а также строятся ROC кривые обучения моделей.
- В файлах "BERT", "DistilBERT", "RoBERTa", "ALBERT" рассматриваются одноименные архитектуры, а также строятся ROC кривые обучения.
- В файле "ROC BERT" на общем графике строятся ROC кривые обучения моделей BERT, DistilBERT, RoBERTa, ALBERT (для тонкой настройки и обучения только классификатора).
