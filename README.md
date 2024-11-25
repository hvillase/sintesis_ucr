# Programación sonora en la creación musical
## 25 de noviembre 2024 
## Universidad de Costa Rica, Escuela de Artes Musicales
Dr. Hernani Villaseñor Ramírez  
UAM, Lerma  

## 1 Introducción
[Música concreta](https://es.wikipedia.org/wiki/M%C3%BAsica_concreta) en la radio de Francia (1948).  
[Música electrónica](https://en.wikipedia.org/wiki/Studio_for_Electronic_Music_(WDR)) en la Radio de Colonia (1951).    
Síntesis sonora con [MUSIC-N](https://en.wikipedia.org/wiki/MUSIC-N) (1957) desarrollado en los Laboratrios Bell por Max Mathews.    

## 2 El lenguaje de la música electrónica

### Frecuencia, amplitud y envolventes
Hz (hertz) o cíclos por segundo (cps).  
dB  (decibles), de presión sonora (dbSPL) en ámbito acústico y de escala completa en ámbito digital (dbFS).  
Amplitud en el tiempo: Ataque, Sostenimiento, Decaimiento, Relajamiento (ASDR).

### Osciladores
Sine, Saw, Pulse, Tri, Noise.

### Acetato y Cinta: grabación, edición y reprodicción de sonido
Acetato: surcos impresos en acetato que representan forma de onda del sonido.  
Cinta: cinta plástica con partículas magnéticas para registrar sonido mediante electromagnetismo.

## Sintetizador

## El lenguaje de la síntesis
Aditiva: suma de ondas sinuidales.  
Sustractiva: filtrado de ruido.  
AM: amplitud modulada.  
FM: frecuencia modulada.   
Modulación de anillo. 
Granular.  
Modelado físico: [Karlplus-Strong](https://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis).  
Wave Table.  

## Software sonoro
Escribir código fuente. [SuperCollider](https://supercollider.github.io/)  
Conectar cables o parcheo. [PureData](https://puredata.info/)  
Sintetizadores virtuales. [VCV Rack](https://vcvrack.com/)   

## Patrones (patterns)
Cíclos en los que se desarrollan las rutinas computacionales en el tiempo.  
Por ejemplo, un patrón de secuencia en SuperCollider que cuenta cuatro índices de manera infinita: 
```
Pseq([1, 2, 3, 4], inf)
```

## Sonido controlado por código

## Software de edición
[Audacity]()  
[Ardour]()  
[Reaper]()  

## Investigación artística en tecnología musical

## Colectividad
Tocar juntos/as. Con sincronía o reloj, sin sincronía.  
SC: [LinkClock](https://doc.sccode.org/Classes/LinkClock.html)  
Dejalo sonar.  

### C.C.A.V.U.L.
![CCAVUL](ccavul1.jpg "ccavul")  
[ccavul](https://hvillase.github.io/ccavul/)  

## Software visual
