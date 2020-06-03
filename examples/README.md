
### Iris
Простая задача классификации цветков ириса

### Handwritten digits recognition by PCA and clustering
Задача распознавания рукописного текста (цифр от 0 до 9) с помощью алгоритмов PCA и K-Means. Блокнот сделан на основе практической работы на семинаре Intel 24-го апреля (проходил на площадке Selectel в Санкт-Петербурге).

### Handwritten digits recognition by simple NN
Задача распознавания рукописного текста (цифр от 0 до 9) с помощью простейшей нейронной сети (2 слоя). Пример использования Keras и Tensorflow.

### Handwritten digits recognition - using simple autoencoder
Задача распознавания рукописного текста (цифр от 0 до 9) с помощью простейшего автоэнкодера для снижения размерности.

### Handwrotten digits recognition - using deep autoencoder
Задача распознавания рукописного текста (цифр от 0 до 9) с помощью глубинного автоэнкодера для снижения размерности.

### Handwritten digits recognition - using convolutional autoencoder
Задача распознавания рукописного текста (цифр от 0 до 9) с помощью свёрточного автоэнкодера для снижения размерности.

### Xor MLP
Пример обучения нейронной сети для простых булевских функций (xor). Сохранение модели в H5 и TF, конвертация в ONNX:
```bash
   python -m tf2onnx.convert --saved-model xor.tf --output xor2.onnx
```
