<<<<<<< HEAD
# Тренировки по Machine Learning
### Young&&Yandex и girafe-ai
#### Осень 2023

Теоретические и практические материалы [тренировок по машинному обучению](https://yandex.ru/yaintern/training/ml-training).


| Дата | Тема и запись | Слайды и доп. материалы | Домашнее задание | Тест для самопроверки |
|:------:|:------------------------------------|:-----------------------:|:-----------------------:|:----------------------:|
| 02.11.2023 | <details><summary>[01. Введение, kNN, Naive Bayes](https://www.youtube.com/live/k3UJOG-DKHE)</summary><br>1. Задачи машинного обучения в очевидных и неочевидных местах<br>2. Основные понятия в машинном обучении<br>3. Формальная постановка задачи обучения с учителем<br>4. Метод k ближайших соседей; kNN<br>5. Правдоподобие<br>6. Наивный байесовский классификатор</details> | [Лекция №1](./step01_intro/README.md) | | |
| 03.11.2023 | <details><summary>[02. Линейная регрессия и регуляризация](https://www.youtube.com/watch?v=5qLVUO0q644)</summary><br>1. Постановка задачи регрессии<br>2. Аналитическое решение линейной регрессии<br>3. Неустойчивость решения<br>4. Теорема Гаусса-Маркова<br> 5. L1 и L2 регуляризация</details> | [Лекция №2](./step02_linear_regression/README.md) | [01. Расстояния в kNN](./homeworks/assignment01_knn/)<br>[02. Распределение Лапласа](./homeworks/assignment02_laplace/) | |
| 09.11.2023 | <details><summary>[03. Линейная классификация. Метод максимального правдоподобия](https://www.youtube.com/watch?v=R1ccYYpEpiA)</summary><br>1. Линейные механизмы классификации. Отступ.<br>2. Логистическая функция потерь. <br>3. Логистическая регрессия и бернуллиевская случайная величина.<br>4. Оценка качества классификации</details> | [Лекция №3](./step03_logistic_regression/README.md) | | |
| 10.11.2023 | <details><summary>[04. Решающие деревья, композиции деревьев, Random Forest](https://youtube.com/live/rBIVch1h5qc)</summary><br>1. Процедура построения деревьев регрессии и классификации. Жадный алгоритм.<br>2. Информационные критерии.<br>3. Бутстрап, бэггинг. «Мудрость толпы». Случайный лес.<br>4. Особые свойства решающих деревьев.</details> | [Лекция №4](./step04_trees_and_forests/README.md) | [03. Векторные производные](./homeworks/assignment03_derivatives/)<br>[04. Степенной метод](./homeworks/assignment04_power_iteration/) | |
| 15.11.2023 | <details><summary>[05. Градиентный бустинг]()</summary><br></details> | [Лекция №5](./step05_gradient_boosting/README.md) |  | |
| 17.11.2023 | <details><summary>[06. Основы Deep Learning бустинг]()</summary><br></details> | [Лекция №6](./step06_intro_to_dl/README.md) | [05. Оценка OOB](./homeworks/assignment05_bagging_and_oob/)<br>[06. Градиентный бустинг](./homeworks/assignment06_boosting/)<br>[07. Классификация MNIST](./homeworks/assignment07_mnist_classification/) | |
| 22.11.2023 | <details><summary>[07. Интерпретация предсказаний]()</summary><br></details> | [Лекция №7](./step07_explaining_ai/README.md) |  | |
| 24.11.2023 | <details><summary>[08. Механизм дистилляции. Методы обучения с учителем.]()1. Нейронные сети и "классические" методы обучени с учителем.<br>2. Дистилляция знаний.<br>3.Подведение итогов</summary><br></details> | [Лекция №8](./step08_distillation_outro/README.md) | [08. Оценка значимости признаков](./homeworks/assignment08_importances/) | |




## Теоретический минимум по математике

Доступен в [файле](./prerequisites.md).

  

## Полезная литература:

1. [Хендбук по машинному обучению от Яндекса](https://academy.yandex.ru/dataschool/book). Чудесная книга с кратким и емким описанием основных методов машинного обучения. Доступна на русском языке.

2. Probabilistic Machine Learning: An Introduction; [English link](https://probml.github.io/pml-book/book1.html), [Русский перевод](https://dmkpress.com/catalog/computer/data/978-5-93700-119-1/). Доступна онлайн на английском языке, в печатном виде – на русском.

3. Deep Learning Book: [English link](https://www.deeplearningbook.org/). Первая часть (Part I) крайне рекомендуется к прочтению.
=======
[**Ссылка на ветку ML тренировок Яндекса 2023**](https://github.com/girafe-ai/ml-course/tree/23f_yandex_ml_trainings)

# Machine Learning course
First semester of girafe-ai Machine Learning course

## Recordings and materials

| Date   | Content                | Lecture video | Slides               | WarmUp test             | HW                  | Deadline          | Comments |
|:------:|:-----------------------|:------------:|:------------:|:-----------------------:|:------------------------:|:----------------------:|:----------------------:|
| 05.09.2022 | Week01. Intro, Naive Bayes and kNN. | [Запись лекции 2021](https://youtu.be/74Kd-rNxSm0) [Запись семинара 2021](https://youtu.be/bzCwHkO-YEk)| [Слайды](week0_01_naive_bayes/lect001_intro_knn_naive_bayes.pdf) | | [Assignment 01: kNN](homeworks/assignment0_01_knn) | 23.59 AOE, 03.10.2022 | *По техническим причинам запись лекции 2022 года не велась*
| 12.09.2022 | extra Week. Linear algebra recap. | [Запись лекции](https://youtu.be/vKfdtHnXVEY?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM) [Запись семинара 2022](https://youtu.be/Ha3pJJnt5YA?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM)| [Слайды](week0_00_linear_algebra_recap/lecture00-linear_algebra_recap.pdf) |  | |  |  |
| 19.09.2022     | Week02. Linear Regression. | [Запись лекции](https://youtu.be/imzlM4jRbD4?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM) [Запись семинара 2022](https://youtu.be/LLGLeM3JKDQ?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM) | [Слайды](week0_02_linear_reg/lect002_linear_regression.pdf) |  |  [Assignment 02: Linear Regression](homeworks/assignment0_02_lin_reg) | 23.59 AOE, 10.10.2022 |  |
| 26.09.2022     | Week03. Linear Classification. | [Запись лекции](https://youtu.be/db1XU_WJHFs?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM) [Запись семинара 2022](https://youtu.be/vSeETg1two8)   | [Слайды](week0_03_linear_classification/msai-ml_s21_lect003_logistic_regression.pdf)   |  | [Lab01: ML pipeline](https://github.com/girafe-ai/ml-course/tree/22f_basic/homeworks/lab01_ml_pipeline) | 23.59 AOE 10.11.2022 | 
| 03.10.2022     | Week04. SVM, PCA. | [Запись лекции](https://youtu.be/mlA-XxC9Ugg?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM) [Запись семинара 2022](https://youtu.be/z-JqKoyHHRI?list=PLJR10EXrBaAv2vPy05qesewHv9JFc8ZjM)   | [Слайды](week0_04_svm_and_pca/lect004_svm_pca.pdf) |  |  [Assignment 03: SVM kernel](https://github.com/girafe-ai/ml-course/tree/22f_basic/homeworks/assignment0_03_svm) | 23.59 AOE, 24.10.2022 |  
| 10.10.2022     | Week05. Trees and ensembles | [Запись лекции](https://youtu.be/kbNZsQj2eHk)   | [Слайды](week0_05_trees_and_ensembles/lect005_trees_and_ensembles_style.pdf) | | [Optional assignment 04: Tree from scratch](https://github.com/girafe-ai/ml-course/tree/22f_basic/homeworks/assignment0_04_tree) | 23.59 AOE, 22.12.2022 | Вместо семинара проходила контрольная работа | 
| 17.10.2022     | Week06. Gradient boosting | [Запись лекции](https://youtu.be/Y97xrRiLY1Q) [Запись семинара](https://youtu.be/4vo39B6M270)   | [Слайды](week0_06_boosting/week0_06_gradient_boosting.pdf) | | | |  | 
| 24.10.2022     | Week07. Разбор теста | [Запись разбора](https://youtu.be/YiO1N6yVJcg)    |  | | | | Вместо лекции были тест и разбор. | 
| 31.10.2022     | Week08. Intro into Deep Learning | [Запись лекции](https://youtu.be/G--msc2IR-Y) [Запись семинара](https://youtu.be/0WMAfRuFHy8)   | [Слайды](https://github.com/girafe-ai/ml-course/blob/22f_basic/week0_07_intro_to_DL/lect007_intro_to_dl_style.pdf) | | | |  | 
| 07.11.2022     | Week09. Backpropogation |  [Запись семинара](https://youtu.be/HGk5xQ0azdo)   | [Слайды]() | | | | Лекция не велась по причине болезни преподавателя, однако был проведён дополнительный семинар по backpropogation | 
| 14.11.2022     | Week10. Dropout and Batchnorm | [Запись лекции](https://youtu.be/UtEV_ILJTA0) [Запись семинара](https://youtu.be/tq-mmdsW5QI)   | [Слайды](https://github.com/girafe-ai/ml-course/blob/22f_basic/week0_08_dropout_batchnorm/lect008_deeplearning_part_2_style.pdf) | | | |  | 
| 21.11.2022     | Week11. Embeddings and seq2seq model | [Запись лекции](https://youtu.be/kUAnB_Leg6E) [Запись семинара](https://youtu.be/KOIEozoCQo0)   | [Слайды](https://github.com/girafe-ai/ml-course/blob/22f_basic/week0_09_embeddings_and_seq2seq/lect009_Language_models_and_RNN.pdf) | | | |  | 



## Prerequisites
Prerequisites are located [here](./prerequisites.md).

## Literature:
1. [YSDA ML Book](https://academy.yandex.ru/dataschool/book) (Russian only)
2. Probabilistic Machine Learning: An Introduction; [English link](https://probml.github.io/pml-book/book1.html), [Русский перевод](https://dmkpress.com/catalog/computer/data/978-5-93700-119-1/)
3. Deep Learning Book: [English link](https://www.deeplearningbook.org/). Первая часть (Part I) крайне рекомендуется к прочтению.
 
More additional materials are available [here](https://github.com/girafe-ai/ml-course/blob/22f_basic/extra_materials.md)

## Exam program:
Available [here](./approximate_program.pdf)


## Main authors:
* Radoslav Neychev
* Vladislav Goncharenko

## Contributors:
* Iurii Efimov
* Nikolay Karpachev
* Ivan Provilkov
* Valery Marchenkov
* Anastasia Ianina
* Irina Rudenko
* Fedor Ryabov

## Acknowledgements:
Special thanks to:
* Stanislav Fedotov, YSDA for informative discussions, program verification and support.
* Konstantiv Vorontsov
* Vadim Strijov for teaching this course teachers
* Just Heuristic




>>>>>>> b57d7c8df19b6166dbc173ee027f9fdd55cc8686
