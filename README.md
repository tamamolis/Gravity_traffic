# Gravity_traffic
Проект по транспортным потокам, осень 2018

Дано:
* Гравитационная модель 
  T_i_j = A_i * O_i * F(C_i_j)
  где:
  - T_i_j -- количество поездок из i в j
  - O_i (origins) -- количество отправлений из зоны i во все зоны (вкл. i)
  - D_j (destinations) -- количество прибытий в зону j из всех зон (вкл. j)
  - C_i_j -- издержки на перемещение из i в j
  - F() -- гравитационная функцияя издержек
  - A_i -- балансировочный коэффициент для отправлений из i
  - B_j -- балансировочный коэффициент для прибытий в j
* Результаты опроса:
  csv-файл с пятью полями:
  - зона i
  - зона j
  - количество жителей i, кто едет в зону j
  - среднее время поездки в минутах
  - среднее расстояние по прямой между домом и работой
