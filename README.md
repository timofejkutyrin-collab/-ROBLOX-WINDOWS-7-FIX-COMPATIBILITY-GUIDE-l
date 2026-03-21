# -ROBLOX-WINDOWS-7-FIX-COMPATIBILITY-GUIDE-l (ru)

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
# -ROBLOX-WINDOWS-7-FIX-COMPATIBILITY-GUIDE-l (eng)

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
edit: I'll get sued for copyright infringement if I publish everything at once, so here are the download links:
roblox:https://www.roblox.com/download/client VxKex:https://github.com/i486/VxKex/releases?ysclid=mn0rtictng79424935
==================================================
#
-中文 (ZH)
**重要提示：网络访问**
如果遇到访问受限或下载缓慢，建议使用 **Tor 浏览器** 访问以下链接。

**安装步骤：**
1. **杀毒软件**：请务必关闭（尤其是 **360安全卫士**），以免拦截 VxKex。
2. **系统更新**：确保已安装 **KB4474419**。
3. **模拟器**：运行 `VxKex_Setup.exe` 并重启。
4. **设置**：右键点击 `RobloxPlayerInstaller.exe` -> 属性 -> VxKex 选项卡。勾选开启并选择 **Windows 10**。
5. **DLL 修复**：如果提示 `api-ms-win-eventlog-legacy-l1-1-0.dll` 丢失，请将本仓库中的 DLL 复制到 Roblox 的 Versions 文件夹中。

---

## 🔗 DOWNLOAD LINKS / 下载链接
* **Roblox**: [Official Download](https://www.roblox.com/download/client)
* **VxKex**: [Official Releases](https://github.com/i486/VxKex/releases)
* **GoodbyeDPI**: [Official Releases](https://github.com/ValdikSS/GoodbyeDPI/releases)
* **Tor Browser**: [Official Site](https://www.torproject.org/)

---
*Disclaimer: This repository does not host game files. It provides compatibility tools and instructions only.*
