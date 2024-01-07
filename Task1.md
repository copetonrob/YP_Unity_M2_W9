# Задание 1: Анимируем персонажа!

## Что нужно сделать?

В этом задании мы выберем своего персонажа и настроим одну анимацию для него.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/knight_dance.gif" width="300"/>

## Инструкция

1. Открой сайт [Mixamo](https://www.mixamo.com/) , создай учетную запись если необходимо.

2. Посмотри список персонажей, выбери того, кто тебе понравился.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/mixamo1.png" width="600"/>

3. Посмотри список анимаций. Используй поиск по ключевым словам. Выбери анимацию, которая тебе понравилась.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/mixamo2.png" width="600"/>

4. Скачай персонажа с анимацией. Используй опцию with skin, если у тебя нет изначальной модели с аватаром.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/mixamo3.png" width="600"/>

5. Перенеси файл в Unity. Давай его настроим. 

Если у персонажа нет аватара (скелета с костями), то его можно создать переключив Animation Type на Humanoid.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity1.png" width="300"/>

Зацикли анимацию галочкой Loop Time

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity2.png" width="300"/>

Если у твоего персонажа не отображаются материал, попробуй извлечь текстуры или материал из fbx файла. И добавить материал на персонажа вручную.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity3.png" width="600"/>

6. Добавь персонажа в сцену и создай компонент Animator у персонажа.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity4.png" width="600"/>

7. Создай Animator Controller. 

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity6.png" width="600"/>

8. Открой Animator Controller. Добавь ссылки в компоненте Animator на Animator Controller и на аватар персонажа. Закинь анимацию в окно Animator Controller

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/unity7.png" width="600"/>

8. Запусти проект, посмотри заработала ли анимация. Поделись скриншотом на доске Миро.

<img src="https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/img/knight_dance.gif" width="300"/>