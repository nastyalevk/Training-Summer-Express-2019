## Задачи

- Для моделирования лабиринта используется двумерный массив, в котором значение 0 - клетка, -1 - стена. Предполагается, что в лабиринте всегда есть вход и выход.  Возможные усложнения входных данных
  - нет выхода (бросается исклбчение);
  - два и более выходов;
  - поиск кратчайшего пути в лабиринте, где два и более возможных пути прохождения лабиринта.

Например, для моделирования лабиринта на рисунке

![](https://github.com/AnzhelikaKravchuk/Training-Summer-Express-2018/blob/master/Day%2010/Maze.png)

используется матрица

             {
                { -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1 },
                {  0,  0, -1,  0,  0,  0,  0,  0, -1,  0,  0, -1 },
                { -1,  0, -1,  0, -1, -1,  0,  0, -1, -1,  0, -1 },
                { -1,  0, -1,  0,  0, -1,  0,  0,  0,  0,  0, -1 },
                { -1,  0, -1, -1,  0, -1, -1, -1, -1, -1, -1, -1 },
                { -1,  0, -1,  0,  0, -1,  0, -1,  0,  0,  0, -1 },
                { -1,  0, -1,  0, -1, -1,  0,  0,  0, -1,  0, -1 },
                { -1,  0, -1,  0,  0,  0,  0, -1, -1, -1,  0, -1 },
                { -1,  0, -1,  0, -1,  0,  0, -1,  0, -1,  0, -1 },
                { -1,  0, -1, -1, -1, -1,  0, -1,  0, -1,  0, -1 },
                { -1,  0,  0,  0,  0,  0,  0, -1,  0,  0,  0,  0 },
                { -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1 }
            }
            
Реализовать алгоритм прохождения данного лабиринта (поместить решение в проект [MazeLibrary.dll](https://github.com/AnzhelikaKravchuk/ExtTraining.Summer.2018.1)). Протестировать построенный алгоритм на предложенных тест-кейсах (проект [MazeLibrary.Tests.dll](https://github.com/AnzhelikaKravchuk/ExtTraining.Summer.2018.1)). Для тех входных данных, где возможна вариационность пути прохождения лабиринта, возможны свои тест-кейсы.

- **Предложить альтернативную модель для решения поставленной задачи.**
