# Beat-Maker
This Repo is to create a Beat Maker using Python and PyGame.

## Notes

### Pygame Config
    - pygame.init() - start a pygame instance
    - pygame.quit() - quit a pygame instance
    - pygame.display
        -set_mode([WIDTH, HEIGHT]) -> outputs the surface
        -set_caption('Caption')
    - pygame.font.Font('font.ttf', size) -> outputs font to use in other
        -  pygame.font.Font().render('Text to show', Anti-Alias(bool), color)
    - pygame.draw -> used to draw shapes on the screen
        -rect(screen, color(rgb tuple), [left, top, width, height], fill(0 -> solid), rounded_edge)
        -line(screen, color, (start_x, start_y), (end_x, end_y), fill)
    - screen.blit(pygame.font.Font().render(), (x,y))

### Pygame Mixer
    - mixer.Sound('sound.wav') -> Returns a mixer object
    - mixer.Sound('sound.wav').play() -> plays the sound from the object created above 



Based on the Tutorial: https://www.youtube.com/watch?v=F3J3PZj0zi0&ab_channel=freeCodeCamp.org
