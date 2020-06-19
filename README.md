# Jailbreak Repo Web Viewer
## Generate a Cydia/Sileo Repository on a Webpage


** Incluye: **
* All Package Viewer
* Clasificación de categoría de paquete
* Visor de categoría de paquete
* Sileo Depiction Viewer
* IU de estilo iOS
* Animaciones suaves

¡Esto se puede usar para generar una representación de WebView para Cydia usando solo su archivo SileoDepiction.json!

### Repo Viewer


Ejemplo disponible: [Here](https://drandroidsv.github.io//repo/?repo=http://repo.mastersv.info/)
<br/><br/>
Este es un gran lugar para configurar la página de destino para su repositorio. Se encargará automáticamente de agregar todos sus paquetes, así como de agregar enlaces a sus respectivas páginas de representación con todos los argumentos disponibles.
<br/>
Simplemente especifique la URL de su repositorio en las direcciones.
Por ejemplo, puede ver mi repositorio de Cydia usando el siguiente argumento:
```
https://drandroidsv.github.io//repo/?repo=http://repo.mastersv.info/
```

| Property      | Description |
| ------------- | ------------- |
| repo          | URL of Cydia Repo  |

### Depiction Viewer

Example Available: [Here](https://pinpal.github.io/Sileo-Depiction-WebViews/?json=https://raw.githubusercontent.com/PINPAL/Sileo-Depiction-WebViews/996b2b375b0c61bcb3af61ee518488c1c670fccb/packages/shortlook/config.json&name=Shortlook&dev=Dynastic&price=3.99&icon=https://raw.githubusercontent.com/PINPAL/Sileo-Depiction-WebViews/996b2b375b0c61bcb3af61ee518488c1c670fccb/packages/shortlook/icon.png&section=Tweaks)
<br/><br/>
Simply Specify your SileoDepiction JSON file in the address.
You can also add other optional arguements seperated by an and (&) symbol for a more complete depiction eg:
```
https://pinpal.github.io/Sileo-Depiction-WebViews/?json=https://pinpal.github.io/package/Example/SileoDepiction.json&name=Example&dev=PINPAL
```

| Property      | Description |
| ------------- | ------------- |
| json          | URL of SileoDepiction JSON file  |
| name          | Tweak Title  |
| dev          | Tweak Developer  |
| price          | Tweak Price (Integer)  |
| section          | Tweak Section (Eg: Tweaks/Themes)  - used to generate generic icon|
| icon          | Tweak Icon - overrides tweak section  |
