# H3VR_RUSSIAN_CORE
H3VR — базовый русский перевод (меню + спавнер)
================================================

❓ЧТО ВНУТРИ
----------
- H3VR_Russian_Core.txt — ~410 строк перевода (меню, настройки, спавнер)
- XUnity Auto Translator 4.21.0 — движок перевода (полная установка)
- AutoTranslatorConfig.ini — уже настроен на Language=ru
- Пустые _Substitutions.txt / _Preprocessors.txt / _Postprocessors.txt

❌НЕ ПЕРЕВЕДЕНО (намеренно):
- названия конкретного оружия (Glock, AK и т.д.)
- названия модов
- тексты игровых режимов (Take and Hold, Meat Fortress и др.)

✅ЗАВИСИМОСТИ
-----------
Нужен только BepInEx Pack for H3VR (запускает моды):
https://h3vr.thunderstore.io/package/BepInEx/BepInExPack_H3VR/

H3VR Localization Base ставить НЕ нужно — XUnity уже внутри этого архива.

📂УСТАНОВКА
---------
1. Установите BepInEx Pack for H3VR в папку игры (G:\H3VR или ваш путь).

2. Скопируйте содержимое папки BepInEx из этого архива в папку игры,
   объединив с существующей BepInEx. Должно получиться:

   <Игра>\BepInEx\core\XUnity.Common.dll
   <Игра>\BepInEx\plugins\XUnity.AutoTranslator\...
   <Игра>\BepInEx\plugins\XUnity.ResourceRedirector\...
   <Игра>\BepInEx\config\AutoTranslatorConfig.ini
   <Игра>\BepInEx\config\Translation\H3VR_Russian_Core.txt

3. Запустите игру.

⚠️ВАЖНО
-----
- Файл НЕ заменяет оригинальные .assets — перевод идёт через плагин
  во время игры.
- Чтобы вернуть английский — удалите папки plugins\XUnity.*
  и config\Translation\.

ФОРМАТ ФАЙЛА ПЕРЕВОДА
---------------------
Английский текст=Русский перевод

Символы \n — перенос строки, их нельзя удалять или менять.
