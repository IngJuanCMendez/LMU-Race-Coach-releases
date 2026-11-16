# Kerbo Race Coach

Ingeniero de pista por voz para **Le Mans Ultimate** e **iRacing**: te dice en qué curva pierdes tiempo y qué hacer distinto, ajusta contigo reparto de freno, ABS y TC, sigue a tus rivales y genera un debrief después de cada sesión.

## Descargar

**Última versión: [Kerbo-Race-Coach-v0.6.0.zip](versiones/Kerbo-Race-Coach-v0.6.0.zip)** (botón *Download raw file* en la página del archivo).

1. Descomprime el zip en `Documentos`.
2. Ejecuta `instalar.bat` (instala Python si hace falta y crea el acceso directo **Kerbo Race Coach** en el Escritorio).
3. En LMU: *Settings → Gameplay → Enable Plugins = ON*. En iRacing no hay que configurar nada.
4. Voz en español: ejecuta `instalar_voz_espanol.bat`.

La app se actualiza sola desde aquí (*Ajustes → Buscar actualizaciones*), conservando tus sesiones y tu configuración.

## Novedades v0.6.0

- Nuevo nombre: Kerbo Race Coach, con icono propio (ya no sale el de Python en la barra de tareas). Al abrir se crea el acceso directo nuevo en el Escritorio y se quita el viejo.
- Compatibilidad con iRacing: la app detecta sola si está abierto LMU o iRacing (o elige uno en Ajustes → Simulador). iRacing no necesita configuración.
- En iRacing funciona el coaching por curva, delta, rivales, combustible, estrategia, banderas, lluvia, consistencia, amigos, debrief e IA.
- Limitaciones de iRacing: no publica deslizamiento por rueda ni señal de TC actuando; el patinaje se estima con la deriva trasera y los bloqueos solo se ven vía ABS. Llantas solo se actualizan en pits.
- El diagnóstico ahora también revisa iRacing.

---
Proyecto independiente, sin relación con Le Mans Ultimate, iRacing ni sus desarrolladores. Beta.
