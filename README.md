# torch_book
Задания к практическим занятиям по дисциплине "Введение в нейронные сети"

# О курсе
В курсе осуществляется знакомство с пакетом pytorch и написание программного кода для создания, обучения и тестирования нейронных сетей классических архитектур.  

## 1. Введение в pytorch (1_Basic)
На занятии рассматриваются основные операции по использованию Pytorch для вычислений тензоров, функции для линейных и нелинейных операций. Раскрываются особенности обработки тензоров с использованием GPU и CPU. Осуществляется знакомство с модулем autograd
   
Домашнее задание:
- провести дифференцирование сложной функции

## 2. Простейшая нейронная сеть на torch (2_Perceptron)
На занятии рассматривается перцептрон и его реализация на pytorch для решения простейших задач
  
Домашнее задание:
- решить задачу нелинейной классификации

## 3. Функции активации и методы оптимизации (3_Activation_Optimiz)
На занятии рассматриваются различные функции активации нейронов (ReLU, LeReLu и др.) и методы оптимизации функции ошибок от простейшего (SGD) до Adam 

Домашнее задание:  

## 4. Сверточные нейронные сети (4_SimpleConv)
На занятии рассматриваются простейшие сверточные нейронные сети для решения задачи классификации изображений датасетов MNIST и CIFAR,  а также дополнительные техники dropout и batchNormalization
 
Домашнее задание:
- реализовать нейронную сеть для классификации дорожных знаков [датасет](https://graphics.cs.msu.ru/projects/traffic-sign-recognition.html)

## 5. Рекурентные нейронные сети (5_RNN)
На занятии рассматриваются вопросы построение рекурентных нейронных сетей, LSTM сетей, двунаправленных сетей

## 6. TransferLearning (6_TL)
На занятии рассматриваются техники по использованию предобученных нейронных сетей, сохранения моделей в формат Torch и ONNX, производится демонстрация весов модели

##  7. Аугментация данных и визуализация результатов (7_Visualization)
На занятии рассматриваются техники по микшированию изображений и сглаживанию маркеровок. Визуализация результатов демонстируется на примере tensorBoard и сайта wandb.ai. Также рассматриваются техники по визуализации слоев участвующих в активации и созданию стекстрейсов. 

##  8. Генеративно-состязательные сети (8_GAN)
На занятии рассматриваются примеры нескольких GAN сетей

##  9. Сегментационные сети (9_Segm)
На занятии используется предобученная нейронная сеть U-net

## Дополнительно:

Hinweis zum Download des Datensatzes in Kapitel 2 ([ссылка на github](https://github.com/falloutdurham/beginners-pytorch-deep-learning))

Датасет для решения задачи классификации [Датасет](https://drive.google.com/file/d/16h8E7dnj5TpxF_ex4vF2do20iMWziM70/edit)





