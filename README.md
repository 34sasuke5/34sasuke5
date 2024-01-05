print("Hello, World!")
import pygame
import sys

# Initialisation de Pygame
pygame.init()

# Définir la taille de la fenêtre
size = (800, 600)

# Créer la fenêtre
screen = pygame.display.set_mode(size)
pygame.display.set_caption("Mon Premier Jeu")

# Boucle principale
running = True
while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

    # import pygame
import sys

# Initialisation de Pygame
pygame.init()

# Définir la taille de la fenêtre
size = (800, 600)

# Créer la fenêtre
screen = pygame.display.set_mode(size)
pygame.display.set_caption("Mon Premier Jeu")



    # Rafraîchir l'écran
    pygame.display.flip()

# Quitter Pygame
pygame.quit()
sys.exit()
