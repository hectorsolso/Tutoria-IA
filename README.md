<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course

## Summary

Creación de una IA para orientar a los estudiantes en la técnicas de estudio, organización y planificación del estudio  para optimizar su rendimiento


## Background

El problema que resolvería sería la orientación de las técnicas de estudio en base a los resultados de los estudiantes para mejorar su rendimiento. Es un problema frecuente encontrar alumnado que no tiene una buena organización y planificación de estudio. La motivación personal es ayudar al alumnado a mejorar en sus estudios. El tema es importante porque hasta dónde yo sé no hay IA para orientar al alumnado en sus estudios


## How is it used?

El contexto es el escolar y la solución la aplica el alumnado con dificultades, supervisado por el profesorado. Las personas afectadas serían profesores, estudiantes y responsables familiares
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
la fuente de datos son los resultados académicos de las pruebas en cada asignatura, las horas de dedicación lectiva a la semana, las horas de dedicación al estudio. Creo que la técnica más adecuada sería la regresión lineal. Como no soy programador no puedo aportar, pero con la regresión lineal se podría predecir el resultado mas optimo

## Challenges

El problema que no resuelve es el control de la aplicación de la solución por parte del alumnado, el problema del seguimiento escolar.

## What next?

Creo que podría ser un tutor personalizado para el estudiante que pudiera llegar a aconsejar en base al conocimiento adquirido de la interacción las mejores soluciones a los problemas de motivación y estudio


## Acknowledgments

La fuente de inspiración es la experiencia adquirida a lo largo de los años en tutoría y las conversaciones con compañeros.
