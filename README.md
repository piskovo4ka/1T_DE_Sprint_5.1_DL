# 1T_DE_Sprint_5.1_DL

Задача мини-проекта: создать нейронную сеть для мультиклассовой классификации цифр из датасета MNIST.
Согласно поставленным задачам в практическом задании была построена нейронная сеть, состоящая из 3 скрытых линейных слоев. 


Вывод:
1. Модель обучалась 50 эпох и достигла неплохих показателей, на мой взгляд. F-1 = 0.94.
2. Использовились лосс-функция CrossEntropyLoss() и оптимизатор Adam с дефолтными параметрами.
3. На 24 эпохе loss значительно упал, и по графику видно, что 27 эпох в целом было бы достаточно.
4. Dropout = 0.3 перед первым скрытым слоем дает значительное уменьшение lossa (и соответственно, прирост в метрике) по сравнению с Dropout = 0.1. Проверено эмпирическим путем.
