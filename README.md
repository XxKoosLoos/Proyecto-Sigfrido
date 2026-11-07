# Proyecto Sigfrido

Prototipo inicial de interfaz de escritorio en Python y PyQt6 para un proyecto denominado «Máquina automatizada para sembradío».

## Estado y alcance actual

El código disponible en `Interfaz/Inicio.py` crea y muestra una ventana de PyQt6 e imprime mensajes de inicio en la consola. `Interfaz/Llamados.py` está vacío.

La implementación revisada no incluye control de una máquina, comunicación con hardware, lógica de siembra, almacenamiento de datos, integración de APIs ni inteligencia artificial. El nombre del proyecto expresa su contexto; no acredita una máquina automatizada funcional.

## Estructura

| Ruta | Contenido |
| --- | --- |
| `Interfaz/Inicio.py` | Punto de entrada de la interfaz básica. |
| `Interfaz/Llamados.py` | Archivo vacío, sin comportamiento implementado. |
| `Doc/Maquina plantadora.docx` | Documento presente en el repositorio; su contenido no fue validado en la revisión técnica. |
| `requirements.txt` | Lista de dependencias declaradas, sin versiones fijadas. |
| `Entorno/` | Entorno virtual de Windows incluido en el repositorio original. |
| `.gitgnore` | Archivo vacío cuyo nombre no corresponde a `.gitignore`. |

## Requisitos y dependencias

Se necesita Python y un entorno gráfico compatible con PyQt6. El archivo `Entorno/pyvenv.cfg` registra Python 3.12.5 en el entorno original de Windows; este dato no establece una versión mínima ni garantiza compatibilidad con otros sistemas.

`requirements.txt` declara:

- PyQt6
- pygame
- kivy
- Pillow
- moviepy

El código propio revisado importa PyQt6 y `sys`, perteneciente a la biblioteca estándar. No se observó uso de las otras cuatro dependencias en esa implementación. La lista necesita validación antes de fijar versiones o retirar paquetes.

## Instalación y ejecución propuestas

Estas instrucciones deben ejecutarse desde la raíz de una copia completa del repositorio. No fueron probadas durante la auditoría; no constituyen una instalación validada.

Crear un entorno virtual nuevo, separado de `Entorno/`:

```bash
python -m venv .venv
```

En Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

En Linux o macOS:

```bash
source .venv/bin/activate
```

Instalar las dependencias declaradas y abrir la interfaz:

```bash
python -m pip install -r requirements.txt
python Interfaz/Inicio.py
```

En algunos sistemas el comando disponible es `python3` en lugar de `python`. PyQt6 requiere una sesión gráfica; pueden ser necesarios componentes del sistema según la plataforma.

Según la lectura del código, se espera una ventana básica y los mensajes «Dentro de main» y «Creando la ventana» en la consola. No se ha verificado este resultado mediante ejecución.

## Limitaciones y validación pendiente

- No se identificaron pruebas propias ni configuración de integración continua.
- No se ejecutó la aplicación ni se comprobó la instalación de dependencias durante la auditoría.
- El entorno virtual versionado contiene paquetes y rutas locales de Windows; debe recrearse para cada instalación.
- Falta documentar los requisitos funcionales, el hardware previsto y las contribuciones de las personas participantes.
- La autoría y los derechos de reutilización del documento y otros materiales deben confirmarse antes de redistribuirlos. La cuenta propietaria del repositorio no demuestra autoría exclusiva.

## Evidencia histórica

Los tres commits accesibles de la rama `main` registran actividad el **18 de septiembre de 2024 (UTC)**:

- [`8e9a9ec`](https://github.com/XxKoosLoos/Proyecto-Sigfrido/commit/8e9a9ec91eeafb6a092e2056cf6f4a1275dc9b71): README inicial.
- [`5441486`](https://github.com/XxKoosLoos/Proyecto-Sigfrido/commit/54414860a8f3db4526e5e3c6119ed39244cbd819): incorporación de la interfaz, dependencias y entorno.
- [`9fbf397`](https://github.com/XxKoosLoos/Proyecto-Sigfrido/commit/9fbf397c9374f44e4cfe8103e4f7be4581b3dd2a): incorporación del documento Word.

Estas fechas corresponden a registros de Git y no prueban el inicio real ni la duración del desarrollo.

## Mantenimiento propuesto

Se propone corregir `.gitgnore`, excluir entornos virtuales del seguimiento actual, validar las dependencias y registrar las modificaciones posteriores en `CHANGELOG.md`, con fecha real, motivo y alcance. Estas operaciones están pendientes de aprobación; no se presentan como cambios ya realizados.

La modernización debe conservar los commits y merges originales y respetar la atribución de los materiales.
