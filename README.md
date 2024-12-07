### Алгоритм расчета генерации солнечной электростанции
Средние значения плотности солнечной энергии $[{МДж\overм^2}]$, доходящей до поверхности Земли за год.
Географическая широта [град.]| Северное полушарие | Южное полушарие |
--- | --- | --- |
 |90|5434|5434|
 |80|5591|5583|
 |70|6150|6151|
 |60|7442|7454|
 |50|8957|8985|
 |40|10388|10391|
 |30|11564|11564|
 |20|12444|12445|
 |10|12989|12989|
 |0|13178|13178|
 
Из поверхностной плотности солнечной энергии $I[{МДж\overм^2}]$, доходящей до Земли на заданной широте за 1 год, находим мощность солнечного излучения $P_{i}[Вт]$, падающего на площадь поверхности $S_{i}[м^2]$ i-ого типа солнечной панели.

$$ P_{i}={{I[МДж/м^2]\cdot10^6\over182[Дни]\cdot24[часы]\cdot3600[секунды]}\cdot S_{i}[м^2]} $$

Далее вычисляем КПД $η_{i}$ для каждого типа солнечной панели, входящего в станцию. Это несложно сделать, поскольку мощность солнечной панели $P_{пi}$ измеряется при инсоляции в $1000Вт/м^2$.

$$η_{i}={P_{пi}[Вт]\over{1000[{Вт\overм^2}]\cdot S_{i}[м^2]}}$$

Для получения средней суточной генерации E[Вт*ч] просуммируем энергии, производимые k наборомами из $n_{i}$ одинаковых солнечных батарей, которые являются ничем иным как премножением P_{i}, $η_{i}$ и $n_{i}$:

$$E=\sum_{i=1}^k E_{i}^2={\sum_{i=1}^k P_{i}\cdotη_{i}\cdot n_{i}}= \sum_{i=1}^k{{I\cdot10^6\cdot P_{пi}\cdot n\cdot S_{i}}\over{182\cdot24\cdot3600\cdot1000\cdot S_{i}}}=\sum_{i=1}^k{I\cdot P_п\cdot n\over15724,8}$$




