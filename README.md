# UL Content Research — demo pública

Versión estática para GitHub Pages, basada en la interfaz V19.5.3/5.4 del paquete proporcionado.

## Publicación
1. Crea un repositorio en GitHub.
2. Sube **el contenido de esta carpeta** a la raíz del repositorio (index.html y los tres archivos JSON).
3. En **Settings → Pages**, selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
4. Abre la URL que indique GitHub Pages cuando termine el despliegue.

## Limitaciones
- Esta versión permite explorar la interfaz y los datos de muestra. Algunas funciones de cliente pueden funcionar, pero no se garantiza funcionamiento completo.
- No ejecuta Ollama, Python, generación de imágenes, transcripción ni endpoints `/api/*`. Las solicitudes al backend muestran un error de demo.
- No introduzcas credenciales, cuentas de servicio ni información confidencial en una página pública.
- El código de backend y el entorno virtual no están incluidos.

## Seguridad
Revisa los JSON y HTML antes de publicar para verificar que no contengan información privada o propietaria. Los datos incluidos proceden del paquete compartido.
