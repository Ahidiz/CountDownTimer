CountdownTimer — готовый проект (Narwhal 2025.1.2)

Инструкция:
1. Распакуй ZIP.
2. (Опционально) Вставь свой звук в app/src/main/res/raw/alert.mp3 — иначе звук не будет воспроизводиться.
3. Открой Android Studio Narwhal -> File -> Open -> выбери папку 'CountdownTimer_FinalProject'.
4. Дай выполнить Sync Project with Gradle Files.
5. Либо собери локально: Build -> Build APK(s). APK появится в app/build/outputs/apk/debug/app-debug.apk
6. Либо залей проект в GitHub в ветку main — workflow .github/workflows/android-build.yml соберёт APK автоматически, и его можно скачать из Actions -> последний job -> Artifacts.

Примечания:
- Service и Activity частично разделены; для полного фонового воспроизведения при закрытии Activity можно улучшить взаимодействие. Но шаблон работает и собирается.
- Если хочешь, я могу вложить громкий mp3 в проект и пересобрать ZIP.
