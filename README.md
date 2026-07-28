# Генератор лабіринтів

Десктопний застосунок для створення, візуалізації та проходження лабіринтів.  
Програма дозволяє одночасно генерувати до трьох лабіринтів із різними параметрами та алгоритмами.

## Завантаження

[![Завантажити програму](https://img.shields.io/badge/Завантажити-програму-blue?style=for-the-badge&logo=windows)](https://github.com/MULTIGID/Maze_generator/raw/refs/heads/main/Maze_generator_UKR.zip)

[![Завантажити мануал UA](https://img.shields.io/badge/Завантажити-мануал_UA-green?style=for-the-badge&logo=adobeacrobatreader)](https://github.com/MULTIGID/Maze_generator/raw/refs/heads/main/User_manual_UKR.pdf)

Завантажте архів, розпакуйте його та запустіть виконуваний файл програми. Детальний опис використання доступний у PDF-інструкції.
## Основні можливості

- генерація до трьох лабіринтів одночасно;
- налаштування висоти та ширини лабіринту;
- анімоване відображення процесу генерації;
- регулювання затримки анімації;
- вибір алгоритму генерації:
  - алгоритм Прима;
  - алгоритм Крускала;
  - пошук у глибину;
  - алгоритм Еллера;
  - рекурсивний поділ;
- експорт лабіринтів у формати `PNG`, `PDF`, `SVG` та `FBX`;
- інтерактивне проходження згенерованого лабіринту.

## Керування

Для проходження лабіринту використовуйте:

- клавіші зі стрілками `↑`, `←`, `↓`, `→`;
- або клавіші `W`, `A`, `S`, `D`.

Зелений круг позначає поточну позицію гравця, а блакитний квадрат — точку фінішу.

## Використання

1. Оберіть один або декілька лабіринтів.
2. Вкажіть алгоритм генерації та розміри.
3. За потреби увімкніть анімацію.
4. Натисніть кнопку **«Генерація»**.
5. Для проходження двічі натисніть на потрібний лабіринт.
6. Для збереження оберіть формат і натисніть **«Експорт»**.

```stl
solid exported
	facet normal 0 0 1
		outer loop
			vertex 0 0 0
			vertex 10 0 0
			vertex 10 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 0
			vertex 10 10 0
			vertex 0 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 0
			vertex 0 0 10
			vertex 0 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 0
			vertex 0 10 10
			vertex 0 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 20
			vertex 10 0 20
			vertex 10 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 20
			vertex 10 10 20
			vertex 0 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 10
			vertex 0 0 20
			vertex 0 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 10
			vertex 0 10 20
			vertex 0 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 20
			vertex 10 0 20
			vertex 10 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 20
			vertex 10 10 20
			vertex 0 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 20
			vertex 0 0 30
			vertex 0 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 20
			vertex 0 10 30
			vertex 0 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 30
			vertex 10 0 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 30
			vertex 10 10 40
			vertex 10 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 40
			vertex 10 0 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 40
			vertex 10 10 40
			vertex 0 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 30
			vertex 0 0 40
			vertex 0 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 30
			vertex 0 10 40
			vertex 0 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 40
			vertex 10 0 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 40
			vertex 10 10 40
			vertex 0 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 40
			vertex 0 0 50
			vertex 0 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 40
			vertex 0 10 50
			vertex 0 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 60
			vertex 10 0 60
			vertex 10 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 60
			vertex 10 10 60
			vertex 0 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 50
			vertex 0 0 60
			vertex 0 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 50
			vertex 0 10 60
			vertex 0 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 60
			vertex 10 0 60
			vertex 10 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 60
			vertex 10 10 60
			vertex 0 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 70
			vertex 10 0 70
			vertex 10 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 70
			vertex 10 10 70
			vertex 0 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 60
			vertex 0 0 70
			vertex 0 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 60
			vertex 0 10 70
			vertex 0 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 70
			vertex 10 0 70
			vertex 10 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 70
			vertex 10 10 70
			vertex 0 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 80
			vertex 10 0 80
			vertex 10 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 80
			vertex 10 10 80
			vertex 0 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 70
			vertex 0 0 80
			vertex 0 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 70
			vertex 0 10 80
			vertex 0 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 80
			vertex 10 0 80
			vertex 10 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 80
			vertex 10 10 80
			vertex 0 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 90
			vertex 10 0 90
			vertex 10 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 90
			vertex 10 10 90
			vertex 0 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 80
			vertex 0 0 90
			vertex 0 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 80
			vertex 0 10 90
			vertex 0 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 90
			vertex 10 0 90
			vertex 10 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 90
			vertex 10 10 90
			vertex 0 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 90
			vertex 10 0 100
			vertex 10 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 90
			vertex 10 10 100
			vertex 10 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 90
			vertex 0 0 100
			vertex 0 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 90
			vertex 0 10 100
			vertex 0 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 100
			vertex 0 0 110
			vertex 0 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 100
			vertex 0 10 110
			vertex 0 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 110
			vertex 10 0 120
			vertex 10 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 110
			vertex 10 10 120
			vertex 10 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 110
			vertex 0 0 120
			vertex 0 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 110
			vertex 0 10 120
			vertex 0 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 130
			vertex 10 0 130
			vertex 10 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 130
			vertex 10 10 130
			vertex 0 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 120
			vertex 0 0 130
			vertex 0 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 120
			vertex 0 10 130
			vertex 0 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 130
			vertex 10 0 130
			vertex 10 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 130
			vertex 10 10 130
			vertex 0 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 130
			vertex 10 0 140
			vertex 10 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 130
			vertex 10 10 140
			vertex 10 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 130
			vertex 0 0 140
			vertex 0 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 130
			vertex 0 10 140
			vertex 0 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 150
			vertex 10 0 150
			vertex 10 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 150
			vertex 10 10 150
			vertex 0 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 140
			vertex 0 0 150
			vertex 0 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 140
			vertex 0 10 150
			vertex 0 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 150
			vertex 10 0 150
			vertex 10 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 150
			vertex 10 10 150
			vertex 0 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 160
			vertex 10 0 160
			vertex 10 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 160
			vertex 10 10 160
			vertex 0 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 150
			vertex 0 0 160
			vertex 0 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 150
			vertex 0 10 160
			vertex 0 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 160
			vertex 10 0 160
			vertex 10 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 160
			vertex 10 10 160
			vertex 0 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 160
			vertex 10 0 170
			vertex 10 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 160
			vertex 10 10 170
			vertex 10 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 160
			vertex 0 0 170
			vertex 0 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 160
			vertex 0 10 170
			vertex 0 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 180
			vertex 10 0 180
			vertex 10 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 180
			vertex 10 10 180
			vertex 0 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 170
			vertex 0 0 180
			vertex 0 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 170
			vertex 0 10 180
			vertex 0 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 180
			vertex 10 0 180
			vertex 10 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 180
			vertex 10 10 180
			vertex 0 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 190
			vertex 10 0 190
			vertex 10 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 190
			vertex 10 10 190
			vertex 0 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 180
			vertex 0 0 190
			vertex 0 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 180
			vertex 0 10 190
			vertex 0 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 190
			vertex 10 0 190
			vertex 10 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 190
			vertex 10 10 190
			vertex 0 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 190
			vertex 10 0 200
			vertex 10 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 190
			vertex 10 10 200
			vertex 10 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 190
			vertex 0 0 200
			vertex 0 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 190
			vertex 0 10 200
			vertex 0 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 210
			vertex 10 0 210
			vertex 10 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 210
			vertex 10 10 210
			vertex 0 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 200
			vertex 0 0 210
			vertex 0 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 200
			vertex 0 10 210
			vertex 0 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 210
			vertex 10 0 210
			vertex 10 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 210
			vertex 10 10 210
			vertex 0 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 210
			vertex 10 0 220
			vertex 10 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 210
			vertex 10 10 220
			vertex 10 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 210
			vertex 0 0 220
			vertex 0 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 210
			vertex 0 10 220
			vertex 0 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 230
			vertex 10 0 230
			vertex 10 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 230
			vertex 10 10 230
			vertex 0 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 220
			vertex 0 0 230
			vertex 0 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 220
			vertex 0 10 230
			vertex 0 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 230
			vertex 10 0 230
			vertex 10 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 230
			vertex 10 10 230
			vertex 0 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 240
			vertex 10 0 240
			vertex 10 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 240
			vertex 10 10 240
			vertex 0 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 230
			vertex 0 0 240
			vertex 0 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 230
			vertex 0 10 240
			vertex 0 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 240
			vertex 10 0 240
			vertex 10 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 240
			vertex 10 10 240
			vertex 0 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 250
			vertex 10 0 250
			vertex 10 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 0 0 250
			vertex 10 10 250
			vertex 0 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 240
			vertex 0 0 250
			vertex 0 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 0 0 240
			vertex 0 10 250
			vertex 0 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 0
			vertex 20 0 0
			vertex 20 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 0
			vertex 20 10 0
			vertex 10 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 10
			vertex 20 0 10
			vertex 20 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 10
			vertex 20 10 10
			vertex 10 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 10
			vertex 20 0 10
			vertex 20 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 10
			vertex 20 10 10
			vertex 10 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 20
			vertex 20 0 20
			vertex 20 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 20
			vertex 20 10 20
			vertex 10 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 20
			vertex 20 0 20
			vertex 20 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 20
			vertex 20 10 20
			vertex 10 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 30
			vertex 20 0 30
			vertex 20 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 30
			vertex 20 10 30
			vertex 10 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 30
			vertex 20 0 30
			vertex 20 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 30
			vertex 20 10 30
			vertex 10 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 40
			vertex 20 0 40
			vertex 20 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 40
			vertex 20 10 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 30
			vertex 10 0 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 30
			vertex 10 10 40
			vertex 10 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 40
			vertex 20 0 40
			vertex 20 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 40
			vertex 20 10 40
			vertex 10 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 50
			vertex 20 0 50
			vertex 20 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 50
			vertex 20 10 50
			vertex 10 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 50
			vertex 20 0 50
			vertex 20 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 50
			vertex 20 10 50
			vertex 10 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 50
			vertex 20 0 60
			vertex 20 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 50
			vertex 20 10 60
			vertex 20 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 60
			vertex 20 0 60
			vertex 20 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 60
			vertex 20 10 60
			vertex 10 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 60
			vertex 20 0 60
			vertex 20 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 60
			vertex 20 10 60
			vertex 10 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 70
			vertex 20 0 70
			vertex 20 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 70
			vertex 20 10 70
			vertex 10 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 70
			vertex 20 0 70
			vertex 20 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 70
			vertex 20 10 70
			vertex 10 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 80
			vertex 20 0 90
			vertex 20 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 80
			vertex 20 10 90
			vertex 20 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 90
			vertex 20 0 100
			vertex 20 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 90
			vertex 20 10 100
			vertex 20 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 100
			vertex 20 0 100
			vertex 20 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 100
			vertex 20 10 100
			vertex 10 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 90
			vertex 10 0 100
			vertex 10 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 90
			vertex 10 10 100
			vertex 10 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 100
			vertex 20 0 100
			vertex 20 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 100
			vertex 20 10 100
			vertex 10 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 100
			vertex 20 0 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 100
			vertex 20 10 110
			vertex 20 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 110
			vertex 20 0 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 110
			vertex 20 10 110
			vertex 10 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 110
			vertex 20 0 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 110
			vertex 20 10 110
			vertex 10 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 110
			vertex 20 0 120
			vertex 20 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 110
			vertex 20 10 120
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 110
			vertex 10 0 120
			vertex 10 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 110
			vertex 10 10 120
			vertex 10 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 130
			vertex 20 0 140
			vertex 20 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 130
			vertex 20 10 140
			vertex 20 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 130
			vertex 10 0 140
			vertex 10 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 130
			vertex 10 10 140
			vertex 10 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 140
			vertex 20 0 150
			vertex 20 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 140
			vertex 20 10 150
			vertex 20 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 150
			vertex 20 0 150
			vertex 20 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 150
			vertex 20 10 150
			vertex 10 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 150
			vertex 20 0 150
			vertex 20 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 150
			vertex 20 10 150
			vertex 10 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 160
			vertex 20 0 160
			vertex 20 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 160
			vertex 20 10 160
			vertex 10 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 160
			vertex 20 0 160
			vertex 20 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 160
			vertex 20 10 160
			vertex 10 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 160
			vertex 10 0 170
			vertex 10 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 160
			vertex 10 10 170
			vertex 10 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 170
			vertex 20 0 180
			vertex 20 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 170
			vertex 20 10 180
			vertex 20 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 180
			vertex 20 0 180
			vertex 20 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 180
			vertex 20 10 180
			vertex 10 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 180
			vertex 20 0 180
			vertex 20 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 180
			vertex 20 10 180
			vertex 10 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 190
			vertex 20 0 190
			vertex 20 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 190
			vertex 20 10 190
			vertex 10 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 190
			vertex 20 0 190
			vertex 20 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 190
			vertex 20 10 190
			vertex 10 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 190
			vertex 10 0 200
			vertex 10 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 190
			vertex 10 10 200
			vertex 10 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 210
			vertex 20 0 210
			vertex 20 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 210
			vertex 20 10 210
			vertex 10 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 210
			vertex 20 0 210
			vertex 20 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 210
			vertex 20 10 210
			vertex 10 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 210
			vertex 20 0 220
			vertex 20 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 210
			vertex 20 10 220
			vertex 20 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 210
			vertex 10 0 220
			vertex 10 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 10 0 210
			vertex 10 10 220
			vertex 10 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 220
			vertex 20 0 230
			vertex 20 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 220
			vertex 20 10 230
			vertex 20 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 250
			vertex 20 0 250
			vertex 20 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 10 0 250
			vertex 20 10 250
			vertex 10 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 0
			vertex 30 0 0
			vertex 30 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 0
			vertex 30 10 0
			vertex 20 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 10
			vertex 30 0 10
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 10
			vertex 30 10 10
			vertex 20 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 10
			vertex 30 0 10
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 10
			vertex 30 10 10
			vertex 20 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 10
			vertex 30 0 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 10
			vertex 30 10 20
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 20
			vertex 30 0 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 20
			vertex 30 10 20
			vertex 20 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 20
			vertex 30 0 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 20
			vertex 30 10 20
			vertex 20 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 20
			vertex 30 0 30
			vertex 30 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 20
			vertex 30 10 30
			vertex 30 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 40
			vertex 30 0 40
			vertex 30 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 40
			vertex 30 10 40
			vertex 20 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 40
			vertex 30 0 40
			vertex 30 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 40
			vertex 30 10 40
			vertex 20 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 50
			vertex 30 0 50
			vertex 30 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 50
			vertex 30 10 50
			vertex 20 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 50
			vertex 30 0 50
			vertex 30 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 50
			vertex 30 10 50
			vertex 20 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 50
			vertex 20 0 60
			vertex 20 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 50
			vertex 20 10 60
			vertex 20 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 60
			vertex 30 0 70
			vertex 30 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 60
			vertex 30 10 70
			vertex 30 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 70
			vertex 30 0 70
			vertex 30 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 70
			vertex 30 10 70
			vertex 20 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 70
			vertex 30 0 70
			vertex 30 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 70
			vertex 30 10 70
			vertex 20 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 70
			vertex 30 0 80
			vertex 30 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 70
			vertex 30 10 80
			vertex 30 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 80
			vertex 20 0 90
			vertex 20 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 80
			vertex 20 10 90
			vertex 20 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 90
			vertex 30 0 100
			vertex 30 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 90
			vertex 30 10 100
			vertex 30 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 90
			vertex 20 0 100
			vertex 20 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 90
			vertex 20 10 100
			vertex 20 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 110
			vertex 30 0 110
			vertex 30 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 110
			vertex 30 10 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 100
			vertex 20 0 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 100
			vertex 20 10 110
			vertex 20 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 110
			vertex 30 0 110
			vertex 30 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 110
			vertex 30 10 110
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 110
			vertex 20 0 120
			vertex 20 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 110
			vertex 20 10 120
			vertex 20 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 120
			vertex 30 0 130
			vertex 30 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 120
			vertex 30 10 130
			vertex 30 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 130
			vertex 30 0 130
			vertex 30 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 130
			vertex 30 10 130
			vertex 20 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 130
			vertex 30 0 130
			vertex 30 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 130
			vertex 30 10 130
			vertex 20 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 140
			vertex 30 0 140
			vertex 30 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 140
			vertex 30 10 140
			vertex 20 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 130
			vertex 20 0 140
			vertex 20 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 130
			vertex 20 10 140
			vertex 20 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 140
			vertex 30 0 140
			vertex 30 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 140
			vertex 30 10 140
			vertex 20 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 140
			vertex 20 0 150
			vertex 20 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 140
			vertex 20 10 150
			vertex 20 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 160
			vertex 30 0 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 160
			vertex 30 10 170
			vertex 30 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 170
			vertex 30 0 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 170
			vertex 30 10 170
			vertex 20 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 170
			vertex 30 0 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 170
			vertex 30 10 170
			vertex 20 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 170
			vertex 30 0 180
			vertex 30 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 170
			vertex 30 10 180
			vertex 30 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 170
			vertex 20 0 180
			vertex 20 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 170
			vertex 20 10 180
			vertex 20 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 180
			vertex 30 0 190
			vertex 30 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 180
			vertex 30 10 190
			vertex 30 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 200
			vertex 30 0 200
			vertex 30 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 200
			vertex 30 10 200
			vertex 20 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 200
			vertex 30 0 200
			vertex 30 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 200
			vertex 30 10 200
			vertex 20 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 210
			vertex 30 0 210
			vertex 30 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 210
			vertex 30 10 210
			vertex 20 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 210
			vertex 30 0 210
			vertex 30 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 210
			vertex 30 10 210
			vertex 20 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 220
			vertex 30 0 220
			vertex 30 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 220
			vertex 30 10 220
			vertex 20 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 210
			vertex 20 0 220
			vertex 20 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 210
			vertex 20 10 220
			vertex 20 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 220
			vertex 30 0 220
			vertex 30 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 220
			vertex 30 10 220
			vertex 20 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 230
			vertex 30 0 230
			vertex 30 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 230
			vertex 30 10 230
			vertex 20 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 220
			vertex 20 0 230
			vertex 20 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 20 0 220
			vertex 20 10 230
			vertex 20 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 230
			vertex 30 0 230
			vertex 30 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 230
			vertex 30 10 230
			vertex 20 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 230
			vertex 30 0 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 230
			vertex 30 10 240
			vertex 30 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 240
			vertex 30 0 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 240
			vertex 30 10 240
			vertex 20 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 240
			vertex 30 0 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 240
			vertex 30 10 240
			vertex 20 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 250
			vertex 30 0 250
			vertex 30 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 20 0 250
			vertex 30 10 250
			vertex 20 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 0
			vertex 40 0 0
			vertex 40 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 0
			vertex 40 10 0
			vertex 30 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 10
			vertex 40 0 10
			vertex 40 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 10
			vertex 40 10 10
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 10
			vertex 40 0 10
			vertex 40 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 10
			vertex 40 10 10
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 20
			vertex 40 0 20
			vertex 40 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 20
			vertex 40 10 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 10
			vertex 30 0 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 10
			vertex 30 10 20
			vertex 30 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 20
			vertex 40 0 20
			vertex 40 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 20
			vertex 40 10 20
			vertex 30 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 30
			vertex 40 0 30
			vertex 40 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 30
			vertex 40 10 30
			vertex 30 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 20
			vertex 30 0 30
			vertex 30 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 20
			vertex 30 10 30
			vertex 30 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 30
			vertex 40 0 30
			vertex 40 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 30
			vertex 40 10 30
			vertex 30 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 40
			vertex 40 0 40
			vertex 40 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 40
			vertex 40 10 40
			vertex 30 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 40
			vertex 40 0 40
			vertex 40 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 40
			vertex 40 10 40
			vertex 30 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 40
			vertex 40 0 50
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 40
			vertex 40 10 50
			vertex 40 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 50
			vertex 40 0 60
			vertex 40 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 50
			vertex 40 10 60
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 60
			vertex 40 0 70
			vertex 40 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 60
			vertex 40 10 70
			vertex 40 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 60
			vertex 30 0 70
			vertex 30 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 60
			vertex 30 10 70
			vertex 30 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 80
			vertex 40 0 80
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 80
			vertex 40 10 80
			vertex 30 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 70
			vertex 30 0 80
			vertex 30 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 70
			vertex 30 10 80
			vertex 30 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 80
			vertex 40 0 80
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 80
			vertex 40 10 80
			vertex 30 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 80
			vertex 40 0 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 80
			vertex 40 10 90
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 90
			vertex 40 0 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 90
			vertex 40 10 90
			vertex 30 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 90
			vertex 40 0 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 90
			vertex 40 10 90
			vertex 30 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 90
			vertex 40 0 100
			vertex 40 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 90
			vertex 40 10 100
			vertex 40 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 90
			vertex 30 0 100
			vertex 30 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 90
			vertex 30 10 100
			vertex 30 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 110
			vertex 40 0 120
			vertex 40 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 110
			vertex 40 10 120
			vertex 40 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 120
			vertex 40 0 120
			vertex 40 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 120
			vertex 40 10 120
			vertex 30 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 120
			vertex 40 0 120
			vertex 40 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 120
			vertex 40 10 120
			vertex 30 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 120
			vertex 40 0 130
			vertex 40 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 120
			vertex 40 10 130
			vertex 40 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 120
			vertex 30 0 130
			vertex 30 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 120
			vertex 30 10 130
			vertex 30 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 140
			vertex 40 0 140
			vertex 40 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 140
			vertex 40 10 140
			vertex 30 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 140
			vertex 40 0 140
			vertex 40 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 140
			vertex 40 10 140
			vertex 30 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 150
			vertex 40 0 150
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 150
			vertex 40 10 150
			vertex 30 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 150
			vertex 40 0 150
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 150
			vertex 40 10 150
			vertex 30 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 150
			vertex 40 0 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 150
			vertex 40 10 160
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 160
			vertex 40 0 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 160
			vertex 40 10 160
			vertex 30 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 160
			vertex 40 0 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 160
			vertex 40 10 160
			vertex 30 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 170
			vertex 40 0 170
			vertex 40 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 170
			vertex 40 10 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 160
			vertex 30 0 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 160
			vertex 30 10 170
			vertex 30 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 170
			vertex 40 0 170
			vertex 40 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 170
			vertex 40 10 170
			vertex 30 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 180
			vertex 40 0 180
			vertex 40 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 180
			vertex 40 10 180
			vertex 30 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 170
			vertex 30 0 180
			vertex 30 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 170
			vertex 30 10 180
			vertex 30 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 180
			vertex 40 0 180
			vertex 40 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 180
			vertex 40 10 180
			vertex 30 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 190
			vertex 40 0 190
			vertex 40 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 190
			vertex 40 10 190
			vertex 30 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 180
			vertex 30 0 190
			vertex 30 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 180
			vertex 30 10 190
			vertex 30 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 190
			vertex 40 0 190
			vertex 40 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 190
			vertex 40 10 190
			vertex 30 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 190
			vertex 40 0 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 190
			vertex 40 10 200
			vertex 40 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 200
			vertex 40 0 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 200
			vertex 40 10 200
			vertex 30 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 200
			vertex 40 0 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 200
			vertex 40 10 200
			vertex 30 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 210
			vertex 40 0 220
			vertex 40 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 210
			vertex 40 10 220
			vertex 40 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 220
			vertex 40 0 230
			vertex 40 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 220
			vertex 40 10 230
			vertex 40 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 230
			vertex 40 0 240
			vertex 40 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 230
			vertex 40 10 240
			vertex 40 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 240
			vertex 40 0 240
			vertex 40 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 240
			vertex 40 10 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 230
			vertex 30 0 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 30 0 230
			vertex 30 10 240
			vertex 30 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 240
			vertex 40 0 240
			vertex 40 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 240
			vertex 40 10 240
			vertex 30 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 250
			vertex 40 0 250
			vertex 40 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 30 0 250
			vertex 40 10 250
			vertex 30 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 0
			vertex 50 0 0
			vertex 50 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 0
			vertex 50 10 0
			vertex 40 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 10
			vertex 50 0 20
			vertex 50 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 10
			vertex 50 10 20
			vertex 50 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 20
			vertex 50 0 30
			vertex 50 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 20
			vertex 50 10 30
			vertex 50 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 30
			vertex 50 0 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 30
			vertex 50 10 40
			vertex 50 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 40
			vertex 50 0 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 40
			vertex 50 10 40
			vertex 40 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 40
			vertex 50 0 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 40
			vertex 50 10 40
			vertex 40 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 50
			vertex 50 0 50
			vertex 50 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 50
			vertex 50 10 50
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 40
			vertex 40 0 50
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 40
			vertex 40 10 50
			vertex 40 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 50
			vertex 50 0 50
			vertex 50 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 50
			vertex 50 10 50
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 50
			vertex 40 0 60
			vertex 40 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 50
			vertex 40 10 60
			vertex 40 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 60
			vertex 50 0 70
			vertex 50 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 60
			vertex 50 10 70
			vertex 50 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 60
			vertex 40 0 70
			vertex 40 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 60
			vertex 40 10 70
			vertex 40 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 70
			vertex 50 0 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 70
			vertex 50 10 80
			vertex 50 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 80
			vertex 50 0 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 80
			vertex 50 10 80
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 80
			vertex 50 0 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 80
			vertex 50 10 80
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 90
			vertex 50 0 90
			vertex 50 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 90
			vertex 50 10 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 80
			vertex 40 0 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 80
			vertex 40 10 90
			vertex 40 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 90
			vertex 50 0 90
			vertex 50 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 90
			vertex 50 10 90
			vertex 40 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 90
			vertex 40 0 100
			vertex 40 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 90
			vertex 40 10 100
			vertex 40 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 110
			vertex 50 0 110
			vertex 50 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 110
			vertex 50 10 110
			vertex 40 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 110
			vertex 50 0 110
			vertex 50 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 110
			vertex 50 10 110
			vertex 40 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 110
			vertex 50 0 120
			vertex 50 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 110
			vertex 50 10 120
			vertex 50 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 110
			vertex 40 0 120
			vertex 40 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 110
			vertex 40 10 120
			vertex 40 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 130
			vertex 50 0 130
			vertex 50 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 130
			vertex 50 10 130
			vertex 40 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 120
			vertex 40 0 130
			vertex 40 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 120
			vertex 40 10 130
			vertex 40 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 130
			vertex 50 0 130
			vertex 50 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 130
			vertex 50 10 130
			vertex 40 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 140
			vertex 50 0 150
			vertex 50 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 140
			vertex 50 10 150
			vertex 50 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 150
			vertex 50 0 150
			vertex 50 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 150
			vertex 50 10 150
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 150
			vertex 50 0 150
			vertex 50 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 150
			vertex 50 10 150
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 160
			vertex 50 0 160
			vertex 50 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 160
			vertex 50 10 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 150
			vertex 40 0 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 150
			vertex 40 10 160
			vertex 40 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 160
			vertex 50 0 160
			vertex 50 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 160
			vertex 50 10 160
			vertex 40 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 170
			vertex 50 0 170
			vertex 50 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 170
			vertex 50 10 170
			vertex 40 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 170
			vertex 50 0 170
			vertex 50 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 170
			vertex 50 10 170
			vertex 40 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 180
			vertex 50 0 180
			vertex 50 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 180
			vertex 50 10 180
			vertex 40 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 180
			vertex 50 0 180
			vertex 50 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 180
			vertex 50 10 180
			vertex 40 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 190
			vertex 50 0 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 190
			vertex 50 10 200
			vertex 50 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 200
			vertex 50 0 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 200
			vertex 50 10 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 190
			vertex 40 0 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 190
			vertex 40 10 200
			vertex 40 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 200
			vertex 50 0 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 200
			vertex 50 10 200
			vertex 40 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 210
			vertex 50 0 220
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 210
			vertex 50 10 220
			vertex 50 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 210
			vertex 40 0 220
			vertex 40 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 210
			vertex 40 10 220
			vertex 40 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 220
			vertex 50 0 230
			vertex 50 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 220
			vertex 50 10 230
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 220
			vertex 40 0 230
			vertex 40 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 220
			vertex 40 10 230
			vertex 40 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 230
			vertex 50 0 240
			vertex 50 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 230
			vertex 50 10 240
			vertex 50 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 230
			vertex 40 0 240
			vertex 40 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 40 0 230
			vertex 40 10 240
			vertex 40 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 250
			vertex 50 0 250
			vertex 50 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 40 0 250
			vertex 50 10 250
			vertex 40 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 0
			vertex 60 0 0
			vertex 60 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 0
			vertex 60 10 0
			vertex 50 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 10
			vertex 60 0 20
			vertex 60 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 10
			vertex 60 10 20
			vertex 60 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 10
			vertex 50 0 20
			vertex 50 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 10
			vertex 50 10 20
			vertex 50 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 20
			vertex 60 0 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 20
			vertex 60 10 30
			vertex 60 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 30
			vertex 60 0 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 30
			vertex 60 10 30
			vertex 50 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 20
			vertex 50 0 30
			vertex 50 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 20
			vertex 50 10 30
			vertex 50 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 30
			vertex 60 0 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 30
			vertex 60 10 30
			vertex 50 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 40
			vertex 60 0 40
			vertex 60 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 40
			vertex 60 10 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 30
			vertex 50 0 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 30
			vertex 50 10 40
			vertex 50 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 40
			vertex 60 0 40
			vertex 60 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 40
			vertex 60 10 40
			vertex 50 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 50
			vertex 60 0 50
			vertex 60 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 50
			vertex 60 10 50
			vertex 50 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 50
			vertex 60 0 50
			vertex 60 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 50
			vertex 60 10 50
			vertex 50 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 50
			vertex 60 0 60
			vertex 60 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 50
			vertex 60 10 60
			vertex 60 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 60
			vertex 60 0 70
			vertex 60 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 60
			vertex 60 10 70
			vertex 60 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 60
			vertex 50 0 70
			vertex 50 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 60
			vertex 50 10 70
			vertex 50 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 80
			vertex 60 0 80
			vertex 60 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 80
			vertex 60 10 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 70
			vertex 50 0 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 70
			vertex 50 10 80
			vertex 50 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 80
			vertex 60 0 80
			vertex 60 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 80
			vertex 60 10 80
			vertex 50 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 90
			vertex 60 0 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 90
			vertex 60 10 100
			vertex 60 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 100
			vertex 60 0 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 100
			vertex 60 10 100
			vertex 50 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 100
			vertex 60 0 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 100
			vertex 60 10 100
			vertex 50 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 110
			vertex 50 0 120
			vertex 50 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 110
			vertex 50 10 120
			vertex 50 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 130
			vertex 60 0 130
			vertex 60 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 130
			vertex 60 10 130
			vertex 50 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 130
			vertex 60 0 130
			vertex 60 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 130
			vertex 60 10 130
			vertex 50 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 140
			vertex 60 0 140
			vertex 60 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 140
			vertex 60 10 140
			vertex 50 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 140
			vertex 60 0 140
			vertex 60 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 140
			vertex 60 10 140
			vertex 50 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 140
			vertex 50 0 150
			vertex 50 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 140
			vertex 50 10 150
			vertex 50 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 150
			vertex 60 0 160
			vertex 60 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 150
			vertex 60 10 160
			vertex 60 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 160
			vertex 60 0 160
			vertex 60 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 160
			vertex 60 10 160
			vertex 50 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 160
			vertex 60 0 160
			vertex 60 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 160
			vertex 60 10 160
			vertex 50 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 170
			vertex 60 0 180
			vertex 60 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 170
			vertex 60 10 180
			vertex 60 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 190
			vertex 60 0 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 190
			vertex 60 10 200
			vertex 60 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 200
			vertex 60 0 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 200
			vertex 60 10 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 190
			vertex 50 0 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 190
			vertex 50 10 200
			vertex 50 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 200
			vertex 60 0 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 200
			vertex 60 10 200
			vertex 50 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 210
			vertex 60 0 210
			vertex 60 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 210
			vertex 60 10 210
			vertex 50 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 210
			vertex 60 0 210
			vertex 60 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 210
			vertex 60 10 210
			vertex 50 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 220
			vertex 60 0 220
			vertex 60 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 220
			vertex 60 10 220
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 210
			vertex 50 0 220
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 210
			vertex 50 10 220
			vertex 50 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 220
			vertex 60 0 220
			vertex 60 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 220
			vertex 60 10 220
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 220
			vertex 60 0 230
			vertex 60 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 220
			vertex 60 10 230
			vertex 60 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 220
			vertex 50 0 230
			vertex 50 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 220
			vertex 50 10 230
			vertex 50 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 230
			vertex 50 0 240
			vertex 50 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 50 0 230
			vertex 50 10 240
			vertex 50 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 250
			vertex 60 0 250
			vertex 60 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 50 0 250
			vertex 60 10 250
			vertex 50 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 0
			vertex 70 0 0
			vertex 70 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 0
			vertex 70 10 0
			vertex 60 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 10
			vertex 70 0 10
			vertex 70 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 10
			vertex 70 10 10
			vertex 60 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 10
			vertex 70 0 10
			vertex 70 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 10
			vertex 70 10 10
			vertex 60 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 10
			vertex 60 0 20
			vertex 60 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 10
			vertex 60 10 20
			vertex 60 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 20
			vertex 70 0 30
			vertex 70 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 20
			vertex 70 10 30
			vertex 70 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 30
			vertex 70 0 30
			vertex 70 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 30
			vertex 70 10 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 20
			vertex 60 0 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 20
			vertex 60 10 30
			vertex 60 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 30
			vertex 70 0 30
			vertex 70 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 30
			vertex 70 10 30
			vertex 60 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 40
			vertex 70 0 40
			vertex 70 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 40
			vertex 70 10 40
			vertex 60 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 40
			vertex 70 0 40
			vertex 70 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 40
			vertex 70 10 40
			vertex 60 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 40
			vertex 70 0 50
			vertex 70 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 40
			vertex 70 10 50
			vertex 70 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 50
			vertex 70 0 60
			vertex 70 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 50
			vertex 70 10 60
			vertex 70 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 50
			vertex 60 0 60
			vertex 60 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 50
			vertex 60 10 60
			vertex 60 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 60
			vertex 60 0 70
			vertex 60 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 60
			vertex 60 10 70
			vertex 60 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 70
			vertex 70 0 80
			vertex 70 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 70
			vertex 70 10 80
			vertex 70 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 80
			vertex 70 0 80
			vertex 70 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 80
			vertex 70 10 80
			vertex 60 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 80
			vertex 70 0 80
			vertex 70 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 80
			vertex 70 10 80
			vertex 60 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 100
			vertex 70 0 100
			vertex 70 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 100
			vertex 70 10 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 90
			vertex 60 0 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 90
			vertex 60 10 100
			vertex 60 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 100
			vertex 70 0 100
			vertex 70 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 100
			vertex 70 10 100
			vertex 60 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 100
			vertex 70 0 110
			vertex 70 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 100
			vertex 70 10 110
			vertex 70 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 110
			vertex 70 0 110
			vertex 70 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 110
			vertex 70 10 110
			vertex 60 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 110
			vertex 70 0 110
			vertex 70 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 110
			vertex 70 10 110
			vertex 60 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 120
			vertex 70 0 120
			vertex 70 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 120
			vertex 70 10 120
			vertex 60 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 120
			vertex 70 0 120
			vertex 70 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 120
			vertex 70 10 120
			vertex 60 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 120
			vertex 70 0 130
			vertex 70 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 120
			vertex 70 10 130
			vertex 70 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 130
			vertex 70 0 130
			vertex 70 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 130
			vertex 70 10 130
			vertex 60 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 130
			vertex 70 0 130
			vertex 70 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 130
			vertex 70 10 130
			vertex 60 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 130
			vertex 70 0 140
			vertex 70 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 130
			vertex 70 10 140
			vertex 70 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 150
			vertex 70 0 160
			vertex 70 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 150
			vertex 70 10 160
			vertex 70 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 150
			vertex 60 0 160
			vertex 60 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 150
			vertex 60 10 160
			vertex 60 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 160
			vertex 70 0 170
			vertex 70 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 160
			vertex 70 10 170
			vertex 70 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 170
			vertex 70 0 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 170
			vertex 70 10 180
			vertex 70 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 180
			vertex 70 0 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 180
			vertex 70 10 180
			vertex 60 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 170
			vertex 60 0 180
			vertex 60 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 170
			vertex 60 10 180
			vertex 60 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 180
			vertex 70 0 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 180
			vertex 70 10 180
			vertex 60 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 180
			vertex 70 0 190
			vertex 70 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 180
			vertex 70 10 190
			vertex 70 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 200
			vertex 70 0 200
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 200
			vertex 70 10 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 190
			vertex 60 0 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 190
			vertex 60 10 200
			vertex 60 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 200
			vertex 70 0 200
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 200
			vertex 70 10 200
			vertex 60 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 200
			vertex 70 0 210
			vertex 70 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 200
			vertex 70 10 210
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 220
			vertex 70 0 220
			vertex 70 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 220
			vertex 70 10 220
			vertex 60 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 220
			vertex 70 0 220
			vertex 70 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 220
			vertex 70 10 220
			vertex 60 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 230
			vertex 70 0 230
			vertex 70 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 230
			vertex 70 10 230
			vertex 60 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 220
			vertex 60 0 230
			vertex 60 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 60 0 220
			vertex 60 10 230
			vertex 60 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 230
			vertex 70 0 230
			vertex 70 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 230
			vertex 70 10 230
			vertex 60 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 240
			vertex 70 0 240
			vertex 70 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 240
			vertex 70 10 240
			vertex 60 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 240
			vertex 70 0 240
			vertex 70 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 240
			vertex 70 10 240
			vertex 60 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 250
			vertex 70 0 250
			vertex 70 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 60 0 250
			vertex 70 10 250
			vertex 60 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 0
			vertex 80 0 0
			vertex 80 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 0
			vertex 80 10 0
			vertex 70 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 20
			vertex 80 0 30
			vertex 80 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 20
			vertex 80 10 30
			vertex 80 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 20
			vertex 70 0 30
			vertex 70 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 20
			vertex 70 10 30
			vertex 70 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 30
			vertex 80 0 40
			vertex 80 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 30
			vertex 80 10 40
			vertex 80 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 40
			vertex 80 0 50
			vertex 80 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 40
			vertex 80 10 50
			vertex 80 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 40
			vertex 70 0 50
			vertex 70 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 40
			vertex 70 10 50
			vertex 70 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 50
			vertex 80 0 60
			vertex 80 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 50
			vertex 80 10 60
			vertex 80 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 60
			vertex 80 0 60
			vertex 80 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 60
			vertex 80 10 60
			vertex 70 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 50
			vertex 70 0 60
			vertex 70 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 50
			vertex 70 10 60
			vertex 70 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 60
			vertex 80 0 60
			vertex 80 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 60
			vertex 80 10 60
			vertex 70 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 60
			vertex 80 0 70
			vertex 80 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 60
			vertex 80 10 70
			vertex 80 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 70
			vertex 70 0 80
			vertex 70 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 70
			vertex 70 10 80
			vertex 70 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 80
			vertex 80 0 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 80
			vertex 80 10 90
			vertex 80 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 90
			vertex 80 0 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 90
			vertex 80 10 90
			vertex 70 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 90
			vertex 80 0 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 90
			vertex 80 10 90
			vertex 70 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 90
			vertex 80 0 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 90
			vertex 80 10 100
			vertex 80 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 100
			vertex 80 0 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 100
			vertex 80 10 100
			vertex 70 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 100
			vertex 80 0 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 100
			vertex 80 10 100
			vertex 70 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 100
			vertex 80 0 110
			vertex 80 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 100
			vertex 80 10 110
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 100
			vertex 70 0 110
			vertex 70 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 100
			vertex 70 10 110
			vertex 70 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 120
			vertex 80 0 120
			vertex 80 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 120
			vertex 80 10 120
			vertex 70 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 120
			vertex 80 0 120
			vertex 80 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 120
			vertex 80 10 120
			vertex 70 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 120
			vertex 80 0 130
			vertex 80 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 120
			vertex 80 10 130
			vertex 80 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 120
			vertex 70 0 130
			vertex 70 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 120
			vertex 70 10 130
			vertex 70 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 130
			vertex 80 0 140
			vertex 80 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 130
			vertex 80 10 140
			vertex 80 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 130
			vertex 70 0 140
			vertex 70 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 130
			vertex 70 10 140
			vertex 70 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 140
			vertex 80 0 150
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 140
			vertex 80 10 150
			vertex 80 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 150
			vertex 80 0 160
			vertex 80 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 150
			vertex 80 10 160
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 150
			vertex 70 0 160
			vertex 70 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 150
			vertex 70 10 160
			vertex 70 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 160
			vertex 70 0 170
			vertex 70 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 160
			vertex 70 10 170
			vertex 70 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 170
			vertex 80 0 180
			vertex 80 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 170
			vertex 80 10 180
			vertex 80 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 180
			vertex 80 0 180
			vertex 80 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 180
			vertex 80 10 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 170
			vertex 70 0 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 170
			vertex 70 10 180
			vertex 70 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 180
			vertex 80 0 180
			vertex 80 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 180
			vertex 80 10 180
			vertex 70 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 190
			vertex 80 0 190
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 190
			vertex 80 10 190
			vertex 70 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 180
			vertex 70 0 190
			vertex 70 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 180
			vertex 70 10 190
			vertex 70 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 190
			vertex 80 0 190
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 190
			vertex 80 10 190
			vertex 70 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 190
			vertex 80 0 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 190
			vertex 80 10 200
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 200
			vertex 80 0 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 200
			vertex 80 10 200
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 200
			vertex 80 0 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 200
			vertex 80 10 200
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 210
			vertex 80 0 210
			vertex 80 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 210
			vertex 80 10 210
			vertex 70 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 200
			vertex 70 0 210
			vertex 70 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 70 0 200
			vertex 70 10 210
			vertex 70 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 210
			vertex 80 0 210
			vertex 80 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 210
			vertex 80 10 210
			vertex 70 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 220
			vertex 80 0 230
			vertex 80 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 220
			vertex 80 10 230
			vertex 80 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 230
			vertex 80 0 230
			vertex 80 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 230
			vertex 80 10 230
			vertex 70 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 230
			vertex 80 0 230
			vertex 80 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 230
			vertex 80 10 230
			vertex 70 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 230
			vertex 80 0 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 230
			vertex 80 10 240
			vertex 80 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 240
			vertex 80 0 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 240
			vertex 80 10 240
			vertex 70 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 240
			vertex 80 0 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 240
			vertex 80 10 240
			vertex 70 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 250
			vertex 80 0 250
			vertex 80 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 70 0 250
			vertex 80 10 250
			vertex 70 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 0
			vertex 90 0 0
			vertex 90 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 0
			vertex 90 10 0
			vertex 80 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 0
			vertex 90 0 10
			vertex 90 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 0
			vertex 90 10 10
			vertex 90 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 10
			vertex 90 0 10
			vertex 90 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 10
			vertex 90 10 10
			vertex 80 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 10
			vertex 90 0 10
			vertex 90 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 10
			vertex 90 10 10
			vertex 80 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 10
			vertex 90 0 20
			vertex 90 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 10
			vertex 90 10 20
			vertex 90 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 20
			vertex 90 0 30
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 20
			vertex 90 10 30
			vertex 90 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 20
			vertex 80 0 30
			vertex 80 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 20
			vertex 80 10 30
			vertex 80 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 30
			vertex 90 0 40
			vertex 90 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 30
			vertex 90 10 40
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 30
			vertex 80 0 40
			vertex 80 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 30
			vertex 80 10 40
			vertex 80 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 40
			vertex 80 0 50
			vertex 80 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 40
			vertex 80 10 50
			vertex 80 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 50
			vertex 90 0 60
			vertex 90 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 50
			vertex 90 10 60
			vertex 90 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 50
			vertex 80 0 60
			vertex 80 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 50
			vertex 80 10 60
			vertex 80 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 60
			vertex 90 0 70
			vertex 90 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 60
			vertex 90 10 70
			vertex 90 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 60
			vertex 80 0 70
			vertex 80 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 60
			vertex 80 10 70
			vertex 80 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 90
			vertex 90 0 90
			vertex 90 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 90
			vertex 90 10 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 80
			vertex 80 0 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 80
			vertex 80 10 90
			vertex 80 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 90
			vertex 90 0 90
			vertex 90 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 90
			vertex 90 10 90
			vertex 80 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 100
			vertex 90 0 100
			vertex 90 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 100
			vertex 90 10 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 90
			vertex 80 0 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 90
			vertex 80 10 100
			vertex 80 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 100
			vertex 90 0 100
			vertex 90 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 100
			vertex 90 10 100
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 100
			vertex 80 0 110
			vertex 80 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 100
			vertex 80 10 110
			vertex 80 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 110
			vertex 90 0 120
			vertex 90 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 110
			vertex 90 10 120
			vertex 90 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 120
			vertex 90 0 130
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 120
			vertex 90 10 130
			vertex 90 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 120
			vertex 80 0 130
			vertex 80 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 120
			vertex 80 10 130
			vertex 80 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 130
			vertex 90 0 140
			vertex 90 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 130
			vertex 90 10 140
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 130
			vertex 80 0 140
			vertex 80 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 130
			vertex 80 10 140
			vertex 80 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 140
			vertex 90 0 150
			vertex 90 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 140
			vertex 90 10 150
			vertex 90 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 150
			vertex 90 0 150
			vertex 90 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 150
			vertex 90 10 150
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 140
			vertex 80 0 150
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 140
			vertex 80 10 150
			vertex 80 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 150
			vertex 90 0 150
			vertex 90 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 150
			vertex 90 10 150
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 150
			vertex 90 0 160
			vertex 90 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 150
			vertex 90 10 160
			vertex 90 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 150
			vertex 80 0 160
			vertex 80 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 150
			vertex 80 10 160
			vertex 80 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 160
			vertex 90 0 170
			vertex 90 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 160
			vertex 90 10 170
			vertex 90 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 170
			vertex 80 0 180
			vertex 80 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 170
			vertex 80 10 180
			vertex 80 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 180
			vertex 90 0 190
			vertex 90 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 180
			vertex 90 10 190
			vertex 90 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 190
			vertex 90 0 190
			vertex 90 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 190
			vertex 90 10 190
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 190
			vertex 90 0 190
			vertex 90 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 190
			vertex 90 10 190
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 200
			vertex 90 0 200
			vertex 90 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 200
			vertex 90 10 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 190
			vertex 80 0 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 190
			vertex 80 10 200
			vertex 80 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 200
			vertex 90 0 200
			vertex 90 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 200
			vertex 90 10 200
			vertex 80 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 200
			vertex 90 0 210
			vertex 90 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 200
			vertex 90 10 210
			vertex 90 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 210
			vertex 90 0 220
			vertex 90 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 210
			vertex 90 10 220
			vertex 90 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 220
			vertex 90 0 220
			vertex 90 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 220
			vertex 90 10 220
			vertex 80 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 220
			vertex 90 0 220
			vertex 90 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 220
			vertex 90 10 220
			vertex 80 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 220
			vertex 90 0 230
			vertex 90 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 220
			vertex 90 10 230
			vertex 90 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 220
			vertex 80 0 230
			vertex 80 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 220
			vertex 80 10 230
			vertex 80 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 240
			vertex 90 0 240
			vertex 90 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 240
			vertex 90 10 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 230
			vertex 80 0 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 80 0 230
			vertex 80 10 240
			vertex 80 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 240
			vertex 90 0 240
			vertex 90 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 240
			vertex 90 10 240
			vertex 80 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 250
			vertex 90 0 250
			vertex 90 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 80 0 250
			vertex 90 10 250
			vertex 80 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 0
			vertex 100 0 0
			vertex 100 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 0
			vertex 100 10 0
			vertex 90 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 0
			vertex 90 0 10
			vertex 90 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 0
			vertex 90 10 10
			vertex 90 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 10
			vertex 90 0 20
			vertex 90 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 10
			vertex 90 10 20
			vertex 90 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 20
			vertex 100 0 30
			vertex 100 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 20
			vertex 100 10 30
			vertex 100 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 30
			vertex 100 0 30
			vertex 100 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 30
			vertex 100 10 30
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 20
			vertex 90 0 30
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 20
			vertex 90 10 30
			vertex 90 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 30
			vertex 100 0 30
			vertex 100 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 30
			vertex 100 10 30
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 30
			vertex 90 0 40
			vertex 90 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 30
			vertex 90 10 40
			vertex 90 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 40
			vertex 100 0 50
			vertex 100 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 40
			vertex 100 10 50
			vertex 100 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 50
			vertex 100 0 60
			vertex 100 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 50
			vertex 100 10 60
			vertex 100 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 50
			vertex 90 0 60
			vertex 90 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 50
			vertex 90 10 60
			vertex 90 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 60
			vertex 100 0 70
			vertex 100 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 60
			vertex 100 10 70
			vertex 100 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 70
			vertex 100 0 70
			vertex 100 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 70
			vertex 100 10 70
			vertex 90 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 60
			vertex 90 0 70
			vertex 90 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 60
			vertex 90 10 70
			vertex 90 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 70
			vertex 100 0 70
			vertex 100 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 70
			vertex 100 10 70
			vertex 90 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 80
			vertex 100 0 80
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 80
			vertex 100 10 80
			vertex 90 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 80
			vertex 100 0 80
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 80
			vertex 100 10 80
			vertex 90 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 80
			vertex 100 0 90
			vertex 100 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 80
			vertex 100 10 90
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 100
			vertex 100 0 100
			vertex 100 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 100
			vertex 100 10 100
			vertex 90 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 100
			vertex 100 0 100
			vertex 100 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 100
			vertex 100 10 100
			vertex 90 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 100
			vertex 100 0 110
			vertex 100 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 100
			vertex 100 10 110
			vertex 100 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 110
			vertex 100 0 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 110
			vertex 100 10 120
			vertex 100 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 120
			vertex 100 0 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 120
			vertex 100 10 120
			vertex 90 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 110
			vertex 90 0 120
			vertex 90 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 110
			vertex 90 10 120
			vertex 90 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 120
			vertex 100 0 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 120
			vertex 100 10 120
			vertex 90 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 130
			vertex 100 0 130
			vertex 100 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 130
			vertex 100 10 130
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 120
			vertex 90 0 130
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 120
			vertex 90 10 130
			vertex 90 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 130
			vertex 100 0 130
			vertex 100 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 130
			vertex 100 10 130
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 130
			vertex 100 0 140
			vertex 100 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 130
			vertex 100 10 140
			vertex 100 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 130
			vertex 90 0 140
			vertex 90 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 130
			vertex 90 10 140
			vertex 90 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 140
			vertex 90 0 150
			vertex 90 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 140
			vertex 90 10 150
			vertex 90 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 150
			vertex 100 0 160
			vertex 100 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 150
			vertex 100 10 160
			vertex 100 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 150
			vertex 90 0 160
			vertex 90 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 150
			vertex 90 10 160
			vertex 90 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 160
			vertex 100 0 170
			vertex 100 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 160
			vertex 100 10 170
			vertex 100 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 160
			vertex 90 0 170
			vertex 90 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 160
			vertex 90 10 170
			vertex 90 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 180
			vertex 100 0 180
			vertex 100 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 180
			vertex 100 10 180
			vertex 90 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 180
			vertex 100 0 180
			vertex 100 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 180
			vertex 100 10 180
			vertex 90 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 180
			vertex 90 0 190
			vertex 90 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 180
			vertex 90 10 190
			vertex 90 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 200
			vertex 100 0 210
			vertex 100 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 200
			vertex 100 10 210
			vertex 100 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 200
			vertex 90 0 210
			vertex 90 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 200
			vertex 90 10 210
			vertex 90 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 210
			vertex 100 0 220
			vertex 100 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 210
			vertex 100 10 220
			vertex 100 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 210
			vertex 90 0 220
			vertex 90 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 210
			vertex 90 10 220
			vertex 90 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 220
			vertex 100 0 230
			vertex 100 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 220
			vertex 100 10 230
			vertex 100 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 230
			vertex 100 0 230
			vertex 100 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 230
			vertex 100 10 230
			vertex 90 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 220
			vertex 90 0 230
			vertex 90 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 90 0 220
			vertex 90 10 230
			vertex 90 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 230
			vertex 100 0 230
			vertex 100 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 230
			vertex 100 10 230
			vertex 90 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 240
			vertex 100 0 250
			vertex 100 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 240
			vertex 100 10 250
			vertex 100 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 250
			vertex 100 0 250
			vertex 100 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 90 0 250
			vertex 100 10 250
			vertex 90 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 0
			vertex 110 0 0
			vertex 110 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 0
			vertex 110 10 0
			vertex 100 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 10
			vertex 110 0 10
			vertex 110 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 10
			vertex 110 10 10
			vertex 100 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 10
			vertex 110 0 10
			vertex 110 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 10
			vertex 110 10 10
			vertex 100 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 20
			vertex 110 0 20
			vertex 110 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 20
			vertex 110 10 20
			vertex 100 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 20
			vertex 110 0 20
			vertex 110 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 20
			vertex 110 10 20
			vertex 100 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 20
			vertex 110 0 30
			vertex 110 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 20
			vertex 110 10 30
			vertex 110 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 20
			vertex 100 0 30
			vertex 100 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 20
			vertex 100 10 30
			vertex 100 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 30
			vertex 110 0 40
			vertex 110 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 30
			vertex 110 10 40
			vertex 110 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 40
			vertex 100 0 50
			vertex 100 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 40
			vertex 100 10 50
			vertex 100 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 60
			vertex 110 0 60
			vertex 110 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 60
			vertex 110 10 60
			vertex 100 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 50
			vertex 100 0 60
			vertex 100 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 50
			vertex 100 10 60
			vertex 100 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 60
			vertex 110 0 60
			vertex 110 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 60
			vertex 110 10 60
			vertex 100 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 60
			vertex 110 0 70
			vertex 110 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 60
			vertex 110 10 70
			vertex 110 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 60
			vertex 100 0 70
			vertex 100 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 60
			vertex 100 10 70
			vertex 100 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 70
			vertex 110 0 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 70
			vertex 110 10 80
			vertex 110 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 80
			vertex 110 0 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 80
			vertex 110 10 80
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 80
			vertex 110 0 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 80
			vertex 110 10 80
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 90
			vertex 110 0 90
			vertex 110 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 90
			vertex 110 10 90
			vertex 100 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 80
			vertex 100 0 90
			vertex 100 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 80
			vertex 100 10 90
			vertex 100 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 90
			vertex 110 0 90
			vertex 110 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 90
			vertex 110 10 90
			vertex 100 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 90
			vertex 110 0 100
			vertex 110 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 90
			vertex 110 10 100
			vertex 110 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 100
			vertex 110 0 110
			vertex 110 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 100
			vertex 110 10 110
			vertex 110 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 100
			vertex 100 0 110
			vertex 100 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 100
			vertex 100 10 110
			vertex 100 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 110
			vertex 110 0 120
			vertex 110 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 110
			vertex 110 10 120
			vertex 110 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 120
			vertex 110 0 120
			vertex 110 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 120
			vertex 110 10 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 110
			vertex 100 0 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 110
			vertex 100 10 120
			vertex 100 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 120
			vertex 110 0 120
			vertex 110 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 120
			vertex 110 10 120
			vertex 100 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 130
			vertex 110 0 130
			vertex 110 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 130
			vertex 110 10 130
			vertex 100 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 130
			vertex 110 0 130
			vertex 110 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 130
			vertex 110 10 130
			vertex 100 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 130
			vertex 110 0 140
			vertex 110 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 130
			vertex 110 10 140
			vertex 110 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 130
			vertex 100 0 140
			vertex 100 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 130
			vertex 100 10 140
			vertex 100 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 150
			vertex 110 0 150
			vertex 110 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 150
			vertex 110 10 150
			vertex 100 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 150
			vertex 110 0 150
			vertex 110 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 150
			vertex 110 10 150
			vertex 100 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 150
			vertex 110 0 160
			vertex 110 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 150
			vertex 110 10 160
			vertex 110 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 150
			vertex 100 0 160
			vertex 100 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 150
			vertex 100 10 160
			vertex 100 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 170
			vertex 110 0 170
			vertex 110 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 170
			vertex 110 10 170
			vertex 100 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 160
			vertex 100 0 170
			vertex 100 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 160
			vertex 100 10 170
			vertex 100 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 170
			vertex 110 0 170
			vertex 110 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 170
			vertex 110 10 170
			vertex 100 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 170
			vertex 110 0 180
			vertex 110 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 170
			vertex 110 10 180
			vertex 110 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 190
			vertex 110 0 190
			vertex 110 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 190
			vertex 110 10 190
			vertex 100 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 190
			vertex 110 0 190
			vertex 110 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 190
			vertex 110 10 190
			vertex 100 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 200
			vertex 110 0 200
			vertex 110 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 200
			vertex 110 10 200
			vertex 100 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 200
			vertex 110 0 200
			vertex 110 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 200
			vertex 110 10 200
			vertex 100 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 200
			vertex 100 0 210
			vertex 100 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 200
			vertex 100 10 210
			vertex 100 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 220
			vertex 110 0 220
			vertex 110 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 220
			vertex 110 10 220
			vertex 100 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 210
			vertex 100 0 220
			vertex 100 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 210
			vertex 100 10 220
			vertex 100 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 220
			vertex 110 0 220
			vertex 110 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 220
			vertex 110 10 220
			vertex 100 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 220
			vertex 100 0 230
			vertex 100 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 220
			vertex 100 10 230
			vertex 100 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 230
			vertex 110 0 240
			vertex 110 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 230
			vertex 110 10 240
			vertex 110 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 240
			vertex 110 0 240
			vertex 110 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 240
			vertex 110 10 240
			vertex 100 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 240
			vertex 110 0 240
			vertex 110 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 240
			vertex 110 10 240
			vertex 100 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 250
			vertex 110 0 250
			vertex 110 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 100 0 250
			vertex 110 10 250
			vertex 100 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 240
			vertex 100 0 250
			vertex 100 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 100 0 240
			vertex 100 10 250
			vertex 100 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 0
			vertex 120 0 0
			vertex 120 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 0
			vertex 120 10 0
			vertex 110 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 10
			vertex 120 0 10
			vertex 120 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 10
			vertex 120 10 10
			vertex 110 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 10
			vertex 120 0 10
			vertex 120 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 10
			vertex 120 10 10
			vertex 110 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 20
			vertex 120 0 20
			vertex 120 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 20
			vertex 120 10 20
			vertex 110 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 20
			vertex 120 0 20
			vertex 120 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 20
			vertex 120 10 20
			vertex 110 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 20
			vertex 110 0 30
			vertex 110 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 20
			vertex 110 10 30
			vertex 110 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 30
			vertex 110 0 40
			vertex 110 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 30
			vertex 110 10 40
			vertex 110 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 40
			vertex 120 0 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 40
			vertex 120 10 50
			vertex 120 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 50
			vertex 120 0 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 50
			vertex 120 10 50
			vertex 110 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 50
			vertex 120 0 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 50
			vertex 120 10 50
			vertex 110 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 60
			vertex 120 0 60
			vertex 120 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 60
			vertex 120 10 60
			vertex 110 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 60
			vertex 120 0 60
			vertex 120 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 60
			vertex 120 10 60
			vertex 110 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 60
			vertex 120 0 70
			vertex 120 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 60
			vertex 120 10 70
			vertex 120 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 60
			vertex 110 0 70
			vertex 110 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 60
			vertex 110 10 70
			vertex 110 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 80
			vertex 120 0 80
			vertex 120 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 80
			vertex 120 10 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 70
			vertex 110 0 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 70
			vertex 110 10 80
			vertex 110 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 80
			vertex 120 0 80
			vertex 120 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 80
			vertex 120 10 80
			vertex 110 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 80
			vertex 120 0 90
			vertex 120 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 80
			vertex 120 10 90
			vertex 120 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 90
			vertex 120 0 100
			vertex 120 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 90
			vertex 120 10 100
			vertex 120 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 90
			vertex 110 0 100
			vertex 110 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 90
			vertex 110 10 100
			vertex 110 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 100
			vertex 110 0 110
			vertex 110 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 100
			vertex 110 10 110
			vertex 110 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 110
			vertex 120 0 120
			vertex 120 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 110
			vertex 120 10 120
			vertex 120 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 110
			vertex 110 0 120
			vertex 110 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 110
			vertex 110 10 120
			vertex 110 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 130
			vertex 110 0 140
			vertex 110 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 130
			vertex 110 10 140
			vertex 110 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 140
			vertex 120 0 150
			vertex 120 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 140
			vertex 120 10 150
			vertex 120 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 150
			vertex 120 0 150
			vertex 120 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 150
			vertex 120 10 150
			vertex 110 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 150
			vertex 120 0 150
			vertex 120 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 150
			vertex 120 10 150
			vertex 110 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 150
			vertex 120 0 160
			vertex 120 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 150
			vertex 120 10 160
			vertex 120 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 150
			vertex 110 0 160
			vertex 110 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 150
			vertex 110 10 160
			vertex 110 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 170
			vertex 120 0 170
			vertex 120 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 170
			vertex 120 10 170
			vertex 110 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 170
			vertex 120 0 170
			vertex 120 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 170
			vertex 120 10 170
			vertex 110 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 170
			vertex 120 0 180
			vertex 120 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 170
			vertex 120 10 180
			vertex 120 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 170
			vertex 110 0 180
			vertex 110 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 170
			vertex 110 10 180
			vertex 110 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 180
			vertex 120 0 190
			vertex 120 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 180
			vertex 120 10 190
			vertex 120 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 190
			vertex 120 0 190
			vertex 120 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 190
			vertex 120 10 190
			vertex 110 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 190
			vertex 120 0 190
			vertex 120 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 190
			vertex 120 10 190
			vertex 110 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 200
			vertex 120 0 200
			vertex 120 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 200
			vertex 120 10 200
			vertex 110 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 200
			vertex 120 0 200
			vertex 120 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 200
			vertex 120 10 200
			vertex 110 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 200
			vertex 120 0 210
			vertex 120 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 200
			vertex 120 10 210
			vertex 120 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 210
			vertex 120 0 210
			vertex 120 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 210
			vertex 120 10 210
			vertex 110 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 210
			vertex 120 0 210
			vertex 120 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 210
			vertex 120 10 210
			vertex 110 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 220
			vertex 120 0 230
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 220
			vertex 120 10 230
			vertex 120 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 230
			vertex 120 0 240
			vertex 120 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 230
			vertex 120 10 240
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 230
			vertex 110 0 240
			vertex 110 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 110 0 230
			vertex 110 10 240
			vertex 110 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 250
			vertex 120 0 250
			vertex 120 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 110 0 250
			vertex 120 10 250
			vertex 110 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 0
			vertex 130 0 0
			vertex 130 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 0
			vertex 130 10 0
			vertex 120 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 0
			vertex 130 0 10
			vertex 130 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 0
			vertex 130 10 10
			vertex 130 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 10
			vertex 130 0 10
			vertex 130 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 10
			vertex 130 10 10
			vertex 120 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 10
			vertex 130 0 10
			vertex 130 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 10
			vertex 130 10 10
			vertex 120 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 20
			vertex 130 0 30
			vertex 130 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 20
			vertex 130 10 30
			vertex 130 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 30
			vertex 130 0 30
			vertex 130 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 30
			vertex 130 10 30
			vertex 120 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 30
			vertex 130 0 30
			vertex 130 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 30
			vertex 130 10 30
			vertex 120 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 30
			vertex 130 0 40
			vertex 130 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 30
			vertex 130 10 40
			vertex 130 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 50
			vertex 130 0 50
			vertex 130 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 50
			vertex 130 10 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 40
			vertex 120 0 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 40
			vertex 120 10 50
			vertex 120 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 50
			vertex 130 0 50
			vertex 130 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 50
			vertex 130 10 50
			vertex 120 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 60
			vertex 130 0 60
			vertex 130 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 60
			vertex 130 10 60
			vertex 120 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 60
			vertex 130 0 60
			vertex 130 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 60
			vertex 130 10 60
			vertex 120 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 60
			vertex 120 0 70
			vertex 120 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 60
			vertex 120 10 70
			vertex 120 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 70
			vertex 130 0 80
			vertex 130 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 70
			vertex 130 10 80
			vertex 130 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 80
			vertex 130 0 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 80
			vertex 130 10 90
			vertex 130 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 90
			vertex 130 0 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 90
			vertex 130 10 90
			vertex 120 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 80
			vertex 120 0 90
			vertex 120 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 80
			vertex 120 10 90
			vertex 120 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 90
			vertex 130 0 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 90
			vertex 130 10 90
			vertex 120 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 100
			vertex 130 0 100
			vertex 130 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 100
			vertex 130 10 100
			vertex 120 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 90
			vertex 120 0 100
			vertex 120 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 90
			vertex 120 10 100
			vertex 120 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 100
			vertex 130 0 100
			vertex 130 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 100
			vertex 130 10 100
			vertex 120 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 100
			vertex 130 0 110
			vertex 130 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 100
			vertex 130 10 110
			vertex 130 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 110
			vertex 130 0 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 110
			vertex 130 10 120
			vertex 130 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 120
			vertex 130 0 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 120
			vertex 130 10 120
			vertex 120 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 110
			vertex 120 0 120
			vertex 120 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 110
			vertex 120 10 120
			vertex 120 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 120
			vertex 130 0 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 120
			vertex 130 10 120
			vertex 120 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 130
			vertex 130 0 130
			vertex 130 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 130
			vertex 130 10 130
			vertex 120 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 130
			vertex 130 0 130
			vertex 130 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 130
			vertex 130 10 130
			vertex 120 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 130
			vertex 130 0 140
			vertex 130 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 130
			vertex 130 10 140
			vertex 130 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 140
			vertex 130 0 150
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 140
			vertex 130 10 150
			vertex 130 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 140
			vertex 120 0 150
			vertex 120 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 140
			vertex 120 10 150
			vertex 120 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 150
			vertex 130 0 160
			vertex 130 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 150
			vertex 130 10 160
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 150
			vertex 120 0 160
			vertex 120 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 150
			vertex 120 10 160
			vertex 120 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 160
			vertex 130 0 170
			vertex 130 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 160
			vertex 130 10 170
			vertex 130 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 170
			vertex 130 0 170
			vertex 130 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 170
			vertex 130 10 170
			vertex 120 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 170
			vertex 130 0 170
			vertex 130 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 170
			vertex 130 10 170
			vertex 120 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 180
			vertex 130 0 180
			vertex 130 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 180
			vertex 130 10 180
			vertex 120 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 170
			vertex 120 0 180
			vertex 120 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 170
			vertex 120 10 180
			vertex 120 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 180
			vertex 130 0 180
			vertex 130 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 180
			vertex 130 10 180
			vertex 120 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 180
			vertex 130 0 190
			vertex 130 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 180
			vertex 130 10 190
			vertex 130 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 180
			vertex 120 0 190
			vertex 120 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 180
			vertex 120 10 190
			vertex 120 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 200
			vertex 130 0 200
			vertex 130 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 200
			vertex 130 10 200
			vertex 120 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 200
			vertex 130 0 200
			vertex 130 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 200
			vertex 130 10 200
			vertex 120 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 200
			vertex 130 0 210
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 200
			vertex 130 10 210
			vertex 130 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 200
			vertex 120 0 210
			vertex 120 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 200
			vertex 120 10 210
			vertex 120 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 210
			vertex 130 0 220
			vertex 130 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 210
			vertex 130 10 220
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 220
			vertex 130 0 230
			vertex 130 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 220
			vertex 130 10 230
			vertex 130 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 230
			vertex 130 0 230
			vertex 130 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 230
			vertex 130 10 230
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 220
			vertex 120 0 230
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 220
			vertex 120 10 230
			vertex 120 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 230
			vertex 130 0 230
			vertex 130 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 230
			vertex 130 10 230
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 230
			vertex 120 0 240
			vertex 120 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 120 0 230
			vertex 120 10 240
			vertex 120 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 240
			vertex 130 0 250
			vertex 130 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 240
			vertex 130 10 250
			vertex 130 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 250
			vertex 130 0 250
			vertex 130 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 120 0 250
			vertex 130 10 250
			vertex 120 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 0
			vertex 140 0 0
			vertex 140 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 0
			vertex 140 10 0
			vertex 130 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 0
			vertex 140 0 10
			vertex 140 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 0
			vertex 140 10 10
			vertex 140 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 0
			vertex 130 0 10
			vertex 130 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 0
			vertex 130 10 10
			vertex 130 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 20
			vertex 140 0 30
			vertex 140 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 20
			vertex 140 10 30
			vertex 140 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 20
			vertex 130 0 30
			vertex 130 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 20
			vertex 130 10 30
			vertex 130 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 40
			vertex 140 0 40
			vertex 140 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 40
			vertex 140 10 40
			vertex 130 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 30
			vertex 130 0 40
			vertex 130 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 30
			vertex 130 10 40
			vertex 130 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 40
			vertex 140 0 40
			vertex 140 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 40
			vertex 140 10 40
			vertex 130 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 50
			vertex 140 0 50
			vertex 140 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 50
			vertex 140 10 50
			vertex 130 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 50
			vertex 140 0 50
			vertex 140 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 50
			vertex 140 10 50
			vertex 130 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 50
			vertex 140 0 60
			vertex 140 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 50
			vertex 140 10 60
			vertex 140 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 70
			vertex 140 0 80
			vertex 140 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 70
			vertex 140 10 80
			vertex 140 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 70
			vertex 130 0 80
			vertex 130 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 70
			vertex 130 10 80
			vertex 130 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 90
			vertex 140 0 90
			vertex 140 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 90
			vertex 140 10 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 80
			vertex 130 0 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 80
			vertex 130 10 90
			vertex 130 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 90
			vertex 140 0 90
			vertex 140 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 90
			vertex 140 10 90
			vertex 130 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 100
			vertex 140 0 110
			vertex 140 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 100
			vertex 140 10 110
			vertex 140 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 100
			vertex 130 0 110
			vertex 130 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 100
			vertex 130 10 110
			vertex 130 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 120
			vertex 140 0 120
			vertex 140 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 120
			vertex 140 10 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 110
			vertex 130 0 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 110
			vertex 130 10 120
			vertex 130 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 120
			vertex 140 0 120
			vertex 140 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 120
			vertex 140 10 120
			vertex 130 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 130
			vertex 140 0 140
			vertex 140 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 130
			vertex 140 10 140
			vertex 140 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 130
			vertex 130 0 140
			vertex 130 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 130
			vertex 130 10 140
			vertex 130 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 140
			vertex 140 0 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 140
			vertex 140 10 150
			vertex 140 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 150
			vertex 140 0 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 150
			vertex 140 10 150
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 140
			vertex 130 0 150
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 140
			vertex 130 10 150
			vertex 130 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 150
			vertex 140 0 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 150
			vertex 140 10 150
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 150
			vertex 130 0 160
			vertex 130 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 150
			vertex 130 10 160
			vertex 130 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 160
			vertex 130 0 170
			vertex 130 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 160
			vertex 130 10 170
			vertex 130 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 180
			vertex 140 0 180
			vertex 140 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 180
			vertex 140 10 180
			vertex 130 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 180
			vertex 140 0 180
			vertex 140 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 180
			vertex 140 10 180
			vertex 130 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 180
			vertex 130 0 190
			vertex 130 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 180
			vertex 130 10 190
			vertex 130 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 190
			vertex 140 0 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 190
			vertex 140 10 200
			vertex 140 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 200
			vertex 140 0 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 200
			vertex 140 10 200
			vertex 130 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 200
			vertex 140 0 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 200
			vertex 140 10 200
			vertex 130 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 210
			vertex 140 0 210
			vertex 140 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 210
			vertex 140 10 210
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 200
			vertex 130 0 210
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 200
			vertex 130 10 210
			vertex 130 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 210
			vertex 140 0 210
			vertex 140 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 210
			vertex 140 10 210
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 210
			vertex 130 0 220
			vertex 130 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 210
			vertex 130 10 220
			vertex 130 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 220
			vertex 140 0 230
			vertex 140 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 220
			vertex 140 10 230
			vertex 140 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 220
			vertex 130 0 230
			vertex 130 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 220
			vertex 130 10 230
			vertex 130 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 230
			vertex 140 0 240
			vertex 140 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 230
			vertex 140 10 240
			vertex 140 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 250
			vertex 140 0 250
			vertex 140 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 130 0 250
			vertex 140 10 250
			vertex 130 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 240
			vertex 130 0 250
			vertex 130 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 130 0 240
			vertex 130 10 250
			vertex 130 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 0
			vertex 150 0 0
			vertex 150 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 0
			vertex 150 10 0
			vertex 140 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 10
			vertex 150 0 10
			vertex 150 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 10
			vertex 150 10 10
			vertex 140 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 0
			vertex 140 0 10
			vertex 140 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 0
			vertex 140 10 10
			vertex 140 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 10
			vertex 150 0 10
			vertex 150 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 10
			vertex 150 10 10
			vertex 140 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 20
			vertex 150 0 20
			vertex 150 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 20
			vertex 150 10 20
			vertex 140 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 20
			vertex 150 0 20
			vertex 150 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 20
			vertex 150 10 20
			vertex 140 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 30
			vertex 150 0 30
			vertex 150 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 30
			vertex 150 10 30
			vertex 140 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 20
			vertex 140 0 30
			vertex 140 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 20
			vertex 140 10 30
			vertex 140 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 30
			vertex 150 0 30
			vertex 150 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 30
			vertex 150 10 30
			vertex 140 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 30
			vertex 150 0 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 30
			vertex 150 10 40
			vertex 150 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 40
			vertex 150 0 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 40
			vertex 150 10 40
			vertex 140 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 40
			vertex 150 0 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 40
			vertex 150 10 40
			vertex 140 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 40
			vertex 150 0 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 40
			vertex 150 10 50
			vertex 150 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 50
			vertex 150 0 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 50
			vertex 150 10 50
			vertex 140 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 50
			vertex 150 0 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 50
			vertex 150 10 50
			vertex 140 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 50
			vertex 150 0 60
			vertex 150 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 50
			vertex 150 10 60
			vertex 150 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 50
			vertex 140 0 60
			vertex 140 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 50
			vertex 140 10 60
			vertex 140 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 60
			vertex 150 0 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 60
			vertex 150 10 70
			vertex 150 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 70
			vertex 150 0 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 70
			vertex 150 10 70
			vertex 140 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 70
			vertex 150 0 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 70
			vertex 150 10 70
			vertex 140 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 70
			vertex 140 0 80
			vertex 140 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 70
			vertex 140 10 80
			vertex 140 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 90
			vertex 150 0 100
			vertex 150 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 90
			vertex 150 10 100
			vertex 150 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 100
			vertex 150 0 100
			vertex 150 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 100
			vertex 150 10 100
			vertex 140 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 100
			vertex 150 0 100
			vertex 150 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 100
			vertex 150 10 100
			vertex 140 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 110
			vertex 150 0 110
			vertex 150 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 110
			vertex 150 10 110
			vertex 140 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 100
			vertex 140 0 110
			vertex 140 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 100
			vertex 140 10 110
			vertex 140 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 110
			vertex 150 0 110
			vertex 150 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 110
			vertex 150 10 110
			vertex 140 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 130
			vertex 150 0 140
			vertex 150 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 130
			vertex 150 10 140
			vertex 150 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 140
			vertex 150 0 140
			vertex 150 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 140
			vertex 150 10 140
			vertex 140 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 130
			vertex 140 0 140
			vertex 140 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 130
			vertex 140 10 140
			vertex 140 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 140
			vertex 150 0 140
			vertex 150 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 140
			vertex 150 10 140
			vertex 140 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 150
			vertex 150 0 150
			vertex 150 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 150
			vertex 150 10 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 140
			vertex 140 0 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 140
			vertex 140 10 150
			vertex 140 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 150
			vertex 150 0 150
			vertex 150 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 150
			vertex 150 10 150
			vertex 140 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 150
			vertex 150 0 160
			vertex 150 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 150
			vertex 150 10 160
			vertex 150 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 160
			vertex 150 0 160
			vertex 150 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 160
			vertex 150 10 160
			vertex 140 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 160
			vertex 150 0 160
			vertex 150 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 160
			vertex 150 10 160
			vertex 140 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 170
			vertex 150 0 170
			vertex 150 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 170
			vertex 150 10 170
			vertex 140 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 170
			vertex 150 0 170
			vertex 150 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 170
			vertex 150 10 170
			vertex 140 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 180
			vertex 150 0 190
			vertex 150 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 180
			vertex 150 10 190
			vertex 150 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 190
			vertex 150 0 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 190
			vertex 150 10 200
			vertex 150 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 200
			vertex 150 0 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 200
			vertex 150 10 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 190
			vertex 140 0 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 190
			vertex 140 10 200
			vertex 140 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 200
			vertex 150 0 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 200
			vertex 150 10 200
			vertex 140 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 200
			vertex 150 0 210
			vertex 150 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 200
			vertex 150 10 210
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 210
			vertex 150 0 220
			vertex 150 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 210
			vertex 150 10 220
			vertex 150 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 220
			vertex 150 0 220
			vertex 150 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 220
			vertex 150 10 220
			vertex 140 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 220
			vertex 150 0 220
			vertex 150 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 220
			vertex 150 10 220
			vertex 140 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 230
			vertex 150 0 230
			vertex 150 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 230
			vertex 150 10 230
			vertex 140 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 220
			vertex 140 0 230
			vertex 140 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 220
			vertex 140 10 230
			vertex 140 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 230
			vertex 150 0 230
			vertex 150 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 230
			vertex 150 10 230
			vertex 140 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 240
			vertex 150 0 240
			vertex 150 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 240
			vertex 150 10 240
			vertex 140 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 230
			vertex 140 0 240
			vertex 140 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 140 0 230
			vertex 140 10 240
			vertex 140 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 240
			vertex 150 0 240
			vertex 150 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 240
			vertex 150 10 240
			vertex 140 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 250
			vertex 150 0 250
			vertex 150 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 140 0 250
			vertex 150 10 250
			vertex 140 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 0
			vertex 160 0 0
			vertex 160 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 0
			vertex 160 10 0
			vertex 150 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 10
			vertex 160 0 10
			vertex 160 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 10
			vertex 160 10 10
			vertex 150 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 10
			vertex 160 0 10
			vertex 160 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 10
			vertex 160 10 10
			vertex 150 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 10
			vertex 160 0 20
			vertex 160 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 10
			vertex 160 10 20
			vertex 160 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 20
			vertex 160 0 20
			vertex 160 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 20
			vertex 160 10 20
			vertex 150 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 20
			vertex 160 0 20
			vertex 160 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 20
			vertex 160 10 20
			vertex 150 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 30
			vertex 160 0 40
			vertex 160 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 30
			vertex 160 10 40
			vertex 160 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 40
			vertex 160 0 40
			vertex 160 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 40
			vertex 160 10 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 30
			vertex 150 0 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 30
			vertex 150 10 40
			vertex 150 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 40
			vertex 160 0 40
			vertex 160 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 40
			vertex 160 10 40
			vertex 150 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 50
			vertex 160 0 50
			vertex 160 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 50
			vertex 160 10 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 40
			vertex 150 0 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 40
			vertex 150 10 50
			vertex 150 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 50
			vertex 160 0 50
			vertex 160 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 50
			vertex 160 10 50
			vertex 150 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 50
			vertex 150 0 60
			vertex 150 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 50
			vertex 150 10 60
			vertex 150 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 70
			vertex 160 0 70
			vertex 160 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 70
			vertex 160 10 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 60
			vertex 150 0 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 60
			vertex 150 10 70
			vertex 150 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 70
			vertex 160 0 70
			vertex 160 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 70
			vertex 160 10 70
			vertex 150 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 80
			vertex 160 0 80
			vertex 160 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 80
			vertex 160 10 80
			vertex 150 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 80
			vertex 160 0 80
			vertex 160 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 80
			vertex 160 10 80
			vertex 150 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 90
			vertex 160 0 100
			vertex 160 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 90
			vertex 160 10 100
			vertex 160 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 90
			vertex 150 0 100
			vertex 150 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 90
			vertex 150 10 100
			vertex 150 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 110
			vertex 160 0 110
			vertex 160 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 110
			vertex 160 10 110
			vertex 150 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 110
			vertex 160 0 110
			vertex 160 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 110
			vertex 160 10 110
			vertex 150 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 110
			vertex 160 0 120
			vertex 160 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 110
			vertex 160 10 120
			vertex 160 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 120
			vertex 160 0 120
			vertex 160 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 120
			vertex 160 10 120
			vertex 150 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 120
			vertex 160 0 120
			vertex 160 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 120
			vertex 160 10 120
			vertex 150 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 120
			vertex 160 0 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 120
			vertex 160 10 130
			vertex 160 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 130
			vertex 160 0 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 130
			vertex 160 10 130
			vertex 150 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 130
			vertex 160 0 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 130
			vertex 160 10 130
			vertex 150 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 130
			vertex 150 0 140
			vertex 150 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 130
			vertex 150 10 140
			vertex 150 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 140
			vertex 160 0 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 140
			vertex 160 10 150
			vertex 160 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 150
			vertex 160 0 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 150
			vertex 160 10 150
			vertex 150 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 150
			vertex 160 0 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 150
			vertex 160 10 150
			vertex 150 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 150
			vertex 150 0 160
			vertex 150 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 150
			vertex 150 10 160
			vertex 150 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 160
			vertex 160 0 170
			vertex 160 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 160
			vertex 160 10 170
			vertex 160 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 170
			vertex 160 0 170
			vertex 160 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 170
			vertex 160 10 170
			vertex 150 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 170
			vertex 160 0 170
			vertex 160 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 170
			vertex 160 10 170
			vertex 150 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 180
			vertex 150 0 190
			vertex 150 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 180
			vertex 150 10 190
			vertex 150 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 190
			vertex 160 0 200
			vertex 160 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 190
			vertex 160 10 200
			vertex 160 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 200
			vertex 160 0 200
			vertex 160 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 200
			vertex 160 10 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 190
			vertex 150 0 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 190
			vertex 150 10 200
			vertex 150 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 200
			vertex 160 0 200
			vertex 160 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 200
			vertex 160 10 200
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 200
			vertex 160 0 210
			vertex 160 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 200
			vertex 160 10 210
			vertex 160 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 200
			vertex 150 0 210
			vertex 150 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 200
			vertex 150 10 210
			vertex 150 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 210
			vertex 150 0 220
			vertex 150 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 150 0 210
			vertex 150 10 220
			vertex 150 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 220
			vertex 160 0 230
			vertex 160 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 220
			vertex 160 10 230
			vertex 160 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 250
			vertex 160 0 250
			vertex 160 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 150 0 250
			vertex 160 10 250
			vertex 150 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 0
			vertex 170 0 0
			vertex 170 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 0
			vertex 170 10 0
			vertex 160 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 10
			vertex 170 0 10
			vertex 170 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 10
			vertex 170 10 10
			vertex 160 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 10
			vertex 170 0 10
			vertex 170 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 10
			vertex 170 10 10
			vertex 160 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 10
			vertex 170 0 20
			vertex 170 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 10
			vertex 170 10 20
			vertex 170 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 10
			vertex 160 0 20
			vertex 160 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 10
			vertex 160 10 20
			vertex 160 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 30
			vertex 170 0 40
			vertex 170 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 30
			vertex 170 10 40
			vertex 170 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 30
			vertex 160 0 40
			vertex 160 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 30
			vertex 160 10 40
			vertex 160 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 40
			vertex 170 0 50
			vertex 170 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 40
			vertex 170 10 50
			vertex 170 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 60
			vertex 170 0 60
			vertex 170 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 60
			vertex 170 10 60
			vertex 160 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 60
			vertex 170 0 60
			vertex 170 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 60
			vertex 170 10 60
			vertex 160 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 80
			vertex 170 0 80
			vertex 170 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 80
			vertex 170 10 80
			vertex 160 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 80
			vertex 170 0 80
			vertex 170 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 80
			vertex 170 10 80
			vertex 160 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 80
			vertex 170 0 90
			vertex 170 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 80
			vertex 170 10 90
			vertex 170 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 100
			vertex 170 0 100
			vertex 170 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 100
			vertex 170 10 100
			vertex 160 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 90
			vertex 160 0 100
			vertex 160 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 90
			vertex 160 10 100
			vertex 160 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 100
			vertex 170 0 100
			vertex 170 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 100
			vertex 170 10 100
			vertex 160 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 100
			vertex 170 0 110
			vertex 170 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 100
			vertex 170 10 110
			vertex 170 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 110
			vertex 170 0 110
			vertex 170 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 110
			vertex 170 10 110
			vertex 160 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 110
			vertex 170 0 110
			vertex 170 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 110
			vertex 170 10 110
			vertex 160 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 110
			vertex 160 0 120
			vertex 160 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 110
			vertex 160 10 120
			vertex 160 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 120
			vertex 170 0 130
			vertex 170 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 120
			vertex 170 10 130
			vertex 170 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 130
			vertex 170 0 130
			vertex 170 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 130
			vertex 170 10 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 120
			vertex 160 0 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 120
			vertex 160 10 130
			vertex 160 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 130
			vertex 170 0 130
			vertex 170 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 130
			vertex 170 10 130
			vertex 160 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 140
			vertex 170 0 140
			vertex 170 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 140
			vertex 170 10 140
			vertex 160 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 140
			vertex 170 0 140
			vertex 170 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 140
			vertex 170 10 140
			vertex 160 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 150
			vertex 170 0 150
			vertex 170 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 150
			vertex 170 10 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 140
			vertex 160 0 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 140
			vertex 160 10 150
			vertex 160 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 150
			vertex 170 0 150
			vertex 170 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 150
			vertex 170 10 150
			vertex 160 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 150
			vertex 170 0 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 150
			vertex 170 10 160
			vertex 170 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 160
			vertex 170 0 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 160
			vertex 170 10 160
			vertex 160 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 160
			vertex 170 0 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 160
			vertex 170 10 160
			vertex 160 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 160
			vertex 170 0 170
			vertex 170 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 160
			vertex 170 10 170
			vertex 170 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 160
			vertex 160 0 170
			vertex 160 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 160
			vertex 160 10 170
			vertex 160 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 170
			vertex 170 0 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 170
			vertex 170 10 180
			vertex 170 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 180
			vertex 170 0 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 180
			vertex 170 10 180
			vertex 160 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 180
			vertex 170 0 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 180
			vertex 170 10 180
			vertex 160 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 180
			vertex 170 0 190
			vertex 170 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 180
			vertex 170 10 190
			vertex 170 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 190
			vertex 160 0 200
			vertex 160 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 190
			vertex 160 10 200
			vertex 160 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 200
			vertex 170 0 210
			vertex 170 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 200
			vertex 170 10 210
			vertex 170 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 210
			vertex 170 0 210
			vertex 170 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 210
			vertex 170 10 210
			vertex 160 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 200
			vertex 160 0 210
			vertex 160 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 200
			vertex 160 10 210
			vertex 160 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 210
			vertex 170 0 210
			vertex 170 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 210
			vertex 170 10 210
			vertex 160 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 210
			vertex 170 0 220
			vertex 170 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 210
			vertex 170 10 220
			vertex 170 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 220
			vertex 170 0 220
			vertex 170 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 220
			vertex 170 10 220
			vertex 160 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 220
			vertex 170 0 220
			vertex 170 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 220
			vertex 170 10 220
			vertex 160 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 230
			vertex 170 0 230
			vertex 170 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 230
			vertex 170 10 230
			vertex 160 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 220
			vertex 160 0 230
			vertex 160 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 160 0 220
			vertex 160 10 230
			vertex 160 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 230
			vertex 170 0 230
			vertex 170 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 230
			vertex 170 10 230
			vertex 160 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 240
			vertex 170 0 240
			vertex 170 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 240
			vertex 170 10 240
			vertex 160 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 240
			vertex 170 0 240
			vertex 170 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 240
			vertex 170 10 240
			vertex 160 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 250
			vertex 170 0 250
			vertex 170 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 160 0 250
			vertex 170 10 250
			vertex 160 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 0
			vertex 180 0 0
			vertex 180 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 0
			vertex 180 10 0
			vertex 170 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 20
			vertex 180 0 20
			vertex 180 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 20
			vertex 180 10 20
			vertex 170 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 10
			vertex 170 0 20
			vertex 170 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 10
			vertex 170 10 20
			vertex 170 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 20
			vertex 180 0 20
			vertex 180 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 20
			vertex 180 10 20
			vertex 170 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 30
			vertex 180 0 30
			vertex 180 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 30
			vertex 180 10 30
			vertex 170 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 30
			vertex 180 0 30
			vertex 180 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 30
			vertex 180 10 30
			vertex 170 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 30
			vertex 180 0 40
			vertex 180 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 30
			vertex 180 10 40
			vertex 180 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 30
			vertex 170 0 40
			vertex 170 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 30
			vertex 170 10 40
			vertex 170 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 50
			vertex 180 0 50
			vertex 180 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 50
			vertex 180 10 50
			vertex 170 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 40
			vertex 170 0 50
			vertex 170 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 40
			vertex 170 10 50
			vertex 170 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 50
			vertex 180 0 50
			vertex 180 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 50
			vertex 180 10 50
			vertex 170 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 60
			vertex 180 0 60
			vertex 180 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 60
			vertex 180 10 60
			vertex 170 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 60
			vertex 180 0 60
			vertex 180 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 60
			vertex 180 10 60
			vertex 170 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 70
			vertex 180 0 70
			vertex 180 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 70
			vertex 180 10 70
			vertex 170 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 70
			vertex 180 0 70
			vertex 180 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 70
			vertex 180 10 70
			vertex 170 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 70
			vertex 180 0 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 70
			vertex 180 10 80
			vertex 180 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 80
			vertex 180 0 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 80
			vertex 180 10 80
			vertex 170 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 80
			vertex 180 0 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 80
			vertex 180 10 80
			vertex 170 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 80
			vertex 180 0 90
			vertex 180 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 80
			vertex 180 10 90
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 80
			vertex 170 0 90
			vertex 170 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 80
			vertex 170 10 90
			vertex 170 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 100
			vertex 180 0 100
			vertex 180 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 100
			vertex 180 10 100
			vertex 170 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 100
			vertex 180 0 100
			vertex 180 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 100
			vertex 180 10 100
			vertex 170 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 100
			vertex 170 0 110
			vertex 170 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 100
			vertex 170 10 110
			vertex 170 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 110
			vertex 180 0 120
			vertex 180 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 110
			vertex 180 10 120
			vertex 180 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 120
			vertex 170 0 130
			vertex 170 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 120
			vertex 170 10 130
			vertex 170 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 140
			vertex 180 0 150
			vertex 180 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 140
			vertex 180 10 150
			vertex 180 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 150
			vertex 180 0 160
			vertex 180 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 150
			vertex 180 10 160
			vertex 180 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 160
			vertex 180 0 160
			vertex 180 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 160
			vertex 180 10 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 150
			vertex 170 0 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 150
			vertex 170 10 160
			vertex 170 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 160
			vertex 180 0 160
			vertex 180 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 160
			vertex 180 10 160
			vertex 170 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 160
			vertex 170 0 170
			vertex 170 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 160
			vertex 170 10 170
			vertex 170 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 180
			vertex 180 0 180
			vertex 180 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 180
			vertex 180 10 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 170
			vertex 170 0 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 170
			vertex 170 10 180
			vertex 170 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 180
			vertex 180 0 180
			vertex 180 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 180
			vertex 180 10 180
			vertex 170 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 190
			vertex 180 0 190
			vertex 180 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 190
			vertex 180 10 190
			vertex 170 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 180
			vertex 170 0 190
			vertex 170 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 180
			vertex 170 10 190
			vertex 170 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 190
			vertex 180 0 190
			vertex 180 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 190
			vertex 180 10 190
			vertex 170 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 190
			vertex 180 0 200
			vertex 180 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 190
			vertex 180 10 200
			vertex 180 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 200
			vertex 170 0 210
			vertex 170 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 200
			vertex 170 10 210
			vertex 170 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 210
			vertex 180 0 220
			vertex 180 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 210
			vertex 180 10 220
			vertex 180 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 210
			vertex 170 0 220
			vertex 170 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 170 0 210
			vertex 170 10 220
			vertex 170 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 230
			vertex 180 0 240
			vertex 180 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 230
			vertex 180 10 240
			vertex 180 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 240
			vertex 180 0 240
			vertex 180 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 240
			vertex 180 10 240
			vertex 170 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 240
			vertex 180 0 240
			vertex 180 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 240
			vertex 180 10 240
			vertex 170 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 250
			vertex 180 0 250
			vertex 180 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 170 0 250
			vertex 180 10 250
			vertex 170 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 0
			vertex 190 0 0
			vertex 190 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 0
			vertex 190 10 0
			vertex 180 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 10
			vertex 190 0 10
			vertex 190 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 10
			vertex 190 10 10
			vertex 180 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 10
			vertex 190 0 10
			vertex 190 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 10
			vertex 190 10 10
			vertex 180 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 20
			vertex 190 0 20
			vertex 190 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 20
			vertex 190 10 20
			vertex 180 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 20
			vertex 190 0 20
			vertex 190 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 20
			vertex 190 10 20
			vertex 180 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 20
			vertex 190 0 30
			vertex 190 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 20
			vertex 190 10 30
			vertex 190 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 30
			vertex 190 0 40
			vertex 190 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 30
			vertex 190 10 40
			vertex 190 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 30
			vertex 180 0 40
			vertex 180 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 30
			vertex 180 10 40
			vertex 180 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 50
			vertex 190 0 50
			vertex 190 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 50
			vertex 190 10 50
			vertex 180 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 50
			vertex 190 0 50
			vertex 190 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 50
			vertex 190 10 50
			vertex 180 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 60
			vertex 190 0 60
			vertex 190 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 60
			vertex 190 10 60
			vertex 180 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 60
			vertex 190 0 60
			vertex 190 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 60
			vertex 190 10 60
			vertex 180 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 70
			vertex 190 0 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 70
			vertex 190 10 80
			vertex 190 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 80
			vertex 190 0 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 80
			vertex 190 10 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 70
			vertex 180 0 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 70
			vertex 180 10 80
			vertex 180 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 80
			vertex 190 0 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 80
			vertex 190 10 80
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 80
			vertex 180 0 90
			vertex 180 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 80
			vertex 180 10 90
			vertex 180 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 90
			vertex 190 0 100
			vertex 190 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 90
			vertex 190 10 100
			vertex 190 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 100
			vertex 190 0 110
			vertex 190 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 100
			vertex 190 10 110
			vertex 190 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 110
			vertex 190 0 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 110
			vertex 190 10 120
			vertex 190 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 120
			vertex 190 0 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 120
			vertex 190 10 120
			vertex 180 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 110
			vertex 180 0 120
			vertex 180 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 110
			vertex 180 10 120
			vertex 180 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 120
			vertex 190 0 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 120
			vertex 190 10 120
			vertex 180 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 130
			vertex 190 0 130
			vertex 190 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 130
			vertex 190 10 130
			vertex 180 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 130
			vertex 190 0 130
			vertex 190 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 130
			vertex 190 10 130
			vertex 180 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 140
			vertex 180 0 150
			vertex 180 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 140
			vertex 180 10 150
			vertex 180 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 150
			vertex 180 0 160
			vertex 180 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 150
			vertex 180 10 160
			vertex 180 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 160
			vertex 190 0 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 160
			vertex 190 10 170
			vertex 190 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 170
			vertex 190 0 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 170
			vertex 190 10 170
			vertex 180 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 170
			vertex 190 0 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 170
			vertex 190 10 170
			vertex 180 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 170
			vertex 190 0 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 170
			vertex 190 10 180
			vertex 190 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 180
			vertex 190 0 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 180
			vertex 190 10 180
			vertex 180 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 180
			vertex 190 0 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 180
			vertex 190 10 180
			vertex 180 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 180
			vertex 190 0 190
			vertex 190 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 180
			vertex 190 10 190
			vertex 190 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 200
			vertex 190 0 200
			vertex 190 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 200
			vertex 190 10 200
			vertex 180 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 190
			vertex 180 0 200
			vertex 180 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 190
			vertex 180 10 200
			vertex 180 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 200
			vertex 190 0 200
			vertex 190 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 200
			vertex 190 10 200
			vertex 180 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 200
			vertex 190 0 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 200
			vertex 190 10 210
			vertex 190 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 210
			vertex 190 0 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 210
			vertex 190 10 210
			vertex 180 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 210
			vertex 190 0 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 210
			vertex 190 10 210
			vertex 180 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 220
			vertex 190 0 220
			vertex 190 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 220
			vertex 190 10 220
			vertex 180 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 210
			vertex 180 0 220
			vertex 180 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 210
			vertex 180 10 220
			vertex 180 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 220
			vertex 190 0 220
			vertex 190 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 220
			vertex 190 10 220
			vertex 180 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 220
			vertex 190 0 230
			vertex 190 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 220
			vertex 190 10 230
			vertex 190 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 230
			vertex 190 0 230
			vertex 190 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 230
			vertex 190 10 230
			vertex 180 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 230
			vertex 190 0 230
			vertex 190 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 230
			vertex 190 10 230
			vertex 180 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 230
			vertex 180 0 240
			vertex 180 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 180 0 230
			vertex 180 10 240
			vertex 180 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 250
			vertex 190 0 250
			vertex 190 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 180 0 250
			vertex 190 10 250
			vertex 180 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 0
			vertex 200 0 0
			vertex 200 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 0
			vertex 200 10 0
			vertex 190 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 0
			vertex 200 0 10
			vertex 200 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 0
			vertex 200 10 10
			vertex 200 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 10
			vertex 200 0 10
			vertex 200 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 10
			vertex 200 10 10
			vertex 190 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 10
			vertex 200 0 10
			vertex 200 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 10
			vertex 200 10 10
			vertex 190 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 20
			vertex 190 0 30
			vertex 190 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 20
			vertex 190 10 30
			vertex 190 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 30
			vertex 200 0 40
			vertex 200 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 30
			vertex 200 10 40
			vertex 200 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 30
			vertex 190 0 40
			vertex 190 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 30
			vertex 190 10 40
			vertex 190 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 40
			vertex 200 0 50
			vertex 200 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 40
			vertex 200 10 50
			vertex 200 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 50
			vertex 200 0 50
			vertex 200 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 50
			vertex 200 10 50
			vertex 190 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 50
			vertex 200 0 50
			vertex 200 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 50
			vertex 200 10 50
			vertex 190 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 60
			vertex 200 0 60
			vertex 200 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 60
			vertex 200 10 60
			vertex 190 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 60
			vertex 200 0 60
			vertex 200 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 60
			vertex 200 10 60
			vertex 190 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 60
			vertex 200 0 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 60
			vertex 200 10 70
			vertex 200 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 70
			vertex 200 0 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 70
			vertex 200 10 70
			vertex 190 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 70
			vertex 200 0 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 70
			vertex 200 10 70
			vertex 190 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 80
			vertex 200 0 80
			vertex 200 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 80
			vertex 200 10 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 70
			vertex 190 0 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 70
			vertex 190 10 80
			vertex 190 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 80
			vertex 200 0 80
			vertex 200 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 80
			vertex 200 10 80
			vertex 190 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 90
			vertex 200 0 90
			vertex 200 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 90
			vertex 200 10 90
			vertex 190 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 90
			vertex 200 0 90
			vertex 200 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 90
			vertex 200 10 90
			vertex 190 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 100
			vertex 200 0 100
			vertex 200 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 100
			vertex 200 10 100
			vertex 190 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 90
			vertex 190 0 100
			vertex 190 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 90
			vertex 190 10 100
			vertex 190 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 100
			vertex 200 0 100
			vertex 200 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 100
			vertex 200 10 100
			vertex 190 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 100
			vertex 200 0 110
			vertex 200 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 100
			vertex 200 10 110
			vertex 200 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 100
			vertex 190 0 110
			vertex 190 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 100
			vertex 190 10 110
			vertex 190 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 120
			vertex 200 0 120
			vertex 200 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 120
			vertex 200 10 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 110
			vertex 190 0 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 110
			vertex 190 10 120
			vertex 190 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 120
			vertex 200 0 120
			vertex 200 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 120
			vertex 200 10 120
			vertex 190 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 120
			vertex 200 0 130
			vertex 200 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 120
			vertex 200 10 130
			vertex 200 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 130
			vertex 200 0 130
			vertex 200 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 130
			vertex 200 10 130
			vertex 190 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 130
			vertex 200 0 130
			vertex 200 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 130
			vertex 200 10 130
			vertex 190 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 140
			vertex 200 0 140
			vertex 200 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 140
			vertex 200 10 140
			vertex 190 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 140
			vertex 200 0 140
			vertex 200 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 140
			vertex 200 10 140
			vertex 190 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 150
			vertex 200 0 150
			vertex 200 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 150
			vertex 200 10 150
			vertex 190 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 150
			vertex 200 0 150
			vertex 200 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 150
			vertex 200 10 150
			vertex 190 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 150
			vertex 200 0 160
			vertex 200 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 150
			vertex 200 10 160
			vertex 200 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 170
			vertex 200 0 170
			vertex 200 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 170
			vertex 200 10 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 160
			vertex 190 0 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 160
			vertex 190 10 170
			vertex 190 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 170
			vertex 200 0 170
			vertex 200 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 170
			vertex 200 10 170
			vertex 190 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 180
			vertex 200 0 180
			vertex 200 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 180
			vertex 200 10 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 170
			vertex 190 0 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 170
			vertex 190 10 180
			vertex 190 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 180
			vertex 200 0 180
			vertex 200 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 180
			vertex 200 10 180
			vertex 190 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 180
			vertex 200 0 190
			vertex 200 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 180
			vertex 200 10 190
			vertex 200 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 180
			vertex 190 0 190
			vertex 190 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 180
			vertex 190 10 190
			vertex 190 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 210
			vertex 200 0 210
			vertex 200 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 210
			vertex 200 10 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 200
			vertex 190 0 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 200
			vertex 190 10 210
			vertex 190 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 210
			vertex 200 0 210
			vertex 200 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 210
			vertex 200 10 210
			vertex 190 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 210
			vertex 200 0 220
			vertex 200 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 210
			vertex 200 10 220
			vertex 200 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 220
			vertex 200 0 230
			vertex 200 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 220
			vertex 200 10 230
			vertex 200 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 220
			vertex 190 0 230
			vertex 190 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 190 0 220
			vertex 190 10 230
			vertex 190 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 230
			vertex 200 0 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 230
			vertex 200 10 240
			vertex 200 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 240
			vertex 200 0 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 240
			vertex 200 10 240
			vertex 190 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 240
			vertex 200 0 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 240
			vertex 200 10 240
			vertex 190 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 250
			vertex 200 0 250
			vertex 200 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 190 0 250
			vertex 200 10 250
			vertex 190 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 0
			vertex 210 0 0
			vertex 210 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 0
			vertex 210 10 0
			vertex 200 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 0
			vertex 210 0 10
			vertex 210 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 0
			vertex 210 10 10
			vertex 210 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 0
			vertex 200 0 10
			vertex 200 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 0
			vertex 200 10 10
			vertex 200 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 20
			vertex 210 0 20
			vertex 210 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 20
			vertex 210 10 20
			vertex 200 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 20
			vertex 210 0 20
			vertex 210 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 20
			vertex 210 10 20
			vertex 200 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 30
			vertex 210 0 30
			vertex 210 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 30
			vertex 210 10 30
			vertex 200 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 30
			vertex 210 0 30
			vertex 210 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 30
			vertex 210 10 30
			vertex 200 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 30
			vertex 210 0 40
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 30
			vertex 210 10 40
			vertex 210 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 30
			vertex 200 0 40
			vertex 200 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 30
			vertex 200 10 40
			vertex 200 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 40
			vertex 210 0 50
			vertex 210 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 40
			vertex 210 10 50
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 40
			vertex 200 0 50
			vertex 200 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 40
			vertex 200 10 50
			vertex 200 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 50
			vertex 210 0 60
			vertex 210 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 50
			vertex 210 10 60
			vertex 210 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 60
			vertex 210 0 70
			vertex 210 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 60
			vertex 210 10 70
			vertex 210 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 70
			vertex 210 0 70
			vertex 210 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 70
			vertex 210 10 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 60
			vertex 200 0 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 60
			vertex 200 10 70
			vertex 200 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 70
			vertex 210 0 70
			vertex 210 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 70
			vertex 210 10 70
			vertex 200 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 70
			vertex 210 0 80
			vertex 210 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 70
			vertex 210 10 80
			vertex 210 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 80
			vertex 210 0 90
			vertex 210 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 80
			vertex 210 10 90
			vertex 210 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 100
			vertex 210 0 110
			vertex 210 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 100
			vertex 210 10 110
			vertex 210 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 100
			vertex 200 0 110
			vertex 200 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 100
			vertex 200 10 110
			vertex 200 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 110
			vertex 210 0 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 110
			vertex 210 10 120
			vertex 210 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 120
			vertex 210 0 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 120
			vertex 210 10 120
			vertex 200 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 120
			vertex 210 0 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 120
			vertex 210 10 120
			vertex 200 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 120
			vertex 200 0 130
			vertex 200 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 120
			vertex 200 10 130
			vertex 200 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 130
			vertex 210 0 140
			vertex 210 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 130
			vertex 210 10 140
			vertex 210 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 140
			vertex 210 0 140
			vertex 210 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 140
			vertex 210 10 140
			vertex 200 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 140
			vertex 210 0 140
			vertex 210 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 140
			vertex 210 10 140
			vertex 200 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 140
			vertex 210 0 150
			vertex 210 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 140
			vertex 210 10 150
			vertex 210 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 150
			vertex 210 0 160
			vertex 210 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 150
			vertex 210 10 160
			vertex 210 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 160
			vertex 210 0 160
			vertex 210 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 160
			vertex 210 10 160
			vertex 200 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 150
			vertex 200 0 160
			vertex 200 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 150
			vertex 200 10 160
			vertex 200 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 160
			vertex 210 0 160
			vertex 210 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 160
			vertex 210 10 160
			vertex 200 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 170
			vertex 210 0 170
			vertex 210 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 170
			vertex 210 10 170
			vertex 200 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 170
			vertex 210 0 170
			vertex 210 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 170
			vertex 210 10 170
			vertex 200 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 170
			vertex 210 0 180
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 170
			vertex 210 10 180
			vertex 210 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 180
			vertex 210 0 190
			vertex 210 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 180
			vertex 210 10 190
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 180
			vertex 200 0 190
			vertex 200 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 180
			vertex 200 10 190
			vertex 200 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 200
			vertex 210 0 200
			vertex 210 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 200
			vertex 210 10 200
			vertex 200 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 200
			vertex 210 0 200
			vertex 210 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 200
			vertex 210 10 200
			vertex 200 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 200
			vertex 210 0 210
			vertex 210 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 200
			vertex 210 10 210
			vertex 210 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 210
			vertex 210 0 220
			vertex 210 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 210
			vertex 210 10 220
			vertex 210 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 210
			vertex 200 0 220
			vertex 200 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 210
			vertex 200 10 220
			vertex 200 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 220
			vertex 200 0 230
			vertex 200 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 220
			vertex 200 10 230
			vertex 200 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 230
			vertex 210 0 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 230
			vertex 210 10 240
			vertex 210 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 240
			vertex 210 0 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 240
			vertex 210 10 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 230
			vertex 200 0 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 200 0 230
			vertex 200 10 240
			vertex 200 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 240
			vertex 210 0 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 240
			vertex 210 10 240
			vertex 200 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 250
			vertex 210 0 250
			vertex 210 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 200 0 250
			vertex 210 10 250
			vertex 200 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 0
			vertex 220 0 0
			vertex 220 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 0
			vertex 220 10 0
			vertex 210 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 0
			vertex 220 0 10
			vertex 220 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 0
			vertex 220 10 10
			vertex 220 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 0
			vertex 210 0 10
			vertex 210 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 0
			vertex 210 10 10
			vertex 210 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 10
			vertex 220 0 20
			vertex 220 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 10
			vertex 220 10 20
			vertex 220 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 20
			vertex 220 0 20
			vertex 220 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 20
			vertex 220 10 20
			vertex 210 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 20
			vertex 220 0 20
			vertex 220 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 20
			vertex 220 10 20
			vertex 210 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 20
			vertex 220 0 30
			vertex 220 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 20
			vertex 220 10 30
			vertex 220 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 30
			vertex 220 0 40
			vertex 220 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 30
			vertex 220 10 40
			vertex 220 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 40
			vertex 220 0 40
			vertex 220 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 40
			vertex 220 10 40
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 30
			vertex 210 0 40
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 30
			vertex 210 10 40
			vertex 210 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 40
			vertex 220 0 40
			vertex 220 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 40
			vertex 220 10 40
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 40
			vertex 210 0 50
			vertex 210 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 40
			vertex 210 10 50
			vertex 210 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 50
			vertex 210 0 60
			vertex 210 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 50
			vertex 210 10 60
			vertex 210 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 60
			vertex 220 0 70
			vertex 220 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 60
			vertex 220 10 70
			vertex 220 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 60
			vertex 210 0 70
			vertex 210 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 60
			vertex 210 10 70
			vertex 210 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 80
			vertex 220 0 80
			vertex 220 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 80
			vertex 220 10 80
			vertex 210 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 70
			vertex 210 0 80
			vertex 210 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 70
			vertex 210 10 80
			vertex 210 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 80
			vertex 220 0 80
			vertex 220 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 80
			vertex 220 10 80
			vertex 210 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 80
			vertex 220 0 90
			vertex 220 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 80
			vertex 220 10 90
			vertex 220 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 80
			vertex 210 0 90
			vertex 210 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 80
			vertex 210 10 90
			vertex 210 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 100
			vertex 220 0 100
			vertex 220 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 100
			vertex 220 10 100
			vertex 210 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 100
			vertex 220 0 100
			vertex 220 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 100
			vertex 220 10 100
			vertex 210 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 100
			vertex 210 0 110
			vertex 210 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 100
			vertex 210 10 110
			vertex 210 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 110
			vertex 220 0 120
			vertex 220 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 110
			vertex 220 10 120
			vertex 220 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 120
			vertex 220 0 120
			vertex 220 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 120
			vertex 220 10 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 110
			vertex 210 0 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 110
			vertex 210 10 120
			vertex 210 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 120
			vertex 220 0 120
			vertex 220 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 120
			vertex 220 10 120
			vertex 210 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 120
			vertex 220 0 130
			vertex 220 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 120
			vertex 220 10 130
			vertex 220 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 130
			vertex 220 0 130
			vertex 220 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 130
			vertex 220 10 130
			vertex 210 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 130
			vertex 220 0 130
			vertex 220 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 130
			vertex 220 10 130
			vertex 210 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 130
			vertex 210 0 140
			vertex 210 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 130
			vertex 210 10 140
			vertex 210 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 140
			vertex 220 0 150
			vertex 220 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 140
			vertex 220 10 150
			vertex 220 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 140
			vertex 210 0 150
			vertex 210 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 140
			vertex 210 10 150
			vertex 210 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 150
			vertex 210 0 160
			vertex 210 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 150
			vertex 210 10 160
			vertex 210 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 160
			vertex 220 0 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 160
			vertex 220 10 170
			vertex 220 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 170
			vertex 220 0 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 170
			vertex 220 10 170
			vertex 210 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 170
			vertex 220 0 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 170
			vertex 220 10 170
			vertex 210 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 180
			vertex 220 0 180
			vertex 220 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 180
			vertex 220 10 180
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 170
			vertex 210 0 180
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 170
			vertex 210 10 180
			vertex 210 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 180
			vertex 220 0 180
			vertex 220 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 180
			vertex 220 10 180
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 180
			vertex 210 0 190
			vertex 210 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 180
			vertex 210 10 190
			vertex 210 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 190
			vertex 220 0 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 190
			vertex 220 10 200
			vertex 220 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 200
			vertex 220 0 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 200
			vertex 220 10 200
			vertex 210 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 200
			vertex 220 0 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 200
			vertex 220 10 200
			vertex 210 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 200
			vertex 220 0 210
			vertex 220 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 200
			vertex 220 10 210
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 200
			vertex 210 0 210
			vertex 210 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 200
			vertex 210 10 210
			vertex 210 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 210
			vertex 210 0 220
			vertex 210 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 210
			vertex 210 10 220
			vertex 210 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 230
			vertex 220 0 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 230
			vertex 220 10 240
			vertex 220 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 240
			vertex 220 0 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 240
			vertex 220 10 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 230
			vertex 210 0 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 210 0 230
			vertex 210 10 240
			vertex 210 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 240
			vertex 220 0 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 240
			vertex 220 10 240
			vertex 210 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 240
			vertex 220 0 250
			vertex 220 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 240
			vertex 220 10 250
			vertex 220 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 250
			vertex 220 0 250
			vertex 220 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 210 0 250
			vertex 220 10 250
			vertex 210 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 0
			vertex 230 0 0
			vertex 230 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 0
			vertex 230 10 0
			vertex 220 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 0
			vertex 220 0 10
			vertex 220 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 0
			vertex 220 10 10
			vertex 220 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 10
			vertex 230 0 20
			vertex 230 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 10
			vertex 230 10 20
			vertex 230 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 10
			vertex 220 0 20
			vertex 220 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 10
			vertex 220 10 20
			vertex 220 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 20
			vertex 230 0 30
			vertex 230 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 20
			vertex 230 10 30
			vertex 230 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 30
			vertex 230 0 30
			vertex 230 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 30
			vertex 230 10 30
			vertex 220 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 20
			vertex 220 0 30
			vertex 220 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 20
			vertex 220 10 30
			vertex 220 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 30
			vertex 230 0 30
			vertex 230 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 30
			vertex 230 10 30
			vertex 220 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 30
			vertex 230 0 40
			vertex 230 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 30
			vertex 230 10 40
			vertex 230 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 30
			vertex 220 0 40
			vertex 220 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 30
			vertex 220 10 40
			vertex 220 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 50
			vertex 230 0 50
			vertex 230 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 50
			vertex 230 10 50
			vertex 220 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 50
			vertex 230 0 50
			vertex 230 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 50
			vertex 230 10 50
			vertex 220 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 50
			vertex 230 0 60
			vertex 230 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 50
			vertex 230 10 60
			vertex 230 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 60
			vertex 230 0 60
			vertex 230 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 60
			vertex 230 10 60
			vertex 220 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 60
			vertex 230 0 60
			vertex 230 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 60
			vertex 230 10 60
			vertex 220 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 60
			vertex 230 0 70
			vertex 230 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 60
			vertex 230 10 70
			vertex 230 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 60
			vertex 220 0 70
			vertex 220 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 60
			vertex 220 10 70
			vertex 220 10 60
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 90
			vertex 230 0 90
			vertex 230 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 90
			vertex 230 10 90
			vertex 220 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 80
			vertex 220 0 90
			vertex 220 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 80
			vertex 220 10 90
			vertex 220 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 90
			vertex 230 0 90
			vertex 230 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 90
			vertex 230 10 90
			vertex 220 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 100
			vertex 230 0 100
			vertex 230 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 100
			vertex 230 10 100
			vertex 220 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 100
			vertex 230 0 100
			vertex 230 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 100
			vertex 230 10 100
			vertex 220 10 100
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 110
			vertex 230 0 110
			vertex 230 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 110
			vertex 230 10 110
			vertex 220 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 110
			vertex 230 0 110
			vertex 230 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 110
			vertex 230 10 110
			vertex 220 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 110
			vertex 220 0 120
			vertex 220 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 110
			vertex 220 10 120
			vertex 220 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 120
			vertex 230 0 130
			vertex 230 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 120
			vertex 230 10 130
			vertex 230 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 120
			vertex 220 0 130
			vertex 220 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 120
			vertex 220 10 130
			vertex 220 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 150
			vertex 230 0 150
			vertex 230 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 150
			vertex 230 10 150
			vertex 220 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 140
			vertex 220 0 150
			vertex 220 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 140
			vertex 220 10 150
			vertex 220 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 150
			vertex 230 0 150
			vertex 230 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 150
			vertex 230 10 150
			vertex 220 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 150
			vertex 230 0 160
			vertex 230 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 150
			vertex 230 10 160
			vertex 230 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 170
			vertex 230 0 170
			vertex 230 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 170
			vertex 230 10 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 160
			vertex 220 0 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 160
			vertex 220 10 170
			vertex 220 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 170
			vertex 230 0 170
			vertex 230 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 170
			vertex 230 10 170
			vertex 220 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 190
			vertex 230 0 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 190
			vertex 230 10 200
			vertex 230 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 200
			vertex 230 0 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 200
			vertex 230 10 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 190
			vertex 220 0 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 190
			vertex 220 10 200
			vertex 220 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 200
			vertex 230 0 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 200
			vertex 230 10 200
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 200
			vertex 220 0 210
			vertex 220 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 200
			vertex 220 10 210
			vertex 220 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 210
			vertex 230 0 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 210
			vertex 230 10 220
			vertex 230 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 220
			vertex 230 0 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 220
			vertex 230 10 220
			vertex 220 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 220
			vertex 230 0 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 220
			vertex 230 10 220
			vertex 220 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 220
			vertex 230 0 230
			vertex 230 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 220
			vertex 230 10 230
			vertex 230 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 240
			vertex 230 0 240
			vertex 230 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 240
			vertex 230 10 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 230
			vertex 220 0 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 230
			vertex 220 10 240
			vertex 220 10 230
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 240
			vertex 230 0 240
			vertex 230 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 240
			vertex 230 10 240
			vertex 220 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 250
			vertex 230 0 250
			vertex 230 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 220 0 250
			vertex 230 10 250
			vertex 220 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 240
			vertex 220 0 250
			vertex 220 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 220 0 240
			vertex 220 10 250
			vertex 220 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 0
			vertex 240 0 0
			vertex 240 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 0
			vertex 240 10 0
			vertex 230 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 10
			vertex 240 0 20
			vertex 240 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 10
			vertex 240 10 20
			vertex 240 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 10
			vertex 230 0 20
			vertex 230 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 10
			vertex 230 10 20
			vertex 230 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 20
			vertex 230 0 30
			vertex 230 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 20
			vertex 230 10 30
			vertex 230 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 30
			vertex 230 0 40
			vertex 230 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 30
			vertex 230 10 40
			vertex 230 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 40
			vertex 240 0 50
			vertex 240 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 40
			vertex 240 10 50
			vertex 240 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 50
			vertex 240 0 50
			vertex 240 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 50
			vertex 240 10 50
			vertex 230 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 50
			vertex 240 0 50
			vertex 240 10 50
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 50
			vertex 240 10 50
			vertex 230 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 50
			vertex 240 0 60
			vertex 240 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 50
			vertex 240 10 60
			vertex 240 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 50
			vertex 230 0 60
			vertex 230 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 50
			vertex 230 10 60
			vertex 230 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 60
			vertex 240 0 70
			vertex 240 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 60
			vertex 240 10 70
			vertex 240 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 60
			vertex 230 0 70
			vertex 230 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 60
			vertex 230 10 70
			vertex 230 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 70
			vertex 240 0 80
			vertex 240 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 70
			vertex 240 10 80
			vertex 240 10 70
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 80
			vertex 240 0 80
			vertex 240 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 80
			vertex 240 10 80
			vertex 230 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 80
			vertex 240 0 80
			vertex 240 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 80
			vertex 240 10 80
			vertex 230 10 80
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 90
			vertex 240 0 90
			vertex 240 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 90
			vertex 240 10 90
			vertex 230 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 90
			vertex 240 0 90
			vertex 240 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 90
			vertex 240 10 90
			vertex 230 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 90
			vertex 240 0 100
			vertex 240 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 90
			vertex 240 10 100
			vertex 240 10 90
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 110
			vertex 240 0 110
			vertex 240 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 110
			vertex 240 10 110
			vertex 230 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 110
			vertex 240 0 110
			vertex 240 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 110
			vertex 240 10 110
			vertex 230 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 110
			vertex 240 0 120
			vertex 240 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 110
			vertex 240 10 120
			vertex 240 10 110
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 120
			vertex 240 0 120
			vertex 240 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 120
			vertex 240 10 120
			vertex 230 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 120
			vertex 240 0 120
			vertex 240 10 120
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 120
			vertex 240 10 120
			vertex 230 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 120
			vertex 240 0 130
			vertex 240 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 120
			vertex 240 10 130
			vertex 240 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 120
			vertex 230 0 130
			vertex 230 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 120
			vertex 230 10 130
			vertex 230 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 130
			vertex 240 0 140
			vertex 240 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 130
			vertex 240 10 140
			vertex 240 10 130
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 140
			vertex 240 0 140
			vertex 240 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 140
			vertex 240 10 140
			vertex 230 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 140
			vertex 240 0 140
			vertex 240 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 140
			vertex 240 10 140
			vertex 230 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 140
			vertex 240 0 150
			vertex 240 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 140
			vertex 240 10 150
			vertex 240 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 150
			vertex 240 0 160
			vertex 240 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 150
			vertex 240 10 160
			vertex 240 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 160
			vertex 240 0 160
			vertex 240 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 160
			vertex 240 10 160
			vertex 230 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 150
			vertex 230 0 160
			vertex 230 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 150
			vertex 230 10 160
			vertex 230 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 160
			vertex 240 0 160
			vertex 240 10 160
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 160
			vertex 240 10 160
			vertex 230 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 170
			vertex 240 0 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 170
			vertex 240 10 180
			vertex 240 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 180
			vertex 240 0 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 180
			vertex 240 10 180
			vertex 230 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 180
			vertex 240 0 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 180
			vertex 240 10 180
			vertex 230 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 190
			vertex 240 0 200
			vertex 240 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 190
			vertex 240 10 200
			vertex 240 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 200
			vertex 240 0 200
			vertex 240 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 200
			vertex 240 10 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 190
			vertex 230 0 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 190
			vertex 230 10 200
			vertex 230 10 190
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 200
			vertex 240 0 200
			vertex 240 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 200
			vertex 240 10 200
			vertex 230 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 200
			vertex 240 0 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 200
			vertex 240 10 210
			vertex 240 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 210
			vertex 240 0 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 210
			vertex 240 10 210
			vertex 230 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 210
			vertex 240 0 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 210
			vertex 240 10 210
			vertex 230 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 220
			vertex 240 0 220
			vertex 240 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 220
			vertex 240 10 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 210
			vertex 230 0 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 210
			vertex 230 10 220
			vertex 230 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 220
			vertex 240 0 220
			vertex 240 10 220
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 220
			vertex 240 10 220
			vertex 230 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 220
			vertex 240 0 230
			vertex 240 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 220
			vertex 240 10 230
			vertex 240 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 220
			vertex 230 0 230
			vertex 230 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 230 0 220
			vertex 230 10 230
			vertex 230 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 240
			vertex 240 0 250
			vertex 240 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 240
			vertex 240 10 250
			vertex 240 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 250
			vertex 240 0 250
			vertex 240 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 230 0 250
			vertex 240 10 250
			vertex 230 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 0
			vertex 250 0 0
			vertex 250 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 0
			vertex 250 10 0
			vertex 240 10 0
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 0
			vertex 250 0 10
			vertex 250 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 0
			vertex 250 10 10
			vertex 250 10 0
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 10
			vertex 250 0 10
			vertex 250 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 10
			vertex 250 10 10
			vertex 240 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 10
			vertex 250 0 10
			vertex 250 10 10
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 10
			vertex 250 10 10
			vertex 240 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 10
			vertex 250 0 20
			vertex 250 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 10
			vertex 250 10 20
			vertex 250 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 10
			vertex 240 0 20
			vertex 240 10 20
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 10
			vertex 240 10 20
			vertex 240 10 10
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 20
			vertex 250 0 30
			vertex 250 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 20
			vertex 250 10 30
			vertex 250 10 20
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 30
			vertex 250 0 30
			vertex 250 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 30
			vertex 250 10 30
			vertex 240 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 30
			vertex 250 0 30
			vertex 250 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 30
			vertex 250 10 30
			vertex 240 10 30
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 30
			vertex 250 0 40
			vertex 250 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 30
			vertex 250 10 40
			vertex 250 10 30
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 40
			vertex 250 0 40
			vertex 250 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 40
			vertex 250 10 40
			vertex 240 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 40
			vertex 250 0 40
			vertex 250 10 40
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 40
			vertex 250 10 40
			vertex 240 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 40
			vertex 250 0 50
			vertex 250 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 40
			vertex 250 10 50
			vertex 250 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 40
			vertex 240 0 50
			vertex 240 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 40
			vertex 240 10 50
			vertex 240 10 40
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 50
			vertex 250 0 60
			vertex 250 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 50
			vertex 250 10 60
			vertex 250 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 50
			vertex 240 0 60
			vertex 240 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 50
			vertex 240 10 60
			vertex 240 10 50
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 60
			vertex 250 0 70
			vertex 250 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 60
			vertex 250 10 70
			vertex 250 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 60
			vertex 240 0 70
			vertex 240 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 60
			vertex 240 10 70
			vertex 240 10 60
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 70
			vertex 250 0 80
			vertex 250 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 70
			vertex 250 10 80
			vertex 250 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 70
			vertex 240 0 80
			vertex 240 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 70
			vertex 240 10 80
			vertex 240 10 70
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 80
			vertex 250 0 90
			vertex 250 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 80
			vertex 250 10 90
			vertex 250 10 80
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 90
			vertex 250 0 100
			vertex 250 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 90
			vertex 250 10 100
			vertex 250 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 90
			vertex 240 0 100
			vertex 240 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 90
			vertex 240 10 100
			vertex 240 10 90
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 100
			vertex 250 0 110
			vertex 250 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 100
			vertex 250 10 110
			vertex 250 10 100
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 110
			vertex 250 0 120
			vertex 250 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 110
			vertex 250 10 120
			vertex 250 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 110
			vertex 240 0 120
			vertex 240 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 110
			vertex 240 10 120
			vertex 240 10 110
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 120
			vertex 250 0 130
			vertex 250 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 120
			vertex 250 10 130
			vertex 250 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 120
			vertex 240 0 130
			vertex 240 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 120
			vertex 240 10 130
			vertex 240 10 120
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 130
			vertex 250 0 140
			vertex 250 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 130
			vertex 250 10 140
			vertex 250 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 130
			vertex 240 0 140
			vertex 240 10 140
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 130
			vertex 240 10 140
			vertex 240 10 130
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 140
			vertex 250 0 150
			vertex 250 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 140
			vertex 250 10 150
			vertex 250 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 150
			vertex 250 0 150
			vertex 250 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 150
			vertex 250 10 150
			vertex 240 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 140
			vertex 240 0 150
			vertex 240 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 140
			vertex 240 10 150
			vertex 240 10 140
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 150
			vertex 250 0 150
			vertex 250 10 150
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 150
			vertex 250 10 150
			vertex 240 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 150
			vertex 250 0 160
			vertex 250 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 150
			vertex 250 10 160
			vertex 250 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 150
			vertex 240 0 160
			vertex 240 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 150
			vertex 240 10 160
			vertex 240 10 150
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 160
			vertex 250 0 170
			vertex 250 10 170
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 160
			vertex 250 10 170
			vertex 250 10 160
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 170
			vertex 250 0 180
			vertex 250 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 170
			vertex 250 10 180
			vertex 250 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 180
			vertex 250 0 180
			vertex 250 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 180
			vertex 250 10 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 170
			vertex 240 0 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 170
			vertex 240 10 180
			vertex 240 10 170
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 180
			vertex 250 0 180
			vertex 250 10 180
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 180
			vertex 250 10 180
			vertex 240 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 180
			vertex 250 0 190
			vertex 250 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 180
			vertex 250 10 190
			vertex 250 10 180
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 190
			vertex 250 0 200
			vertex 250 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 190
			vertex 250 10 200
			vertex 250 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 190
			vertex 240 0 200
			vertex 240 10 200
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 190
			vertex 240 10 200
			vertex 240 10 190
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 200
			vertex 250 0 210
			vertex 250 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 200
			vertex 250 10 210
			vertex 250 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 210
			vertex 250 0 210
			vertex 250 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 210
			vertex 250 10 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 200
			vertex 240 0 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 200
			vertex 240 10 210
			vertex 240 10 200
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 210
			vertex 250 0 210
			vertex 250 10 210
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 210
			vertex 250 10 210
			vertex 240 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 210
			vertex 250 0 220
			vertex 250 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 210
			vertex 250 10 220
			vertex 250 10 210
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 220
			vertex 250 0 230
			vertex 250 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 220
			vertex 250 10 230
			vertex 250 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 220
			vertex 240 0 230
			vertex 240 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 220
			vertex 240 10 230
			vertex 240 10 220
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 230
			vertex 250 0 240
			vertex 250 10 240
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 230
			vertex 250 10 240
			vertex 250 10 230
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 240
			vertex 250 0 250
			vertex 250 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 250 0 240
			vertex 250 10 250
			vertex 250 10 240
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 250
			vertex 250 0 250
			vertex 250 10 250
		endloop
	endfacet
	facet normal 0 0 1
		outer loop
			vertex 240 0 250
			vertex 250 10 250
			vertex 240 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 240
			vertex 240 0 250
			vertex 240 10 250
		endloop
	endfacet
	facet normal -1 0 0
		outer loop
			vertex 240 0 240
			vertex 240 10 250
			vertex 240 10 240
		endloop
	endfacet
endsolid exported

```

<p align="center">
  <a href="3D_model_Maze_exemple.stl">
    <img src="https://img.shields.io/badge/Відкрити_STL-3D_модель-blue?style=for-the-badge">
  </a>
</p>
