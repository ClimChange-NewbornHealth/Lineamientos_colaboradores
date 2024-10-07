# Lineamientos para colaboradores

Bienvenido/a a nuestro proyecto de trabajo acerca de exposición ambienta y efectos en salud perinatal. La descripción de este repositorio y proyectos lo puedes encontrar en [https://github.com/ClimChange-NewbornHealth](https://github.com/ClimChange-NewbornHealth).

A continuación te dejamos lineamientos generales para la incorporación de proyectos colaboradores al proyecto. En términos generales cualquier persona puede hacer un `fork` o copia de nuestros repositorios por lo que es importante estandarizar algunos procedimientos. 

## Generar nuevos repositorios 

### Paso 1: Generar un repositorio

|["/Images/repo1"]("/Images/repo1")

### Paso 2: Definir un repositorio

|["/Images/repo1"]("/Images/repo2")

Nuestros repositorios siempre deben tener estos ajustes: 

- Usar nombres breves, directos y de preferencia en inglés.
- Puede incorporar una breve descripción que de contexto al proyecto.
- El repositorio debe ser *públicos*.
- El respositorio siempre de tener un archivo `README`. 
- El respositorio siempre deben tener un archivo `.gitignore`.
- El respositorio siempre deben tener una licencia de copyright. Puede usar el `MIT License` que es el más estandarizado.

### Paso 3: Trabajar el repositorio desde mi entorno local

|["/Images/repo1"]("/Images/repo3")

Con esto puedes utilizar el link de acceso al repositorio y conectarte desde cualquier Interfaz de Desarrollo de Aplicaciones: RStudio, Visual Studio Code, Positron.

## Descripción de los repositorios

### Estructura del repositorio

Se espera que los repositorios tengan una estructura estandarizada: 

```
├── Code: códigos con procesamiento, análisis descriptivos y modelamiento
│   ├── Process
│   ├── Descriptive
│   ├── Models
|
├── Output_Analysis: tablas, gráficos y las salidas de código. Se espera que sean resultados finales
│   ├── Graphs
│   ├── Tables
|
- .gitignore : archivos ignorados del repositorio (en especial los datos)
- README.md : documento de descripción del repositorio
- LICENSE: 
```

### Acerca del README file

El README es una descripción del código del proyecto 

Puedes encontrar una plantilla aquí: 

### Sobre la disponibilidad de datos en los repositorios 

En el repositorio solo estarán disponibles todos los códigos para replicar los resultados del proyecto. Sin embargo, las tablas de datos utilizadas y generadas en el paso a paso deben ser linkeadas en otro espacio como dropbox o google drive. Con esto cuidamos la capacidad disponible en el repositorio. 

Puede revisar un ejemplo aquí: [https://github.com/ClimChange-NewbornHealth/CIIIA-ClimateBirthWeightAnalysis](https://github.com/ClimChange-NewbornHealth/CIIIA-ClimateBirthWeightAnalysis)

|["/Images/data1"]("/Images/data1")

|["/Images/data2"]("/Images/data2")