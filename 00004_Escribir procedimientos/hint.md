¿No recuerdas cómo se escribe un procedimiento? No te preocupes, es normal, recién estamos empezando. :wink:

Mira como ejemplo este procedimiento que mueve el cabezal cinco veces hacia el norte y el programa que lo invoca:

```gobstones
procedure Mover5VecesHaciaElNorte() {
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
}

program {
  Mover5VecesHaciaElNorte()   
}
```