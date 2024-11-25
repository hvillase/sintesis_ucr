# Programación sonora en la creación musical
## 25 de noviembre 2024 
## Universidad de Costa Rica, Escuela de Artes Musicales
Dr. Hernani Villaseñor Ramírez  
UAM, Lerma  

## 1 Introducción
[Música concreta](https://es.wikipedia.org/wiki/M%C3%BAsica_concreta) en la radio de Francia (1948).  
[Música electrónica](https://en.wikipedia.org/wiki/Studio_for_Electronic_Music_(WDR)) en la Radio de Colonia (1951).    
Síntesis sonora con [MUSIC-N](https://en.wikipedia.org/wiki/MUSIC-N) (1957) desarrollado en los Laboratrios Bell por Max Mathews.    

## 2 El lenguaje de la síntesis

### Software
Escribir código fuente. [SuperCollider](https://supercollider.github.io/)  
Conectar cables o parcheo. [PureData](https://puredata.info/)  
Sintetizadores virtuales. [VCV Rack](https://vcvrack.com/)   

### Frecuencia, amplitud y envolventes
Hz (hertz) o cíclos por segundo (cps).  
dB  (decibles), de presión sonora (dbSPL) en ámbito acústico y de escala completa en ámbito digital (dbFS).  
Amplitud en el tiempo: Ataque, Sostenimiento, Decaimiento, Relajamiento (ASDR).

### Osciladores
Sine, Saw, Pulse, Tri, Noise.  
```
{SinOsc.ar(440, 0, 1)!2}.play;
{LFTri.ar(440, 0, 1)!2}.play;
{Saw.ar(440, 1)!2}.play;
{Pulse.ar(440, 0, 1)!2}.play;
{WhiteNoise.ar(440, 0, 1)!2}.play;
```

### Tipos de síntesis
Aditiva: suma de ondas sinuidales.  
Sustractiva: filtrado de ruido.  
AM: amplitud modulada.  
FM: frecuencia modulada.   
Modulación de anillo. 
Granular.  
Modelado físico: [Karlplus-Strong](https://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis).  
Wave Table.  
[Ejemplos](https://github.com/hvillase/taller-tec/tree/main/ejemplos) en SC y Pd.  

## Patrones (patterns)
Cíclos en los que se desarrollan las rutinas computacionales en el tiempo.  
Por ejemplo, un patrón de secuencia en SuperCollider que cuenta cuatro índices de manera infinita: 

```
Pseq([1, 2, 3, 4], inf)
```

## Sonido controlado por código
Implementación de rutinas y patrones a muestras de sonido.

## Software de edición
[Audacity](https://www.audacityteam.org/)  
[Ardour](https://ardour.org/)  
[Reaper](https://www.reaper.fm/)  

## 3 Colectividad
Tocar juntos/as. Con sincronía o reloj, sin sincronía.  
SC: [LinkClock](https://doc.sccode.org/Classes/LinkClock.html)  
Déjalo sonar.  

### C.C.A.V.U.L.
Colectivo de Creación AudioVisual de la UAM Lerma  
![CCAVUL](ccavul1.jpg "ccavul")  
[c.c.a.v.u.l.](https://hvillase.github.io/ccavul/)