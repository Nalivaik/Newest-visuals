# Newest-visual

Клиентский visual/HUD-мод для Minecraft 1.21.11 на Fabric.

## Возможности

* кастомный прицел с редактором, hit color и отображением HP цели после удара;
* HUD с watermark, информацией, эффектами, списком биндов, Target HUD и TNT timer;
* плавный `ChinaHat` над невидимыми игроками с оптимизированной проверкой видимости;
* ESP, NameTags, Shader ESP, World Tweaks, Gamma и другие render-модули;
* кастомизация рук, swing animation, частиц, trails и world cubes;
* музыкальный HUD, темы и белая тема `White`;
* drag-позиционирование HUD через открытый чат;
* автоспринт и Item Scroller.

## Установка

1. Установите Minecraft `1.21.11`, Fabric Loader и Fabric API.
2. Скопируйте JAR-файл в папку `mods`.
3. Запустите клиент через Fabric.

Готовый артефакт после сборки:

```text
build/libs/Newest-visual-1.0-SNAPSHOT.jar
```

## Сборка из исходного кода

Необходимы Java 21 и Gradle Wrapper:

```bash
./gradlew clean build
```

Для запуска клиента в среде разработки:

```bash
./gradlew runClient
```

## Управление

* Откройте ClickGUI назначенной клавишей.
* Включите `Inter Face`, чтобы видеть и перемещать HUD-элементы.
* Откройте чат и перетаскивайте HUD-элементы левой кнопкой мыши.
* Позиции и настройки сохраняются в конфигурации клиента.

## Структура

* `src/client/java/ru/white/module/impl/render` — visual-модули;
* `src/client/java/ru/white/module/impl/display` — HUD и интерфейс;
* `src/client/java/ru/white/module/impl/display/interfaceimpl` — отдельные HUD-элементы;
* `src/client/resources` — Fabric metadata, mixins и ресурсы.

## Лицензия

All Rights Reserved. Условия использования и распространения определяет владелец проекта.
