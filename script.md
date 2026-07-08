# Performance Review · Valde (Despedida de Soltero)

Presentación de la despedida de Diego "Valde" Valdebenito.
Ábrela con doble click en `presentacion.html` (cualquier navegador).
Navegación: flechas ← →, barra espaciadora, o botones abajo. Tecla **F** = pantalla completa.

## Cómo rellenar
- TODO el contenido se edita en el objeto `DATA`, arriba del archivo `presentacion.html`.
- Lo que está entre `[corchetes]` o con `??` / `???` es para reemplazar con datos reales de Valde.
- Fotos: pon el archivo en la carpeta `Fotos/` y usa la ruta indicada abajo
  (ej: `Fotos/valde-colegio.jpeg`). Si el archivo no existe, sale un placeholder con instrucciones.
- Las "fotos animadas" (GIF/video) están marcadas con borde azul como placeholder.

## Novedades (julio 2026)
- **Paleta verde-amarilla estilo Brasil 🇧🇷** en todo el deck.
- **17 slides nuevos**, todos editables en `DATA` (incluye nueva sección `DATA.roast`):
  - Timeline con fotos (Colegio · U · Trabajo) — usa `DATA.timeline`
  - Citas por año (gráfico) · Mapa de conquistas · Récords personales
  - Cómo conoció a la novia — usa `DATA.laNovia`
  - Bloque alcohol: KPIs + gauge de tolerancia · Borracheras por año (gráfico) · Top borracheras
  - **Auditoría 360° (roast)**: divider, Competencias maritales (barras), Presupuesto del soltero (donut),
    Dice vs. Hace, Evolución del activo físico (antes/después + tendencia), Excusas más usadas,
    Testimonios del comité (3 fotos), Predicciones para la boda (%), Cláusulas del contrato de Marido.
  - **Roast expositivo (2ª tanda, 10 slides)**: Diccionario Valde→Español, Tiempo de respuesta por
    remitente, El teléfono de Valde (screen time + donut), La curva de la noche (gráfico con hitos),
    Expediente disciplinario, Crímenes contra la moda (galería 4 fotos), Certificaciones obtenidas,
    Aporte real al carrete, Marido funcional vs. método Valde, Cifras verificadas por el comité.
    Todo se edita en `DATA.roast` (claves: diccionario, respuesta, telefono, curvaNoche, expediente,
    looks, certificaciones, aporteCarrete, vsMarido, datosCuriosos).

### Fotos nuevas opcionales (si no existen, sale placeholder)
| Archivo | Aparece en |
|---------|-----------|
| valde-antes.jpeg / valde-despues.jpeg | Evolución del activo físico (pon la ruta en `DATA.roast.evolucion`) |
| testigo-1/2/3.png | Testimonios del comité (campo `img` en `DATA.roast.testimonios`) |

## Fotos que espera la presentación (súbelas con estos nombres a `Fotos/`)
| Archivo | Aparece en |
|---------|-----------|
| valde-perfil-empleado.png | Ficha del empleado (avatar) |
| valde-colegio.jpeg | Timeline · Colegio |
| valde-universidad.jpeg | Timeline · Universidad |
| valde-trabajo.jpeg | Timeline · Trabajo |
| valde-pilar-1..4.jpeg | Pilares estratégicos (4 fotos) |
| valde-grupo-viajes / -deporte / -carrete.jpeg | El equipo (grupales) |
| valde-pareja.jpeg | Cómo conoció a la novia |
| valde-trayectoria.jpeg | Sección Trayectoria (con la frase legendaria) |
| valde-especimen.jpeg | Funnel de conversión ("el espécimen") |
| valde-brindis.jpeg | Cierre · Brindis final |
| Exes/ex1.png, ex2.png, ex3.png | KPI · Portafolio de relaciones |
| Novia/valde-novia.png | KPI · Portafolio (la actual, 💍) |
| Novia/novia-mensaje-inicial.mp4 | Apertura · mensaje de la novia (video) |
| footage-1.mp4, footage-2.mp4 | "Footage inédito" (2 videos en secuencia) |

Para cambiar una foto: edita la ruta `Fotos/...` en el slide correspondiente
dentro de `presentacion.html` (o en el objeto `DATA`).

## Estructura (actos)

### 0. Portada
1. Portada
2. Aviso de confidencialidad (chiste)
3. Agenda / índice

### 1. Resumen Ejecutivo
4. Veredicto del comité + nota global
5. Ficha del empleado (perfil)

### 2. Trayectoria Profesional (timeline)
6. Divider
7. Timeline completo (Colegio · Universidad · Trabajo)
8-11. Un slide con foto por cada etapa

### 3. KPIs Sociales & Lifestyle
- Divider
- Novias / portafolio de relaciones
- One night stands
- Citas por año (gráfico)
- Funnel de conversión (match → pololeo)
- Mapa de conquistas
- Alcohol: métricas + gauge de tolerancia
- Borracheras por año (gráfico)
- Top borracheras históricas
- Récords personales
- Grupo de amigos
- Análisis FODA (fortalezas / oportunidades / debilidades / amenazas)

### 4. Juegos
- Divider + 1 slide por juego (editables en DATA.juegos)

### 5. Cierre
- Veredicto: ASCENDER a Marido
- Brindis final
