Куда поведёт Орди? — проект Android-приложения

Это Android Studio-проект, который упаковывает исходный HTML в Android WebView.

Как получить APK:
1. Установите Android Studio (https://developer.android.com/studio).
2. Откройте в Android Studio папку OrdiTula.
3. Дождитесь синхронизации Gradle и установки Android SDK Platform 35 (если будет предложено).
4. Для APK: Build → Build Bundle(s) / APK(s) → Build APK(s).
5. Готовый файл появится в app/build/outputs/apk/debug/app-debug.apk.

Важно:
- Для Tailwind CSS и шрифтов исходная страница загружает ресурсы из интернета.
- Яндекс Карты открываются по внешним ссылкам.
- Прогресс и пользовательские маршруты сохраняются в локальном хранилище приложения.
