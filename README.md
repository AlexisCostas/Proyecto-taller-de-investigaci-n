# Lluvia de ideas #
* Reconocimiento de patrones de juego utilizando Machine Learning:
 * En este caso necesitaríamos jugar muchas partidas nosotros para que el sistema detecte cual es la mejor estrategia
 * Luego podríamos aplicar redes neuronales para simular muchísimas partidas y así obtener:
   * Los mejores patrones de juegos
   * Un sistema multiagente competente
* Posible lineamientos de futura investigación y/o proyecto
 * Sistema de visión que detecte objetos y enemigo On Live
   * ~~Segun los objetos, al detectar al enemigo, debería de marcarlo en un minimapa creado exclusivamente para este fin~~
   * Dependiendo el juego, si existe un minimapa, puede ser marcada la última vez que se ha visto a un enemigo
 * Sistema de visión que detecte el estado de la partida;
   * Recursos como puede ser la stamina, la vida.
   * Estado de los aliados.
   * Posibles ubicaciones de los enemigos en donde no hay visión.
   * Estado de la disponibilidad de las habilidades de los enemigos
 * Combinando ambos elementos anteriores, un sistema de soporte para la toma de decisiones en tiempo real, cuya base para la toma
de decisiones estará basada en lo aprendido mediante las redes neuronales

# Actualización de 3 de abril #

* Proyecto acotado al desarrollo de overlay para la toma de decisiones para jugadores principiantes en League of Legends

* Proximos pasos
 * Investigación sobre que tecnología utiliza el lol
 * Decisión sobre que marco de trabajo se realizará el overlay
 * Informar sobre el funconamiento de la API
