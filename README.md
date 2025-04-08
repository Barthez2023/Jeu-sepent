# Jeu-sepent
presente une version ameliorer avec plus d'interaction du jeu du serpent
# Merdi 8 avril
J'ai travailler sur le fonctionnement des panel 
j'ai creer un la classe qui vas recevoir notre panel et dessus j'ai initialiser toute nos varialble
dans cette classe j'ai code toutes les fonction (paintComponent(Graphics g2),drawRectangle(Graphics g),palceCible(),collision(Tile tile1,Tile tile2),move(),keyPressed(KeyEvent e) )
tout les appls des fonctions se font faite dans le constructeur de la classe du panel(class GamePanel extends JPanel).

# Difficulte 8 avril
0- probleme u niveau de la fenetre principale qui recoit le panel  jFrame1.setBounds(100, 100, 614, 635); ici avec  jFrame1.setBounds(100, 100, 600, 600); ca n efonctionnement pas 
1- Lors de la compilation le button start s'execute une seul fois et lorsque la fenetre du jeu est ferme et on reclique sur start le programme ne reouvre plus la fenetre du jeu
2- Lorsque le serpent entre dans une condition de Game over juste la tete dois normalement sortir et le corp dois rester dansla fenetr edu jeu
