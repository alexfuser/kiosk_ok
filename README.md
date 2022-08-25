
### Usage
1. Restablecer el telefono
2. No loguearte con tu cuenta de google en el telefono
3. Instalar el apk
```bash
$ adb install path/to/kiosk.apk
```
4. Poner modo administrador u owner
```bash
$ adb shell dpm set-device-owner pl.snowdog.kiosk/.MyDeviceAdminReceiver
```
