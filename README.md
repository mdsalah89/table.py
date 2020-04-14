# table.py

import pygame

# Initializera PyGame
pygame.init()

# skapar ett ny fönster för spelet
win = pygame.display.set_mode((1000, 1000))

# välkommen titel för spelet
pygame.display.set_caption('PyGame Tic-Tac-Toe')

# Dra spelbrädet
first = pygame.draw.rect(win, (255, 255, 255), (25, 25, 150, 150))
second = pygame.draw.rect(win, (255, 255, 255), (200, 25, 150, 150))
third = pygame.draw.rect(win, (255, 255, 255), (375, 25, 150, 150))
fourth = pygame.draw.rect(win, (255, 255, 255), (550, 25, 150, 150))
fifth = pygame.draw.rect(win, (255, 255, 255), (725, 25, 150, 150))
sixth = pygame.draw.rect(win, (255, 255, 255), (25, 200, 150, 150))
seventh = pygame.draw.rect(win, (255, 255, 255), (200, 200, 150, 150))
eighth = pygame.draw.rect(win, (255, 255, 255), (375, 200, 150, 150))
ninth = pygame.draw.rect(win, (255, 255, 255), (550, 200, 150, 150))
tenth = pygame.draw.rect(win, (255, 255, 255), (725, 200, 150, 150))
eleventh = pygame.draw.rect(win, (255, 255, 255), (25, 375, 150, 150))
twelveth = pygame.draw.rect(win, (255, 255, 255), (200, 375, 150, 150))
thirtheenth = pygame.draw.rect(win, (255, 255, 255), (375, 375, 150, 150))
fourteenth = pygame.draw.rect(win, (255, 255, 255), (550, 375, 150, 150))
fifteenth = pygame.draw.rect(win, (255, 255, 255), (725, 375, 150, 150))
sixteeth = pygame.draw.rect(win, (255, 255, 255), (25, 550, 150, 150))
seventeenth = pygame.draw.rect(win, (255, 255, 255), (200, 550, 150, 150))
eighteenth = pygame.draw.rect(win, (255, 255, 255), (375, 550, 150, 150))
nineteenth = pygame.draw.rect(win, (255, 255, 255), (550, 550, 150, 150))
twentyteeth = pygame.draw.rect(win, (255, 255, 255), (725, 550, 150, 150))
twentyoneth = pygame.draw.rect(win, (255, 255, 255), (25, 725, 150, 150))
twentytooth = pygame.draw.rect(win, (255, 255, 255), (200, 725, 150, 150))
twentythird = pygame.draw.rect(win, (255, 255, 255), (375, 725, 150, 150))
twentyfourth = pygame.draw.rect(win, (255, 255, 255), (550, 725, 150, 150))
twentyfifth = pygame.draw.rect(win, (255, 255, 255), (725, 725, 150, 150))

# Ställer in den första spelarens form
draw_object = 'circle'

# kolla om utrymme tas 
first_open = True
second_open = True
third_open = True
fourth_open = True
fifth_open = True
sixth_open = True
seventh_open = True
eighth_open = True
ninth_open = True
tenth_open = True
eleventh_open = True
twelveth_open = True
thirtheenth_open = True
fourteenth_open = True
fifteenth_open = True
sixteeth_open = True
seventeenth_open = True
eighteenth_open = True
nineteenth_open = True
twentyteeth_open = True
twentyoneth_open = True
twentytooth_open = True
twentythird_open = True
twentyfourth_open = True
twentyfifth_open = True


# Main Loop
run = True
while run:

    # Refresh Time
    pygame.time.delay(100)

    # Pygame Events
    for event in pygame.event.get():

        # Quit Event
        if event.type == pygame.QUIT:
            run = False

        # Space bar to reset
        if event.type == pygame.KEYDOWN:
            if event.key == pygame.K_SPACE:
                first_open = True
                second_open = True
                third_open = True
                fourth_open = True
                fifth_open = True
                sixth_open = True
                seventh_open = True
                eighth_open = True
                ninth_open = True
                tenth_open = True
                eleventh_open = True
                twelveth_open = True
                thirtheenth_open = True
                fourteenth_open = True
                fifteenth_open = True
                sixteeth_open = True
                seventeenth_open = True
                eighteenth_open = True
                nineteenth_open = True
                twentyteeth_open = True
                twentyoneth_open = True
                twentytooth_open = True
                twentythird_open = True
                twentyfourth_open = True
                twentyfifth_open = True

                run = True
                # pygame.draw.rect(surface, (color), (startx,starty,length width))
                first = pygame.draw.rect(win, (255, 255, 255), (25, 25, 150, 150))
                second = pygame.draw.rect(win, (255, 255, 255), (200, 25, 150, 150))
                third = pygame.draw.rect(win, (255, 255, 255), (375, 25, 150, 150))
                fourth = pygame.draw.rect(win, (255, 255, 255), (550, 25, 150, 150))
                fifth = pygame.draw.rect(win, (255, 255, 255), (725, 25, 150, 150))
                sixth = pygame.draw.rect(win, (255, 255, 255), (25, 200, 150, 150))
                seventh = pygame.draw.rect(win, (255, 255, 255), (200, 200, 150, 150))
                eighth = pygame.draw.rect(win, (255, 255, 255), (375, 200, 150, 150))
                ninth = pygame.draw.rect(win, (255, 255, 255), (550, 200, 150, 150))
                tenth = pygame.draw.rect(win, (255, 255, 255), (725, 200, 150, 150))
                eleventh = pygame.draw.rect(win, (255, 255, 255), (25, 375, 150, 150))
                twelveth = pygame.draw.rect(win, (255, 255, 255), (200, 375, 150, 150))
                thirtheenth = pygame.draw.rect(win, (255, 255, 255), (375, 375, 150, 150))
                fourteenth = pygame.draw.rect(win, (255, 255, 255), (550, 375, 150, 150))
                fifteenth = pygame.draw.rect(win, (255, 255, 255), (725, 375, 150, 150))
                sixteeth = pygame.draw.rect(win, (255, 255, 255), (25, 550, 150, 150))
                seventeenth = pygame.draw.rect(win, (255, 255, 255), (200, 550, 150, 150))
                eighteenth = pygame.draw.rect(win, (255, 255, 255), (375, 550, 150, 150))
                nineteenth = pygame.draw.rect(win, (255, 255, 255), (550, 550, 150, 150))
                twentyteeth = pygame.draw.rect(win, (255, 255, 255), (725, 550, 150, 150))
                twentyoneth = pygame.draw.rect(win, (255, 255, 255), (25, 725, 150, 150))
                twentytooth = pygame.draw.rect(win, (255, 255, 255), (200, 725, 150, 150))
                twentythird = pygame.draw.rect(win, (255, 255, 255), (375, 725, 150, 150))
                twentyfourth = pygame.draw.rect(win, (255, 255, 255), (550, 725, 150, 150))
                twentyfifth = pygame.draw.rect(win, (255, 255, 255), (725, 725, 150, 150))

        # Used to see which space is clicked
        if event.type == pygame.MOUSEBUTTONUP:
            pos = pygame.mouse.get_pos()

            # Checks if mouse position is in a space and if space is available
            if first.collidepoint(pos) and first_open:
                # Draws a shapes based on whose turn it is
                if draw_object == 'circle':
                    # pygame.draw.circle(surface, (color), (centerx, centery),radius)
                    pygame.draw.circle(win, (255, 0, 0), (100, 100), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (50, 50, 100, 100))
                    draw_object = 'circle'
                # Marks this space as taken
                first_open = False

            if second.collidepoint(pos) and second_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (275, 100), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (225, 50, 100, 100))
                    draw_object = 'circle'
                second_open = False

            if third.collidepoint(pos) and third_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (450, 100), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (400, 50, 100, 100))
                    draw_object = 'circle'
                third_open = False

            if fourth.collidepoint(pos) and fourth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (625, 100), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (575, 50, 100, 100))
                    draw_object = 'circle'
                fourth_open = False

            if fifth.collidepoint(pos) and fifth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (800, 100), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (750, 50, 100, 100))
                    draw_object = 'circle'
                fifth_open = False

            if sixth.collidepoint(pos) and sixth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (100, 275), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (50, 225, 100, 100))
                    draw_object = 'circle'
                sixth_open = False

            if seventh.collidepoint(pos) and seventh_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (275, 275), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (225, 225, 100, 100))
                    draw_object = 'circle'
                seventh_open = False

            if eighth.collidepoint(pos) and eighth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (450, 275), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (400, 225, 100, 100))
                    draw_object = 'circle'
                eighth_open = False

            if ninth.collidepoint(pos) and ninth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (625, 275), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (575, 225, 100, 100))
                    draw_object = 'circle'
                ninth_open = False

            if tenth.collidepoint(pos) and tenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (800, 275), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (750, 225, 100, 100))
                    draw_object = 'circle'
                tenth_open = False

            if eleventh.collidepoint(pos) and eleventh_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (100, 450), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (50, 400, 100, 100))
                    draw_object = 'circle'
                eleventh_open = False

            if twelveth.collidepoint(pos) and twelveth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (275, 450), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (225, 400, 100, 100))
                    draw_object = 'circle'
                twelveth_open = False

            if thirtheenth.collidepoint(pos) and thirtheenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (450, 450), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (400, 400, 100, 100))
                    draw_object = 'circle'
                thirtheenth_open = False

            if fourteenth.collidepoint(pos) and fourteenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (625, 450), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (575, 400, 100, 100))
                    draw_object = 'circle'
                fourteenth_open = False

            if fifteenth.collidepoint(pos) and fifteenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (800, 450), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (700, 400, 100, 100))
                    draw_object = 'circle'
                fifteenth_open = False

            if sixteeth.collidepoint(pos) and sixteeth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (100, 625), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (50, 575, 100, 100))
                    draw_object = 'circle'
                sixteenth_open = False

            if seventeenth.collidepoint(pos) and seventeenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (275, 625), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (225, 575, 100, 100))
                    draw_object = 'circle'
                seventeenth_open = False

            if eighteenth.collidepoint(pos) and eighteenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (450, 625), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (400, 575, 100, 100))
                    draw_object = 'circle'
                eighteenth_open = False

            if nineteenth.collidepoint(pos) and nineteenth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (625, 625), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (575, 575, 100, 100))
                    draw_object = 'circle'
                nineteenth_open = False

            if twentyteeth.collidepoint(pos) and twentyteeth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (800, 625), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (750, 575, 100, 100))
                    draw_object = 'circle'
                twentyteeth_open = False

            if twentyoneth.collidepoint(pos) and twentyoneth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (100, 800), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (50, 750, 100, 100))
                    draw_object = 'circle'
                twentyoneth_open = False

            if twentytooth.collidepoint(pos) and twentytooth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (275, 800), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (225, 750, 100, 100))
                    draw_object = 'circle'
                twentytooth_open = False

            if twentythird.collidepoint(pos) and twentythird_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (450, 800), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (400, 750, 100, 100))
                    draw_object = 'circle'
                twentythird_open = False

            if twentyfourth.collidepoint(pos) and twentyfourth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (625, 800), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (575, 750, 100, 100))
                    draw_object = 'circle'
                twentyfourth_open = False

            if twentyfifth.collidepoint(pos) and twentyfifth_open:
                if draw_object == 'circle':
                    pygame.draw.circle(win, (255, 0, 0), (800, 800), 50)
                    draw_object = 'rect'
                else:
                    pygame.draw.rect(win, (0, 255, 0), (750, 750, 100, 100))
                    draw_object = 'circle'
                twentyfifth_open = False
    pygame.display.update()

# slutar spelet när loop också slutar
pygame.quit()
