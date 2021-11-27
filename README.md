El tutu en cuestión es este: https://www.youtube.com/watch?v=FeqEThlghqo
El señor lo hace con una versión antigua de angular y de firebase.
Para hacerlo con la nueva hay que hacer un downgrade en el package en:
  "firebase": "^7.0 || ^8.0",
  "@angular/fire": "^6.1.4",

