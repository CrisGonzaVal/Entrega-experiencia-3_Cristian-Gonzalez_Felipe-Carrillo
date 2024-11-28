# **Entrega Experiencia 3**

**Autor**: Cristian Gonzalez Felipe-Carrillo

---

## **Requisitos para instalar**

1. **Node.js**: Versión 20  
   [Descargar Node.js](https://nodejs.org/)
2. **Angular**: Versión 18  
   [Documentación de Angular](https://angular.io/docs)
3. **Ionic Framework**: Versión 7.2  
   [Instalar Ionic](https://ionicframework.com/docs/intro/cli)

---

## **Pasos para crear el proyecto Ionic**

1. Abre una terminal y ejecuta el siguiente comando:
   ```bash
   ionic start MyApp
Durante la configuración, selecciona las siguientes opciones:
ngmodule
Framework: Angular
Template: Blank
Una vez creado el proyecto, reemplaza la carpeta src con la carpeta proporcionada en esta entrega.
Implementación de captura QR
Instalar dependencias necesarias
Instala el paquete para la captura de QR:
bash
Copiar código
npm install @zxing/browser
Instala el generador de códigos QR:
bash
Copiar código
npm install angularx-qrcode
Ejecutar en Android Studio
Instala Capacitor para Android:
bash
Copiar código
npm install @capacitor/android
Agrega soporte para Android:
bash
Copiar código
npx cap add android
Construye el proyecto:
bash
Copiar código
ionic build
Sincroniza los cambios con Capacitor:
bash
Copiar código
ionic capacitor sync android
Copia los archivos a la carpeta de Android:
bash
Copiar código
ionic capacitor copy android
Abre el proyecto en Android Studio:
bash
Copiar código
ionic capacitor open android
Uso del JSON alojado
El proyecto utiliza un archivo JSON alojado en la siguiente URL:
https://repodata-rqrl.onrender.com

Notas importantes
Puedes reinstalar las dependencias del proyecto con:
bash
Copiar código
npm install
Para cualquier problema con los paquetes o configuraciones, revisa la documentación oficial de Ionic, Angular o Capacitor.
¡Gracias por revisar mi entrega!

go
Copiar código

Copia y pega este contenido en un archivo llamado `README.md` y colócalo en la raíz de tu proyecto.
