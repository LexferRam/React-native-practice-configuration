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

* 