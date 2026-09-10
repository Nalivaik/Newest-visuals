# Newest-visuals
# Newest-visual

Клієнтський visual/HUD-мод для Minecraft 1.21.11 на Fabric.

## Можливості

- кастомний приціл із редактором, hit color та HP цілі після удару;
- HUD із watermark, інформацією, ефектами, bind-листом, Target HUD і TNT timer;
- плавний `ChinaHat` над невидимими гравцями з оптимізованою перевіркою видимості;
- ESP, NameTags, Shader ESP, World Tweaks, Gamma та інші render-модулі;
- кастомізація рук, swing animation, частинок, trails і world cubes;
- музичний HUD, теми та біла тема `White`;
- drag-позиціонування HUD через відкритий чат;
- автоспринт і Item Scroller.

## Встановлення

1. Встановіть Minecraft `1.21.11`, Fabric Loader та Fabric API.
2. Скопіюйте JAR-файл у папку `mods`.
3. Запустіть клієнт через Fabric.

Готовий артефакт після збірки:

```text
build/libs/Newest-visual-1.0-SNAPSHOT.jar
```

## Збірка з вихідного коду

Потрібні Java 21 і Gradle Wrapper:

```bash
./gradlew clean build
```

Для запуску клієнта в середовищі розробки:

```bash
./gradlew runClient
```

## Керування

- Відкрийте ClickGUI призначеною клавішею.
- Увімкніть `Inter Face`, щоб бачити та переміщати HUD-елементи.
- Відкрийте чат і перетягуйте HUD-елементи лівою кнопкою миші.
- Позиції та налаштування зберігаються конфігурацією клієнта.

## Структура

- `src/client/java/ru/white/module/impl/render` — visual-модулі;
- `src/client/java/ru/white/module/impl/display` — HUD та інтерфейс;
- `src/client/java/ru/white/module/impl/display/interfaceimpl` — окремі HUD-елементи;
- `src/client/resources` — Fabric metadata, mixins та ресурси.

## Ліцензія

All Rights Reserved. Умови використання та розповсюдження визначає власник проєкту.
