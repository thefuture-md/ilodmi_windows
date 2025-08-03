Ilodmi Suite - Beta  v2.0
Aclaración. este programa está únicamente en español. esto dado a que está pensado para una comunidad hispanohablante, y no creo hacer una  adaptación a otros idiomas no, por ahora.
Esta herramienta te permite realizar tareas básicas como editar texto o cerrar procesos del sistema de forma rápida y accesible.
Desarrollador:
https://the-future.kesug.com
Casi todo se maneja con la tecla Tabulador. Cuando hay un menú, como el de selección de procesos, se navega con las teclas de flecha arriba y abajo.
1. 
Editor de Texto: Permite escribir, guardar y abrir archivos .txt fácilmente.
Si utilizamos la tecla  alt, podremos abrir y guardar archivos.
2. 
Mata Procesos: Elige un proceso en ejecución y termina su tarea. Si seleccionás explorer.exe, y presionás enter en reiniciar explorer, se reinicia automáticamente.
3. 
Juegos. En esta opción temporalmente solo hay un juego, el cual no cuenta con una lectura automática al ejecutar acciones. Para leer tu historial navega con tabulador hasta el historial, el cual está indicado con las opciones iniciales del juego. Con flechas arriba y abajo podrán leer el historial.
4. 
YouTube. Aquí se colocó un navegador embebido exclusivamente para YouTube. No podemos acceder a otros sitios. Aviso importante: Pueden enfocar esto de 2 formas. La más simple es presionar alt tab y volver a enfocar, o con el OCR. Pueden iniciar sesión en YouTube, los datos se guardarán como en cualquier navegador chromium.
Nota de seguridad importante: El programa en su código fuente no tiene alguna redirección a una web propia para recopilación de datos, Logramos el acceso a YouTube con wx.html2.WebView, utilizando un navegador embebido. Para mayor transparencia, a continuación se dejará el fragmento de código utilizado, y podemos comprobar por nosotros mismos que es algo ampliamente usado.
self.browser = wx.html2.WebView.New(self.panel)
self.browser.LoadURL("https://www.youtube.com")
5. 
Salir: Opción para cerrar el programa de forma segura desde el menú principal.
Importante: En el gestor de procesos, presiona la tecla Enter sobre el botón matar proceso para cerrarlo.
Aviso.
En mata procesos están los procesos del sistema también, por lo tanto, no me hago responsable de las acciones que cada usuario tome, pero si que puedo decirles que solo manipulen procesos que ustedes conozcan y sepan que hacen, y si el administrador de tareas no les gusta.