# 🖱️ Macros en Memoria

**Guarda tus macros en la memoria interna de tu mouse Logitech G** para que funcionen **sin necesidad de tener Logitech G HUB abierto**. Úsalo en cualquier PC, en un cibercafé o en un torneo.

La interfaz imita a G HUB: arrastras una macro a un botón del mouse y se escribe directamente en el hardware. El mouse la ejecutará por sí solo, sin ningún software corriendo de fondo.

> ⚠️ **Proyecto independiente.** No está afiliado ni respaldado por Logitech. Todas las marcas pertenecen a sus respectivos dueños.

<img width="1434" height="928" alt="Interfaz de Macros en Memoria" src="https://github.com/user-attachments/assets/d1655d9e-a698-493a-bce9-b521378cefb4" />

## ✨ Características Principales
*   **Escritura en hardware:** Guarda macros, DPI e iluminación directamente en el mouse.
*   **Importación fácil:** Trae tus perfiles y macros desde G HUB (solo necesitas hacerlo una vez).
*   **Modo On/Off:** Decide si el mouse usa su memoria interna o lo controla el PC.
*   **Editor integrado:** Crea macros escribiéndolas o grabando tus teclas (soporta teclado en español).
*   **Copias de seguridad:** Guarda un respaldo antes de cada cambio y verifica byte a byte que todo se escriba bien.

## 🚀 Guía Rápida de Uso

1.  **Cierra G HUB:** Mientras G HUB esté abierto, el mouse ignorará su memoria interna. (La app te avisará con un botón naranja para cerrarlo).
2.  **Conecta y Abre:** Ejecuta la app y conecta tu mouse (idealmente por cable).
3.  **Configura:** Arrastra tus macros a los botones, ajusta el DPI en la sección *Sensibilidad*.
4.  **Guarda:** Pulsa el botón **GUARDAR EN MEMORIA INTERNA**. ¡Listo! Ya puedes desconectar el mouse y llevarlo a otro PC.

## 🛡️ Nota sobre Seguridad y Antivirus
Este es un ejecutable independiente (standalone) firmado con un certificado autofirmado.
*   Es posible que Windows SmartScreen muestre una advertencia la primera vez (clic en "Más información" > "Ejecutar de todas formas").
*   Puedes verificar el archivo en VirusTotal. La app **no se conecta a internet**; solo lee G HUB y se comunica con el mouse vía USB.

## 🔧 Solución de Problemas Comunes

*   **"La macro no hace nada":** G HUB está abierto o en segundo plano. Ciérralo completamente (icono junto al reloj) y activa la **Memoria Integrada** en la app.
*   **"No queda memoria libre":** Borra macros viejas que ya no uses para liberar espacio en el mouse. En un G502 HERO caben ~10 macros.
*   **El mouse no es detectado:** Verifica que sea un modelo Logitech G con memoria interna (los de oficina como MX Master no sirven).

## 💻 Requisitos y Compilación
*   **Sistema:** Windows 10 / 11.
*   **Hardware:** Mouse Logitech G compatible (Probado en G502 HERO).
*   **ejecuta ele xe:** LogitechGhub.exe.

Si quieres compilar tu propio `.exe`, el proyecto incluye scripts para usar `PyInstaller` (sencillo) o `Cython + cx_Freeze` (para ofuscar el código y proteger la lógica). Revisa el código fuente o la carpeta `setup.py` para ver el flujo exacto.

---
**Licencia:** GPL-3.0 license
