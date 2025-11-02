# Datos para taller de Análisis de Datos de Oxford Nanopore

## Forma recomendada de uso

Primero descarga una copia del repositorio con Git:

```bash
git clone https://github.com/dialvarezs/ont-data-analysis-files-2025
cd ont-data-analysis-files-2025
```

Posteriormente, para obtener las actualizaciones más recientes del repositorio, ejecuta `git pull` desde dentro del directorio del repositorio.

## Datos asociados

Algunos datos son muy pesados para almacenarlos en el repositorio, por lo que están almacenados de forma externa.

Para descargar los datos asociados a este repositorio necesitas instalar [dvc](https://dvc.org/).

La forma recomendada de instalar dvc es con [uv](https://docs.astral.sh/uv/):

```bash
uv tool install dvc
```

También es posible instalar dvc con otros gestores como `pip`, `mamba` o `brew`.
Revisa la [documentación oficial](https://dvc.org/doc/install) para más detalles.

Una vez que tengas instalado `dvc`, navega al directorio del repositorio y descarga los datos asociados:

```bash
# Descarga todos los datos asociados al repositorio
dvc pull

# Descarga un archivo o directorio específico
dvc pull ch1/format_examples.dvc
```
