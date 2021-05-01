# MLPP_ML
МЛПП - элемент комплексной сервисно-методической поддержки клиентов АО «Вектор-Бест», направленной на повышение степени лояльности клиентов к компании, удовлетворенности от работы с нашей биохимической продукцией, в конечном счете – на увеличение объема продаж.
Цель: предотвращение оттока клиентов путем предсказания и своевременного выявления проблем, до того как они станут критичными и вызовут недовольство клиентов. 
Для этого после каждого цикла программы исследовались данные по оттоку участников.

Была построена модель классификатора для предсказания оттока по основным характеристикам участников. Использовался CatBoost, так как в основном были категориальные переменные.
Основные метрики:
f1_score 0.91
accuracy_score 0.96
roc_auc_score 0.94
recall_score 0.94

Основной отток связан с количеством исполняемых тестов (чем меньше тестов, тем больше вероятность оттока). Это может быть объяснено плохой организацией процесса в лаборатории, невозможности проведения большого разнообразия тестов.
Также большое влияние на отток оказывает результативность выполнения лабораторных тестов. Ухудшение качества приводит к оттоку.

Полученные данные позволяют определить некоторые направления дальнейшей работы и условия, способствующими повышению точности результатов и их сопоставимости в лабораториях, использующих наборы Вектор-Бест для биохимического анализа:
1) оснащение лабораторий автоматическими анализаторами, составляющими систему с нашими наборами реагентов, их сервисно-методическое сопровождение;
2) наличие в лабораториях эффективной системы контроля качества на аналитическом этапе (с нашей стороны – помощь в организации такой системы);
3) замена биохимических мультикалибраторов сторонних производителей, пока еще широко использующихся в лабораториях, нашей продукцией (Мультикалибратор-СЭ, Мультикалибратор-Ф);
4) продвижение наборов реагентов, основанных на более точных методов анализа.
