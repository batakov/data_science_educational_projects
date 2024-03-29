<h2 align="left">Определение уровня дохода</h2>

###

<h3 align="left">Задача проекта</h3>

###

<p align="left">В данном проекте решал задачу бинарной классификации физических лиц по уровню дохода.</p>

###

<h3 align="left">Выводы по работе</h3>

###

<p align="left">* В ходе выполнения работы мне удалось обучить модели и оценить их качество. Поскольку условиями задачи не указано, какого значения метрики score нам нужно было достигнуть трудно судить о том, насколько его значение получилось удовлетворительным или нет. Конечно хотелось бы получать значение score близкое к 100%.<br>* При работе с данными я проверил наличие пропусков в датасете. Пустых значений в нем не оказалось, но были значения "?", что по сути является пропуском. Строки с данными значениями были удалены из данных. Альтернативные варианты работы с пропусками я указал в коде выше.<br>* Точность двух моделей оказалась сопоставима, но скорость обучения в случае с логистической регрессией была много выше - пара секунд. При этом скорость обучения при использования модели опорных векторов была минута с небольшим.<br>* В целом я считаю, что модели в полной мере справились со своей задачей. Повысить качество предсказания можно было бы за счет запонения пропусков в данных, вместо их удаления. Так же можно было бы взять все признаки, которые есть в датасете, и я так и сделал на самом деле. Но когда обучал модель, Google Colab завис - оперативной памяти не хватило. Также получить более высокое качество наверное можно было бы добавив другие, новые признаки в датасет. При работе я пробовал разные варианты признаков, брал 3 признака, по итогу взял 7. Но score принципиально не менялся, значение лежало в диапазон от 0,78 до 0,82.</p>

###

<h3 align="left">Стек</h3>

###

<p align="left">* NumPy<br>* Pandas<br>* SciPy<br>* Matplotlib<br>* LogisticRegression<br>* SVC</p>

###
