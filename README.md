# Виртуальная примерочная



https://github.com/PRomanVl/Virtual_try_on/assets/96573887/e45da616-28ec-4c21-9962-5446a1584149


Для того чтобы реализовать виртуальную примерку вещей проекте реализованны две нейросети:

1) FrankMocap извлекает из видео SMPL (https://arxiv.org/abs/2206.08851) модель человека - это трехмерная модель определяющая положение рук, ног, туловища и головы и задающая их форму
   ![image](https://github.com/PRomanVl/Virtual_try_on/assets/96573887/729669b5-b324-4db3-b572-a5a9d62ee07d)
2) MultiGarmentNetwork (https://github.com/MPI-IS/mesh) с помощью это нейросети трехмерные модели одежды "подгоняются" под SMPL модель человека


Для отрисовки трехмерных моделей использовалась библиотека DIRT (https://github.com/pmh47/dirt)

Ссылка на колаб https://drive.google.com/file/d/1nSYrs7Q-6NBDIjzNpugjiewAn0eBdK-_/view?usp=sharing
