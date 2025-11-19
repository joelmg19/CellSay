<h1>🚀 Guía de instalación y ejecución del proyecto Flutter</h1>

<p>¡Bienvenido al proyecto <strong>CellSay</strong>!<br>
Sigue estos pasos para configurar tu entorno de desarrollo correctamente y ejecutar la aplicación. 💻📱</p>

<hr>

<h2>🧩 1️⃣ Instalar Flutter</h2>
<ol>
  <li>Descarga Flutter desde la página oficial:<br>
  👉 <a href="https://flutter.dev/docs/get-started/install" target="_blank">https://flutter.dev/docs/get-started/install</a></li>
  <li>Descomprime el archivo donde prefieras (por ejemplo, <code>C:\src\flutter</code> en Windows).</li>
  <li>Asegúrate de tener <strong>Git</strong> instalado y disponible en tu terminal.<br>
  Puedes verificar con:
  <pre><code>git --version</code></pre></li>
</ol>

<hr>

<h2>⚙️ 2️⃣ Configurar las variables de entorno (PATH)</h2>
<ol>
  <li>Copia la ruta donde instalaste Flutter, por ejemplo:<br>
  <pre><code>C:\src\flutter\bin</code></pre></li>
  <li>Añádela a las <strong>Variables de entorno → Path</strong> del sistema.</li>
  <li>Cierra y vuelve a abrir tu terminal, luego verifica la instalación con:
  <pre><code>flutter doctor</code></pre>
  ✅ Si todo está correcto, verás los componentes instalados y configurados.</li>
</ol>

<hr>

<h2>📦 3️⃣ Instalar dependencias del proyecto</h2>
<ol>
  <li>Abre una terminal en la carpeta del proyecto (por ejemplo, <code>CellSay/</code>).</li>
  <li>Ejecuta el siguiente comando para descargar las dependencias necesarias:
  <pre><code>flutter pub get</code></pre></li>
</ol>

<hr>

<h2>🧰 4️⃣ Instalar los plugins de Flutter y Dart</h2>
<p>💡 Puedes usar <strong>Android Studio</strong>, <strong>Visual Studio Code</strong> o tu editor favorito.</p>

<h3>En Android Studio:</h3>
<ul>
  <li>Abre <strong>File → Settings → Plugins</strong></li>
  <li>Busca e instala:
    <ul>
      <li>🔹 Flutter</li>
      <li>🔹 Dart</li>
    </ul>
  </li>
</ul>

<h3>En Visual Studio Code:</h3>
<ul>
  <li>Abre la pestaña de extensiones (<code>Ctrl + Shift + X</code>)</li>
  <li>Busca e instala:
    <ul>
      <li>🧩 Flutter</li>
      <li>🧩 Dart</li>
    </ul>
  </li>
</ul>

<hr>

<h2>▶️ 5️⃣ Ejecutar el proyecto</h2>
<ol>
  <li>Conecta tu dispositivo físico o abre un emulador.</li>
  <li>Ejecuta el siguiente comando desde la carpeta raíz del proyecto:
  <pre><code>flutter run lib/main.dart</code></pre></li>
  <li>¡Y listo! 🎉 Tu aplicación debería iniciar correctamente.</li>
</ol>

<hr>

<h2>🧠 Consejos útiles</h2>
<ul>
  <li>Si tienes problemas, ejecuta:
    <pre><code>flutter doctor -v</code></pre>
    para ver los detalles de la configuración.
  </li>
  <li>Mantén Flutter actualizado:
    <pre><code>flutter upgrade</code></pre>
  </li>
</ul>

<hr>

<p>✨ <strong>Ahora ya puedes empezar a trabajar en tu proyecto Flutter sin problemas.</strong></p>
