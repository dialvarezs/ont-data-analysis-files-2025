# Datos para taller de Análisis de Datos de Oxford Nanopore

Para descargar los datos asociados a este repositorio necesitas instalar [dvc](https://dvc.org/).

La forma recomendada de instalar dvc es con [uv](https://docs.astral.sh/uv/):
```bash
uv tool install dvc
```

También es posible instalar dvc con otros gestores como `pip`, `mamba` o `brew`.
Revisa la [documentación oficial](https://dvc.org/doc/install) para más detalles.

Una vez que tengas instalado `dvc` puedes clonar este repositorio y descargar los datos asociados con "pull":

```bash
# Descarga todos los datos asociados al repositorio
dvc pull

# Descarga un archivo o directorio específico 
dvc pull ch1/format_examples.dvc
```

