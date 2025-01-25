# How-to-create-an-SDL-project-in-Visual-Studio
How to create an SDL project in Visual Studio

1. Свойства конфигурации -> Каталоги VC++ -> Включаемые каталоги -> `"\SDL2\include"`
2. Компоновщик -> Все параметры -> `"Дополнительные зависимости"` -> добавить -> 
   `SDL2.lib`
   `SDL2main.lib`
3. Компоновщик -> Все параметры -> `"Дополнительные каталоги библиотек"` -> добавить -> `\SDL2\lib\x64`
