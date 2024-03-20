# Mangueras Musmanno Rock Festival

## Introducción
Marzo, época de Lollapallooza. ¿Van? Sin embargo, hay otro festival en esta época, el Musmanno Rock Festival: https://www.youtube.com/watch?v=PwUiwtrIbgQ.

## Consigna
Pónganse en parejas. Uno va a ser CM (Community Manager) de Twitter/X, y el otro CM de Instagram. Vamos a abreviarlos **CMX** y **CMI**. Es importante que se acuerden y asignen roles para la actividad que viene.

### Parte 1
**CMX** descarga los archivos del repositorio linkeado debajo y los sube a un nuevo repositorio propio. **CMX** lo agrega a **CMI** como colaborador. Para más información de como hacer esto, pueden leer en https://docs.github.com/en/authentication/managing-access-to-your-repositories/inviting-collaborators-to-a-personal-repository. **CMI** debe luego clonar el repositorio en sus máquina.

### Parte 2
Antes del festival, se bajan 2 bandas a último momento, una del excenario huawei y otra del escenario indie (elijan ustedes cuales). Queda a cargo de los CM's encontrar reemplazos a último momento. 
1. CMX reemplaza la banda del escenario Huawei, y CMI del escenario Indie.
2. Ambos realizan un commit
3. CMX pushea
4. CMI pullea

¿Qué ocurre? 

5. CMI pushea
6. CMX pullea

### Parte 3
Pomelo se baja a último momento. Tanto CMX como CMI buscan un reemplazo a último momento.
1. Tanto CMX como CMI reemplazan a Pomelo por otro artista de forma independiente (distinto los dos).
2. Ambos realizan un commit
3. CMI pushea
4. CMX pullea

¿Qué ocurre?

5. Solucionar el merge conflict, realizando un commit, con algo acordado entre los 2.
6. CMX pushea
7. CMI pullea

### Punto 4
Como se sobrevendieron las entradas, hay que poner un 4to escenario. Nuevamente, los CM's quedan a cargo de la situación.

1. CMI crea un branch llamada *new-stage*, y de ahora en más trabaja en ella.
2. Tanto CMI como CMX agregan un escenario de forma independiente (distintos con distintas bandas).
3. Ambos realizan un commit
4. Ambos pushean

Vean como se comporta en github

### Punto 5
Esta vuelta, ambos pudieron ver sus propuestas y decidieron en una propuesta superadora (una, otra o mezcla).

1. CMI cambia al branch principal (*main* o *master*) y pullea
2. Mergea el branch *new-stage* al este branch principal (*main* o *master*).
3. Soluciona el merge conflict con la propuesta final
4. CMI pushea
5. CMX pullea

## Fin.

¡Salvaron el festival! Ahora miles de personas lo pueden disfrutar rock, rock y más rock.