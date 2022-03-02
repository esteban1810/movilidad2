
![Logo](https://pim.guadalajara.gob.mx/material/img/pim.png)


# MOVILIDAD 2.0 GDL

Sistema de gestión de infracciones de movilidad
## Versión 2.4.2

**Correcciones:**

- Se arregló el reporte diario.
    - Se mejoró el formato que tiene.
    - Imprime todas las infracciones que el agente realizó en el día seleccionado.
    - Se entrega un recuento de las infracciones agrupadas por conceptos.
- Se solucionó el problema en las reimpresiones.
    - Si la foto 1 no existe se muestra la foto 2.
- Se solucionó el problema en el onBack.
    - Cuando el agente desea regresar a la pantalla de inicio después de haber levantado una infracción, el folio siguiente no será marcado como 'No Procesado'.

**Mejoras:**

- La Inteligencia Artificial para el reconocimiento de placas, se volvió optativo. 
    - Si el agente le toma foto a las placas y decide escribirlas manualmente la Inteligencía Artificial no reemplazará lo que haya escrito.
    - Si después de haber tomado la foto la Inteligencia Artificial detecta que el agente no ha escrito nada en el recuadro de placas la IA se las pondrá en automático.

**Eliminaciones:**

- No hubo eliminaciones.

## Información técnica

**Entorno de Desarrollo Integrado:** Android Studio

**Lenguaje:** Java

**Server:** PHP 8

**BDD:** SQLite


## Instalación

Instalar con comandos

```bash
  1.- Habilitar los permisos de su dispositivo android para poder descargar archivos de fuentes desconocidas.
  2.- Descargar el archivo .apk.
  3.- Presionar sobre el archivo para instalarlo.
  4.- Abrir la aplicación.
```


## Autor

- [Perspective Global de México](https://perspective.com.mx/)

![imagen](https://www.perspective.com.mx/assets/img/logo.png)

