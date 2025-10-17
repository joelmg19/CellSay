¡Bienvenido al proyecto CellSay!
Sigue estos pasos para configurar tu entorno de desarrollo correctamente y ejecutar la aplicación. 💻📱

🧩 1️⃣ Instalar Flutter

Descarga Flutter desde la página oficial:
👉 https://flutter.dev/docs/get-started/install

Descomprime el archivo donde prefieras (por ejemplo, C:\src\flutter en Windows).

Asegúrate de tener Git instalado y disponible en tu terminal.
Puedes verificar con:

git --version

⚙️ 2️⃣ Configurar las variables de entorno (PATH)

Copia la ruta donde instalaste Flutter, por ejemplo:

C:\src\flutter\bin


Añádela a las Variables de entorno → Path del sistema.

Cierra y vuelve a abrir tu terminal, luego verifica la instalación con:

flutter doctor


✅ Si todo está correcto, verás los componentes instalados y configurados.

📦 3️⃣ Instalar dependencias del proyecto

Abre una terminal en la carpeta del proyecto (por ejemplo, CellSay/).

Ejecuta el siguiente comando para descargar las dependencias necesarias:

flutter pub get

🧰 4️⃣ Instalar los plugins de Flutter y Dart

💡 Puedes usar Android Studio, Visual Studio Code o tu editor favorito.

En Android Studio:

Abre File → Settings → Plugins

Busca e instala:

🔹 Flutter

🔹 Dart

En Visual Studio Code:

Abre la pestaña de extensiones (Ctrl + Shift + X)

Busca e instala:

🧩 Flutter

🧩 Dart

▶️ 5️⃣ Ejecutar el proyecto

Conecta tu dispositivo físico o abre un emulador.

Ejecuta el siguiente comando desde la carpeta raíz del proyecto:

flutter run lib/main.dart


¡Y listo! 🎉
Tu aplicación debería iniciar correctamente.

🧠 Consejos útiles

Si tienes problemas, ejecuta:

flutter doctor -v


para ver los detalles de la configuración.

Mantén Flutter actualizado:

flutter upgrade
