1 - BrasBalance.c Programme principal. Pour compiler gcc -o BrasBalance BrasBalance.c Balance.c interfaceVL6180xmod.c uarm_swift_pro.c -lpthread -lm
2 - Balance.c Programme qui gère la Balance. Pour l'utiliser seul, modifier _main(0 pour main(), et rajouter LirePoids() dans le main avant de compiler (sudo gcc Balance.c -o Balance et ./Balance)
3 - interfaceVL6180xmod.c Programme qui gère le capteur de distance VL6180
4 - uarm_swift_pro.c Programme qui gère le bras UARM Swift pro. Peux l'utiliser seul, modifié main_() pour main(), compiler (sudo gcc uarm_swift_pro.c -o uarm_swift_pro et ./uarm_swift_pro)
