# TP1_JAVA
Pour ajouter une machine , il faut tout d'abord ajouter une salle .
Dans la classe Machine, Il y a une référence à Salle avec @ManyToOne et @JoinColumn(name = "salle_id") , cela signifie que la colonne "salle_id" 
dans la table des machines sera utilisée pour stocker l'ID de la salle à laquelle chaque machine est associée.Pour @OneToMany , mappedBy = "salle" 
signifie que la relation entre Salle et Machine sera gérée par l'attribut salle déclaré dans Machine . 

https://github.com/goldenadnane/TP1_JAVA/assets/122232044/07f0ee39-9269-40a0-a633-0b7539515f5e

