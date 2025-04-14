# Jeu-sepent
presente une version ameliorer avec plus d'interaction du jeu du serpent
# Merdi 8 avril
J'ai travailler sur le fonctionnement des panels 
j'ai creer un la classe qui vas recevoir notre panel et dessus j'ai initialiser toute nos varialble
dans cette classe j'ai code toutes les fonction (paintComponent(Graphics g2),drawRectangle(Graphics g),palceCible(),collision(Tile tile1,Tile tile2),move(),keyPressed(KeyEvent e) )
tout les appls des fonctions se font faite dans le constructeur de la classe du panel(class GamePanel extends JPanel).

# Difficulte 8 avril
0- probleme au niveau de la fenetre principale qui recoit le panel  jFrame1.setBounds(100, 100, 614, 635); ici avec  jFrame1.setBounds(100, 100, 600, 600); ca ne fonctionnement pas .
1- Lors de la compilation le button start s'execute une seul fois et lorsque la fenetre du jeu est ferme et on reclique sur start le programme ne reouvre plus la fenetre du jeu
2- Lorsque le serpent entre dans une condition de Game over juste la tete dois normalement sortir et le corp dois rester dansla fenetr edu jeu

# Lundi 14 avril
Le probleme 0 de la semaine passe a ete resolu le probleme venais du faite que j'ai creer le deuxieme frame dans le OthersCompoment de la partie Disign.J'ai juste initialise un nouveau jframe dans le boutton satrt game(JFrame jFrame1 = new JFrame("Snake Game");) et cela a resolu le probleme.
De meme cela a permit de rteoudre le probleme 1 de la semaine passer.
Le proble 2 a aussi etais resolu le probleme venait du fait que je n'arraitais pas le timer lorsque le GameOver etias true se qui permettais toujours au serpent de ce deplacer. Pour le faire j'ai juste mit le Timer a stop (gameloop.stop();)

J'ai travailler sur un frame qui apprait et qui affiche le score du joueur lorsqu'il a perdu.
# Difficulte 14 avril
personnalise la frame qui s'affiche lorsque l'utilisateur perd et mettre un boutton qui va lui permettre de recommance.