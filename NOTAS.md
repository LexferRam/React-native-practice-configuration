# ENV SETUP

## step by step configuration guide (official documentation)

<https://reactnative.dev/docs/environment-setup>

## If you are having trouble with iOS, try to reinstall the dependencies by running:

* **cd ios** to navigate to the ios folder.
* **bundle install** to install Bundler.
* **bundle exec pod install** to install the iOS dependencies managed by CocoaPods.

## Show availables devices

```cmd
xcrun simctl list devices
```

## Execute using a specific device

```cmd
npx react-native run-ios --simulator="iPhone 8"
```

## Mostrar lista de dispositivos conextados

```cmd
adb devices
```

## React Native

React Native is a framework that allows you to build native mobile apps using JavaScript.
With React Native, you create one codebase that works on both Android and iOS. And it doesn’t just “work”—it compiles to native Java and Swift code. Specifically, React Native creates a bridge between web UI components and their native Java/Swift counterparts.

**Aplicaciones híbridas**
Las aplicaciones híbridas son esencialmente aplicaciones web que se han colocado en un shell de aplicación nativo,
se ejecutan en algo similar a un navegador web dentro de la aplicación, por esa razón no son muy recomendables para 
proyectos de uso general ya que el rendimiento no es el más óptimo.

**Aplicaciones bridge**
existen otro tipo de tecnologías que permiten exportar para las dos plataformas sin perder rendimiento o fluidez y así 
no perjudicar la experiencia del usuario. Este tipo de aplicaciones es conocida como “bridge”. Esta tecnología crea un 
puente entre el código nativo y el código escrito en Javascript. Lo solución llamada React Native ha creado cada componente 
con una contraparte nativa, de esa forma, la aplicación se está ejecutando de forma nativa y los controles son los nativos.

En la actualidad, las tecnologías híbridas están siendo reemplazadas por las tecnologías “bridge” (como React Native) por todos 
los beneficios que estas traen, por eso, si vas a empezar un proyecto móvil, te recomendamos conversar con tu equipo sobre las 
tecnologías bridge, es una muy buena opción que trae beneficios en inversión, tiempo, gestión y lo mejor de todo, el rendimiento 
y la experiencia son muy buenos.