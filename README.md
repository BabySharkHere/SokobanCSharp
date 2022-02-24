# SokobanCSharp
Игра сокобан на c#

1. Чтобы добавить/изменить уровень: заходим в папку WindowsFormsApp1 -> bin -> Debug -> Lvl -> Выбираем необходимый нам уровень, 
открываем его с помощью любого редактора текстовых документов и изменяем.
Описание матрицы: 0 -- игровое поле; 1 -- стартовое положение персонажа; 2 -- стена; 3 -- ящики; 4 -- точка, в которую необходимо принести ящики.
Чтобы добавить новый уровень необходимо в эту папку добавить новый текстовый файл и в Form1.cs в функции buttonSelect_Click добавить новый кейс 
и прописать путь до этого уровня.

2. Текстуры изменяются в папке WindowsFormsApp1 -> bin -> Debug -> textures.

3. Правила игры описаны в игре.

4. Чтобы начать игру необходимо выбрать уровень, нажать добавить и потом играть. Как уровень будет пройден, будет возможность выйти в главное меню.
Рекорд -- минимальное количество шагов, затраченное на прохождение уровня. 
