# SetHome
Скрипт для плагина Script Minecraft чтобы устанавливать /sethome

# Как использовать
1.	Сохраните код в файл с расширением .sk в папке скриптов (plugins/Skript/scripts/).
	2.	Перезагрузите скрипты с помощью команды /sk reload all на сервере.

# Требования:

	1.	Установленный плагин Skript на сервере.
	2.	Установленный плагин SkBee для работы с NBT, если требуется проверка на предмет в руке.

# Объяснение:

	1.	/sethome: Устанавливает позицию дома для игрока, если у него еще нет установленного дома.
	2.	/home: Проверяет, держит ли игрок аметистовый кристалл в руке, затем ждет 10 секунд и телепортирует игрока на сохраненную позицию дома, если игрок продолжает держать кристалл.
	3.	/delhome: Удаляет позицию дома для игрока, если он установлен.