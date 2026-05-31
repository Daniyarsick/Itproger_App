# Itproger App

Учебное Android-приложение на Kotlin, сделанное как практика базовой работы с интерфейсом, списком и обработкой пользовательского ввода. Проект показывает простой сценарий: пользователь вводит текст, добавляет его в список и может удалить элемент нажатием.

## Возможности

- Ввод текста через `EditText`.
- Добавление новой записи кнопкой.
- Отображение записей в `ListView`.
- Удаление записи нажатием на элемент списка.
- Toast-уведомление после удаления.

## Технологии

- Kotlin
- Android SDK
- AppCompat
- ConstraintLayout
- Material Components
- Gradle Kotlin DSL

## Структура проекта

```text
app/src/main
├── AndroidManifest.xml
├── java/com/example/itprogerapp
│   └── MainActivity.kt
└── res/layout
    └── activity_main.xml
```

`MainActivity.kt` содержит основную логику экрана: связывает `EditText`, `Button` и `ListView`, создает адаптер и обрабатывает добавление/удаление элементов.

## Сборка

Требования:

- Android Studio или Android SDK
- JDK 17
- Gradle Wrapper из репозитория

Команда сборки:

```bash
./gradlew assembleDebug
```

На Windows:

```powershell
.\gradlew.bat assembleDebug
```

APK после сборки:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Что можно улучшить

- Заменить `ListView` на `RecyclerView`.
- Добавить сохранение данных между запусками приложения.
- Очистить поле ввода после добавления записи.
- Добавить проверку пустых строк и сообщение об ошибке.
- Обновить интерфейс под Material Design.

## Статус

Учебный проект для демонстрации базовых навыков Android-разработки на Kotlin: работа с layout, обработчиками событий, адаптером списка и простым пользовательским сценарием.
