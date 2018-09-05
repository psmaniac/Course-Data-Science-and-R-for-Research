#Exercise of probabilities and proportions

They was cultivated isolated methanogenic bacteria  _(Ruminococcus flavefaciens)_ in an anaerobic reactor, these coming from the stomach of a ruminant, two types of culture media were used: standard medium and leachate medium, they were cultivated in anaerobic reactors of 5 liters, after 36 hours of cultivation, they calculate the biomass of bacteria in (g/L)

They have the following results in: "https://github.com/psmaniac/Course-Data-Science-and-R-for-Research/blob/master/Exercies/culture_methanogenic_bacteria.csv"

**1.-** Cuales son los promedios de: toda la muestra, medio estandar y medio lixiviado?.\
**2.-** Que hipotesis puede asimir comparando los promedios de los dos medios?.\
**3.-** Calcule las desviaciones estandares de los dos medios por separado.\
**4.-** Grafice con la funcion hist(), todas las muestras, medio estandar y medio lixivaido por separado.\
**5.-** Grafice con la funcion plot(density(x)) el medio estandar y sobreponga el medio lixiviado con la funcion line(density(y))\
   > ejemplo\
        plot(density(x), col='blue', lwd=2)\
        lines(density(y), col='red', lwd=2)\
**6.-** Cual es la proporcion de las muestras que pesan menos de 75 gramos?, de los dos medios por separado.\
**7.-** Cual es la proporcion de las muestras que pesan entre +- 10 gramos con respecto a sus promedios?, de los dos medios por separado.\
**8.-** Cual es la proporcion de las muestras que pesan entre +- 0.6 DS?, de los dos medios por separado.\
**9.-** Cual es la proporcion de las muestras que pesan entre 65 y 85 gramos?, de los dos medios por separado.\
**10.-** Cual es la proporcion de las muestras del medio estandar que pesan entre +- 1 DS del medio lixiviado.\
**11.-** Cual es la proporcion de las muestras del medio lixiviado que pesan entre +- 1 DS del medio estandar.\
**12.-** Extraiga el promedio de una 30 muestras aleatoriamente y repitela 1000 veces con un set.seed(256) calcule los promedios y        desviaciones estandares de estos, de los dos medios por separado.\
**13.-** Grafice con la funcion hist(), todos los promedios de: medio estandar y medio lixivaido por separado.\
**14.-** Grafice con la funcion plot(density(x)) los promedios del medio estandar y sobreponga los promedios del medio lixiviado con la funcion line(density(y))\
**15.-** Cual es la probabilidad de los promedios que pesan menos de 75 gramos?, de los dos medios por separado.\
**16.-** Cual es la probabilidad de los promedios que pesan entre +- 10 gramos con respecto a sus promedios?, de los dos medios por separado.\
**17.-** Cual es la probabilidad de los promedios que pesan entre +- 0.6 DS?, de los dos medios por separado.\
**18.-** Cual es la probabilidad de los promedios que pesan entre 65 y 85 gramos?, de los dos medios por separado.\
**19.-** Cual es la probabilidad de los promedios del medio estandar que pesan entre +- 1 DS del medio lixiviado.\
**20.-** Cual es la probabilidad de los promedios del medio lixiviado que pesan entre +- 1 DS del medio estandar.\
**21.-** Realize una comparacion entre los resultados con respecto a la proporcion y probabilidad de los ejercicios
