<div align="center">

# Valheim: visor de mapas y semillas

Consulta mapas de semillas de Valheim y prepara rutas hacia jefes y comerciantes. Comprueba con qué versión se creó el mundo.

<a href="[LINK]"><img src="./assets/readme/download-es.svg" width="280" height="54" alt="Descargar — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Valheim: visor de mapas y semillas — Vista de la aplicación">
</p>

## Por qué existe esta herramienta

Para consultar el mapa de una semilla de Valheim, usa la versión con la que se creó el mundo, no necesariamente la última versión instalada. Comprueba la semilla, la versión de creación y las capas antes de buscar jefes o comparar mundos. Los mundos existentes pueden requerir sus archivos para reflejar los cambios posteriores.

## Antes de empezar

- Prepara **Versión semilla + mundo** y confirma que corresponde al perfil o sesión de Valheim que quieres usar.
- Anota la build actual del juego/cliente o la fecha de los datos antes de cambiar un perfil.
- Decide dónde guardar **Configuración de semillas y capas** para no sobrescribir el resultado anterior.
- Prueba primero **vista previa mundial con reconocimiento de versiones** en una sesión corta y conserva al lado la partida, el perfil o la comparación original.

## Qué hace

### 01 · vista previa mundial con reconocimiento de versiones

Representa el terreno con las reglas de generación utilizadas por la versión del mundo seleccionada.

### 02 · marcadores de jefe y comerciante

Le permite mostrar u ocultar grupos de marcadores útiles sin saturar el mapa.

### 03 · comparación del mundo explorado

Coloca datos del mundo explorado junto a la semilla generada para una comparación directa.

## Recorrido por la interfaz

- **01.** Panel de semillas para la sarta de semillas y versión de generación mundial.
- **02.** Controles de capas para biomas, jefes, comerciantes y marcadores personalizados.
- **03.** Lienzo de mapa con zoom, coordenadas y ruta seleccionada.
- **04.** Inspector de marcadores con bioma, ubicación y detalles de puntos de referencia cercanos.
- **05.** Control de comparación mundial para una partida guardada explorada o una segunda semilla.

## Primera sesión completa

1. Abre **Valheim: visor de mapas y semillas** y comprueba la build o la fuente de datos de Valheim.
2. Elige la entrada o el perfil y configura **vista previa mundial con reconocimiento de versiones** sin tocar los valores que no formen parte de la prueba.
3. Revisa **marcadores de jefe y comerciante** en la vista previa o el panel de estado y corrige cualquier aviso de versión, filtro o detección.
4. Ejecuta una sola acción controlada. Compara el resultado visible con la vista previa antes de cambiar otro ajuste.
5. Guarda el perfil o exporta el resultado; conserva **comparación del mundo explorado** para comparar o recuperar.

## De un vistazo

| Función | Resultado |
|---|---|
| **Entrada** | Versión semilla + mundo |
| **Resultado** | Mapa en capas con marcadores. |
| **Salida** | Configuración de semillas y capas |

## Cómo interpretar el resultado

Trate el mapa generado como un plan vinculado a una semilla y una versión mundial. La distancia del marcador, la forma de la costa y el acceso al bioma son más útiles juntos que un solo pin. Al comparar mundos, mantenga las mismas capas visibles y el mismo nivel de zoom para que la diferencia surja de la semilla y no de la configuración de visualización.

## Pensado para

- Explora un mundo nuevo
- Compara dos semillas
- Encuentre una ruta hacia un jefe o comerciante

## Después de actualizar el juego

- [ ] Mantén la versión de creación del mundo; no la cambies solo porque el juego se haya actualizado.
- [ ] Regenere el terreno antes de cargar marcadores antiguos o capas de ruta.
- [ ] Compare un punto de referencia conocido para detectar un cambio de coordenadas o generación.
- [ ] Guarde el perfil de capa actualizado con un nuevo nombre hasta que se verifique el mapa.

## Solución de problemas

> **Problema habitual:** Los marcadores de jefe se movieron después de la actualización 1.0..

### Los marcadores aparecen en la ubicación incorrecta

Confirma la versión mundial antes de regenerar el mapa; Las reglas del terreno pueden cambiar entre construcciones.

### Un mundo explorado no se alinea

Verifique que el guardado y la semilla pertenezcan al mismo mundo, luego restablezca las compensaciones de escala y coordenadas.

### Una capa de marcador está vacía

Borre los filtros de categoría y reconstruya solo esa capa antes de regenerar todo el mapa.

## Datos y recuperación

Los mapas de semillas y los filtros de marcadores son de solo lectura. Exporte los perfiles por separado para poder restaurar una configuración de capa útil después de actualizar los datos mundiales.

<sub>Usa automatizaciones y modificaciones solo cuando las reglas del juego y el tipo de sesión lo permitan.</sub>

## Preguntas frecuentes

<details open>
<summary><strong>¿Puedo comparar una semilla con un mundo explorado?</strong></summary>

Sí. Primero cargue la semilla y luego agregue los datos del mundo explorado como capa de comparación. El terreno generado permanece separado de los marcadores descubiertos.
</details>

<details>
<summary><strong>¿Qué debe incluir un informe de compatibilidad?</strong></summary>

Anota la versión exacta del juego y de la herramienta o datos, la entrada usada y el resultado observado. Conserva lo desconocido como tal; otra versión no demuestra compatibilidad actual.
</details>

<details>
<summary><strong>¿Se incluye un ejecutable o script funcional?</strong></summary>

El repositorio contiene documentación y un concepto de interfaz, no un lanzamiento funcional verificado. Las notas y las imágenes no son pruebas de ejecución ni demuestran autoría oficial, compatibilidad o protección de cuenta.
</details>

---

<div align="center">

## Descargar

Revisa el alcance y la compatibilidad documentados antes de elegir una versión.

<a href="[LINK]"><img src="./assets/readme/download-es.svg" width="280" height="50" alt="Descargar — Windows"></a>

</div>

---

Concepto de interfaz generado con IA; no se ha verificado una versión funcional.
