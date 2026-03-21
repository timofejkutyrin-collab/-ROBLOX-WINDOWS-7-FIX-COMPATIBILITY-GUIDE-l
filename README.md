# -ROBLOX-WINDOWS-7-FIX-COMPATIBILITY-GUIDE-l

ВАЖНО: ПЕРЕД УСТАНОВКОЙ
1. ОТКЛЮЧИТЕ АНТИВИРУС (особенно 360 Total Security).
   Причина: У компонентов VxKex отсутствует цифровая подпись. Антивирусы блокируют их работу, принимая за угрозу.
2. УБЕДИТЕСЬ В НАЛИЧИИ ОБНОВЛЕНИЯ KB4474419 (поддержка SHA-2). Без него драйверы античита не запустятся.
3. ПРЕДОСТАВЬТЕ ПРАВА: При установке и запуске всегда выбирайте «Да» в запросах системы на внесение изменений (UAC).

ИНСТРУКЦИЯ:

1. УСТАНОВКА ЭМУЛЯТОРА
   - Запустите VxKex_Setup.exe.
   - Подтвердите установку и перезагрузите ПК.

2. НАСТРОЙКА ИНСТАЛЛЕРА ROBLOX
   - Правой кнопкой на RobloxPlayerInstaller.exe -> Свойства -> Вкладка VxKex.
   - Поставьте галочку "Enable VxKex for this program".
   - ОБЯЗАТЕЛЬНО поставьте галочку "Report a different version of Windows".
   - В списке выберите "Windows 10" (билд 19044 или выше).
   - Нажмите ОК и запустите установку.

3. ИСПРАВЛЕНИЕ ОШИБКИ DLL
   Если игра выдает ошибку api-ms-win-eventlog-legacy-l1-1-0.dll:
   - Скопируйте файл api-ms-win-eventlog-legacy-l1-1-0.dll из этого репозитория.
   - Перейдите в папку: C:\Users\[Ваше_Имя]\AppData\Local\Roblox\Versions\version-[код]\
   - Вставьте файл в папку, где лежит RobloxPlayerBeta.exe.

4. ДОПОЛНИТЕЛЬНО
   Если ошибка ОС сохраняется при запуске самой игры, повторите шаги из пункта 2 для файла RobloxPlayerBeta.exe в папке Versions.
*ВАЖНО*:перед установкой Roblox по ссылке установите godbyeDPI,ссылку на который я тоже оставлю
правка:меня прибьют за авторские права если я опубликую сразу все готовое поэтому держите ссылки на скачивание:
roblox:https://www.roblox.com/download/client
VxKex:https://github.com/i486/VxKex/releases?ysclid=mn0rtictng79424935
godbyeDPI:https://github.com/ValdikSS/GoodbyeDPI/releases/?ysclid=mn0yd8fvtz622442272
==================================================
# -ROBLOX-WINDOWS-7-FIX-COMPATIBILITY-GUIDE-l

IMPORTANT: BEFORE INSTALLATION
1. DISABLE YOUR ANTIVIRUS (especially 360 Total Security).
   Reason: VxKex components lack digital signatures. Antivirus programs block them, mistaking them for threats.
2. ENSURE YOU HAVE UPDATE KB4474419 (SHA-2 support). Without it, anti-cheat drivers will not run.
3. GRANT PERMISSIONS: When installing and running, always select "Yes" when the system prompts for changes (UAC).

INSTRUCTIONS:

1. EMULATOR INSTALLATION
   - Run VxKex_Setup.exe.
   - Confirm installation and restart your PC.

2. CONFIGURE ROBLOX INSTALLER
   - Right-click on RobloxPlayerInstaller.exe → Properties → VxKex Tab.
   - Check the box "Enable VxKex for this program".
   - MUST check the box "Report a different version of Windows".
   - From the list, select "Windows 10" (build 19044 or higher).
   - Click OK and run the installation.

3. FIX DLL ERROR
   If the game shows an error api-ms-win-eventlog-legacy-l1-1-0.dll:
   - Copy the file api-ms-win-eventlog-legacy-l1-1-0.dll from this repository.
   - Navigate to folder: C:\Users\[Your_Name]\AppData\Local\Roblox\Versions\version-[code]\
   - Paste the file in the folder where RobloxPlayerBeta.exe is located.

4. ADDITIONAL
   If the OS error persists when running the game itself, repeat the steps from section 2 for the RobloxPlayerBeta.exe file in the Versions folder.
IMPORTANT: Before installing Roblox from the link, install godbyeDPI, which I will also provide a link to
edit: I'll get sued for copyright infringement if I publish everything at once, so here are the download links:
roblox:https://www.roblox.com/download/client VxKex:https://github.com/i486/VxKex/releases?ysclid=mn0rtictng79424935
godbyeDPI:https://github.com/ValdikSS/GoodbyeDPI/releases/?ysclid=mn0yd8fvtz622442272
==================================================
