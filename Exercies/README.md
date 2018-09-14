#Exercise of probabilities and proportions

They was cultivated isolated methanogenic bacteria  _(Ruminococcus flavefaciens)_ in an anaerobic reactor, these coming from the stomach of a ruminant, two types of culture media were used: standard medium and leachate medium, they were cultivated in anaerobic reactors of 5 liters, after 36 hours of cultivation, they calculate the biomass of bacteria in (g/L)

They have the following results in: "https://raw.githubusercontent.com/psmaniac/Course-Data-Science-and-R-for-Research/master/Exercies/culture_methanogenic_bacteria.csv"

**1.-** Cuales son los promedios de: toda la muestra, medio estandar y medio lixiviado?.\
**2.-** Que hipotesis puede asimir comparando los promedios de los dos medios?.\
**3.-** Calcule las desviaciones estandares de los dos medios por separado.\
**4.-** Grafice con la funcion hist(), todas las muestras, medio estandar y medio lixivaido por separado.\
**5.-** Grafice con la funcion plot(density(x)) el medio estandar y sobreponga el medio lixiviado con la funcion line(density(y))\
   Ejemplo
  >     plot(density(x), col='blue', lwd=2)
  >     lines(density(y), col='red', lwd=2)
**6.-** Cual es la proporcion de las muestras que pesan menos de 75 gramos?, de los dos medios por separado.\
   Ejemplo
  >     mean(condicion)
  >     mean(data_set < 80) "Devuelve la proporcion de datos que son menores a 80"
**7.-** Cual es la proporcion de las muestras que pesan entre +- 10 gramos con respecto a sus promedios?, de los dos medios por separado.\
**8.-** Cual es la proporcion de las muestras que pesan entre +- 0.6 DS?, de los dos medios por separado.\
**9.-** Cual es la proporcion de las muestras que pesan entre 65 y 85 gramos?, de los dos medios por separado.\
**10.-** Cual es la proporcion de las muestras del medio estandar que pesan entre +- 1 DS del medio lixiviado.\
**11.-** Cual es la proporcion de las muestras del medio lixiviado que pesan entre +- 1 DS del medio estandar.\
**12.-** Extraiga el promedio de 30 muestras aleatoriamente y repitela 1000 veces con un set.seed(256) calcule los promedios y        desviaciones estandares de estos, de los dos medios por separado.\
   Ejemplo
  >     set.seed(1) "Establece un orden unico aleatorio para poder repetir el resultado"
  >     sample(data_set, size) "Extrae muestras aleatorias de un vector con un tamanio definido"
  >     replicate(n, expresion) "Repite una expresion n cantidad de veces parecida al for"
**13.-** Grafice con la funcion hist(), todos los promedios de: medio estandar y medio lixivaido por separado.\
**14.-** Grafice con la funcion plot(density(x)) los promedios del medio estandar y sobreponga los promedios del medio lixiviado con la funcion line(density(y))
   Use el parametro xlim dentro de la funcion plot(), para ampliar el tamanio de los limites del grafico
  >    xlim=c(45, 110)
**15.-** Cual es la probabilidad de los promedios que pesan menos de 75 gramos?, de los dos medios por separado.\
   Ejemplo
  >     pnorm(valor, mean= 0, sd=1) "devuelve la probabilidad de datos que sean menor a el valor para una distribucion estandar"
  >     pnorm(6.2, mean= 5, sd= 0.7) "devuelve la probabilidad de datos que sean menor a 6.2 en una distribucion normal con una media de 5 y una desviacion estandar de 0.7"
**16.-** Cual es la probabilidad de los promedios que pesan entre +- 10 gramos con respecto a sus promedios?, de los dos medios por separado.\
**17.-** Cual es la probabilidad de los promedios que pesan entre +- 0.6 DS?, de los dos medios por separado.\
**18.-** Cual es la probabilidad de los promedios que pesan entre 65 y 85 gramos?, de los dos medios por separado.\
**19.-** Cual es la probabilidad de los promedios del medio estandar que pesan entre +- 1 DS del medio lixiviado.\
**20.-** Cual es la probabilidad de los promedios del medio lixiviado que pesan entre +- 1 DS del medio estandar.\
**21.-** Realize una comparacion entre los resultados con respecto a la proporcion y probabilidad de los ejercicios
