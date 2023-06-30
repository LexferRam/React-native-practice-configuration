# CREACION DE VARIABLES DE ENTORNO EN MAC:

* Open Terminal
* Run touch ~/.bash_profile; open ~/.bash_profile (is se use zsh se debe crear el archivo .zshrc)
* In TextEdit, add export PATH="$HOME/.rbenv/bin:$PATH"
* Save the .bash_profile file and Quit (Command + Q) Text Edit.
* Run source ~/.bash_profile (ejecutar archivo)

**NOTAS:**
* Hacer cd ~, nos lleva al Home del usuario actual
* Ejecutar ECHO $SHELL para ver que Shell se esta usando

**ENV CONFIGURADO**

```cmd
export PATH="$HOME/.rbenv/bin:$PATH"
export PATH=/Users/lexferramirezpolidor/Library/Android/sdk:/opt/homebrew/bin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Library/Apple/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin
export JAVA_HOME="/Applications/Android Studio.app/Contents/jbr/Contents/Home" 

export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools

export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
```