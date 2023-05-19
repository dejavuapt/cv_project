
## Plant Disease Using Siamese Network - Keras
Оригинал - [click](https://www.kaggle.com/code/bulentsiyah/plant-disease-using-siamese-network-keras)

![](https://tyami.github.io/assets/images/post/DL/2020-10-20-siamese-neural-networks/2020-10-20-siamese-neural-networks-8-siamese-neural-network.png)

**_Сиамская нейронная сеть_** - это особый тип нейронной сети. Сначала мы обучаем изображение последовательности сверточных слоев, объединяя слои и полностью связанные слои, в итоге получаем вектор признаков f (x1). Затем мы обучаем другое изображение в той же последовательности, чтобы получить другой вектор признаков f(x2). Теперь мы вычисляем d, которое будет расстоянием между каждой из точек вектора признаков f (x1) и вектором признаков f(x2). Если d мало, мы можем сказать, что оба изображения одинаковы, в противном случае, если d велико, все наоборот.

Заявленная точность метода: 96.16% на тренировочном сете.

---

## Plant Disease Classification Using DenseNet121

Статья нейронки DenseNet121 - [click](https://arxiv.org/pdf/1608.06993.pdf)

Оригинал - [click](https://www.kaggle.com/code/shawon10/plant-disease-classification-using-densenet121)

![](https://imgur.com/wWHWbQt.jpg)

Представляется решение с помощью плонтой сверточной сети (DenseNet), которая соединяет каждый слой с любым другим слоем в режиме прямой связи. В то время как традиционные сверточные сети с L слоями имеют L соединений - по одному между каждым слоем и его последующим слоем - наша сеть имеет L(L+1)/2 прямых соединения. Для каждого слоя в качестве входных данных используются карты объектов всех предыдущих слоев, а его собственные карты объектов используются в качестве входных данных для всех последующих слоев. 

Итоговая точность метода:
![](https://www.kaggleusercontent.com/kf/29695542/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..8nAw3iEM-zIGIInN29yaBQ.O9mny7cb519t7zbWqq7jTO6p4oP6g98IrjcAmyNMhDCa-eA4MaRY-QYw8ZUnEekzTF13iZGi9R1QGutLb1nRdgIGO3gj7fzfUs8IgNpj38NfJa2YlhvMeGs8Mos746go3fsM7aTCKLjJ5-_veB8lakefkPJQCXmjZ5o39_7rA2L536bbOp70AYYkXEw4m0hqpnu3gq8Qnx7kFvOKo1s2S3A2f9J4JM8OL9-bE_sxtTEJJyPZ88z9HTgOCHRM1TPjr25RrMHQjq2u2aGfKU4fGYWgkK5kJnVlEdU8-aE3ji6Y_GQaQyH6MNdNOYcAZURK8NPica5Axw8nzNug-DlnuHjKQh0rLs33gEJng8F_zE_jylr4VHgegMIBZ1lRwx_C2159PwAQ9Lz0GKcTFb6EIcAdmvY0g5raX5BQ5PinWLA_rZ1juspf0kFa5f-JcEb75BJ9PFdHZFKp0EgEM_uLmGBm4YbunfmeEdFpm1DE82fKRCU6eN7Ov-p9kABpfO7qfujd0KinQuvAa5KTVLSj2TerGFKAD0VbJiIS3B9oc1UYknOoQKgAVP9Pwj8utpInw4YghHQnl6CvuZuJxIlJXKEWjQL7gwnsdDBc2YLzXWSO2XLLtXtgwRieXoATpqqjXoHYfxxNIsUby6bnllMGuH5E0Nlp3qBRfMj8soHLZOdSRPdYH1gP2D0917hEyhEZ.TKof7sgpY4RNtJf2DEs9xQ/__results___files/__results___17_0.png)

----

## Transfer Learning-Plant Disease Detection

Оригинал - [click](https://www.kaggle.com/code/gizemak/transfer-learning-plant-disease-detection#Results-and-Plots)

Преимущества трансферного обучения
Как правило, трансферное обучение позволяет нам создавать более надежные модели, которые могут выполнять широкий спектр задач.

Помогает решать сложные задачи реального мира с несколькими ограничениями
Решать такие проблемы, как недостаточная доступность помеченных данных или их почти полное отсутствие
Простота переноса знаний из одной модели в другую в зависимости от предметных областей и задач
Открывает путь к созданию общего искусственного интеллекта когда-нибудь в будущем!

- Заявленая точность метода c имплементацией ModelV3: 91.65%
- Заявленая точность метода c имплементацией Resmodel: 89.64%
- Заявленая точность метода c имплементацией VGG16: 89.97%
- Заявленая точность метода c имплементацией VGG19: 91.24%