
- **Alumno:** Vanessa Victoria Wilczek
- **Bloque:** B0 — Prerrequisitos
- **Fase / ejercicio:** Fase 0.1
- **Fecha de inicio:** 15/09/2026
- **Fecha de entrega:** 17/09/2026

---

## 🎯 Qué se pedía

(Dos o tres líneas con tus palabras: qué había que conseguir.)

Se ha pedido que creemos una bóveda de 0 para un prestamo de portatiles, hemos creado sus carpetas y notas,
hicimos el primer commit de index
hemos cambiado textos dentro de los html e hicimos commit otra vez para comprobar que cambio, hicimos push y commit hasta tener los 3 archivos html, luego nos movimos al primer commit que hicimos y salimos de el.
## ⌨️ Comandos y pasos importantes

- `comando` — para qué sirve.
-pwd -> Muestra la carpeta actual. Contrasta su ruta con la indicada en este paso antes de seguir.
git init -> Crea el repositorio local en la carpeta que acabas de comprobar.
git branch -M main -> Establece main como nombre de la rama actual.
git status -> Muestra la rama main, sin commits todavía, y los archivos iniciales sin seguimiento.
git remote add origin git@github.com:TU-USUARIO/sor-web-prestamo-portatiles-cole.git ->Registra origin con la dirección SSH de tu repositorio vacío; todavía no envía archivos.
git remote -v ->Muestra las direcciones de lectura y envío de los remotos; origin debe ser el de este proyecto.
git add . -> Prepara todos los archivos no ignorados que hay bajo esta carpeta: en esta primera entrega, gitignore, bitácora y portada.
git commit -m "Crear pagina inicial de prestamos" -> Guarda localmente una versión con los cambios preparados y el mensaje indicado.
git push -u origin main -> Sube main por primera vez a origin y configura su seguimiento para las siguientes subidas.|
## 🛠️ Qué he hecho

(Los pasos que has seguido. No copies el enunciado: cuenta lo que hiciste tú.)

## 🚩 Qué me ha fallado y cómo lo he resuelto

(El mensaje de error LITERAL y qué hiciste. Si no falló nada, escribe "nada"
— pero piénsalo dos veces antes.)

## 🤔 Respuestas a las preguntas

1. ¿Por qué `git init` se hizo en `01_Proyecto` y no en la raíz de la bóveda?
 Porque el control de versiones con Git debe gestionarse de forma independiente dentro de la carpeta específica del proyecto que queremos versionar.
2. ¿Qué mostró `git status` antes de `add`, después de `add` y después de `commit`?
- **Antes de `add`:** Los archivos aparecían en color rojo que no estan rastreadas, indicando que Git sabe que están ahí pero todavía no los está vigilando activamente.

- **Después de `add`:** Los archivos cambiaron a color verde, listos para ser guardados en el siguiente paquete de cambios.

- **Después de `commit`:** La terminal indicó que el directorio de trabajo estaba limpio, ya que todos los cambios ya se habían registrado en el historial oficial.

3. ¿Por qué creaste un repositorio de GitHub propio y lo conectaste con `git remote add origin`?
Para alojar una copia de seguridad del proyecto en la nube y permitir su entrega o sincronización remota.

4. ¿Por qué las páginas nuevas aparecen en `git status` pero no en `git diff -- web/index.html`?
Porque git status avisa de la existencia de archivos nuevos en el directorio, pero git diff solo compara las modificaciones línea por línea de archivos que ya están rastreadas por Git.
5. ¿Cómo has comprobado que los vídeos existen pero no se van a subir?
Porque al ejecutar git status o al estar configurados en el archivo .gitignore, los archivos pesados de vídeo no aparecen en verde ni listados para ser empaquetados en el commit, confirmando que el sistema los está ignorando.

7. ¿Qué muestra `git diff --cached --stat` después de preparar los cuatro archivos?

8. ¿Qué cambia al visitar el primer commit y qué recuperas al volver a `main`?

9. ¿Por qué esta web necesita historial? ¿Qué aportaría GitHub si otro técnico trabajase contigo?

10. Si mañana corriges una errata en `normas.html`, ¿qué pasos repites y cuáles no?

## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/6bEQ8gxm1NQ
- **Playlist:** https://www.youtube.com/playlist?list=PLexytpFFPp5U

## 💭 Dudas / a repasar

- (lo que no te ha quedado claro)
-Me ha quedado claro, más o menos todo, solo necesito saberme los comandos básicos y que hace cada uno.