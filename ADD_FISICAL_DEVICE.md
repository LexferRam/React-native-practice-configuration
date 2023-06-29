## Guia oficial <https://reactnative.dev/docs/running-on-device>

## ANDROID
---

<b>Configuración en el dispositivo (Redmi 7A)</b>

* habilitar modo desarrollador en el dispositivo
(configuracion > acerca del telefono > presionar varias veces en **versión MIUI** para activar el modo desarrollador )

* Habilitar opcion de debugger (configuracion > ajustes adicionales > opciones de desarrollador > activar opcion (**opciones de desarrollador**) y (**Depuracion USB**))

* verificar que la pc reconoce el dispositivo
```cmd
adb devices
```

* Conectar el dispositivo mediante USB a la pc

* Ejecutar proyecto con 
```cmd
npx react-native run-android
```
* **Aditional configuration**
- Activate autofill (Additional Settings, Languages and Input, and then set Auto-fill service to Google)
- developer option > reset to default values 
- Turn off "MIUI optimization" 

* If you wnat to run on a speficific device

```cmd
 # get the availables devices
 adb devices

 # run command on a specific device Id
 npx react-native run-android --deviceId deviceId
```


## IPHONE
---
<b>Configuración en el dispositivo</b>

* Activar developer mode ==> settings > privacy&Security > developer Mode(On)
* Untrusted Enterprise Developer on iPhone ==> Settings > General > Device Management(Developer App)
* Conectar el iPhone directo a la pc
* ejecutar, para asegurar tener la ultima version: 
```cmd
npx react-native run-ios
```
* open .xcworkspace, within it using Xcode. ubicado en la carpeta ios > .xcworkspace
* xCode > preference > ir a tabs de accounts y agregar cuenta de AppleID
* seleccionar tab "SignIn and capabilities" 
* En las barra superior desplegar los dispositivos y seleccionar el iPhone
* Darle al icono de "Play"