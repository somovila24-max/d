# Fluent Motion (Fabric, Minecraft 1.21.11, Yarn)

Клиентский мод: новая анимация ходьбы/бега, наклоны в поворотах, шаги при развороте на месте,
прыжок/падение/приземление, IK ног по высоте блоков, отодвигание рук от стен.

## Сборка
1. Установи JDK 21 или новее (CI использует 25, как шаблон Fabric).
2. Gradle wrapper уже в проекте (gradlew / gradlew.bat).
3. Версии в gradle.properties сверены с шаблоном Fabric для 1.21.11.
4. `./gradlew build` -> build/libs/fluentmotion-1.0.0.jar в папку mods.
   Тест: `./gradlew runClient` (F5 — вид от третьего лица).

Настройки: config/fluentmotion.json (после первого запуска). Мод только клиентский, сервер не нужен.
