# Horarios de laboratorios del Zero - UBA

Este repositorio contiene los horarios de los laboratorios de la Facultad de Ciencias Exactas (UBA) y un script para generar **grillas visuales de ocupación** por semana.

## Estructura del repositorio

- `data/` → Archivos CSV con los horarios por día (Lunes, Martes, …, Sábado).  
- `scripts/graficador.py` → Script en Python que procesa los CSV y genera la grilla.  
- `figures/` → Carpeta donde se guardan las imágenes generadas.  
- `requirements.txt` → Librerías necesarias para ejecutar el script.  

## Uso

1. Clonar el repositorio:

```bash
git clone https://github.com/ManuUBA/Horarios-de-labos-del-zero.git
cd Horarios-de-labos-del-zero
