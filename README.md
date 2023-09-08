#Modelo Mundo
class Blackjack:
    def __init__(self):
        self.jugador = None
        self.casa = None
        self.baraja = None

        def iniciar_juego(self, apuesta):
            self.casa.mano.es_blackjack():
            (self.jugador.mano.es_blackjack() or valor_casa > 21) or \
            (valor_jugador <= 21 and valor_jugador > valor_casa):(
                print("¡El jugador gana!"))
class Mano:
    self.jugador.mano.valor() > 21:
    valor_jugador = self.jugador.mano.valor()
    self.casa.mano.destapar_carta_oculta()
    valor_casa = self.casa.mano.valor()
class Jugador:
    def hacer_jugada_jugador(self, tipo_jugada):
        tipo_jugada == "pedir_carta":
        self.finalizar_juego("jugador_pierde")
        tipo_jugada == "plantarse":
        self.finalizar_juego("plantarse")

        def finalizar_juego(self, resultado):
            resultado == "jugador_pierde":
            resultado == "plantarse":
            self.jugador.fichas += self.jugador.apuesta * 2
            (self.casa.mano.es_blackjack() or valor_jugador > 21) or \
            (valor_casa <= 21 and valor_casa >= valor_jugador):
            print("¡El jugador perdió!")
            self.jugador.fichas -= self.jugador.apuesta
            valor_jugador == valor_casa:(
                print("¡Es un empate!"))
            self.jugador.fichas += self.jugador.apuesta
            self.jugador.fichas > 0:
            print("Tienes {} fichas disponibles.".format(self.jugador.fichas))
            print("1. Iniciar nuevo juego")
            print("2. Salir de la aplicación")
            opcion = input("Selecciona una opción: ")
            opcion == "1":(
            self.iniciar_juego())
            opcion == "2":(
                print("Gracias por jugar. ¡Hasta la próxima!"))
            print("Opción no válida. Saliendo del juego.")

            print("Te has quedado sin fichas. La partida ha terminado.")
            print("¡Gracias por jugar!")


class Carta:
    carta = self.baraja.repartir_carta()
    self.casa.mano.agregar_carta(carta)
class Casa:
    self.jugador.mano.agregar_carta(carta)
    self.hacer_jugada_casa()
    def hacer_jugada_casa(self):
        self.finalizar_juego("casa_gana")
        valor_casa = self.casa.mano.valor()
        valor_casa <= 16 and valor_casa < self.jugador.mano.valor():
        valor_casa > 21:
        self.finalizar_juego("jugador_gana")
        valor_casa <= 21 and valor_casa >= self.jugador.mano.valor():
        self.finalizar_juego("casa_gana")
        self.finalizar_juego("jugador_gana")
        def hacer_jugada_casa(self):
            valor_jugador = self.jugador.mano.valor()
            valor_casa = self.casa.mano.valor()
class Baraja:
    carta = self.baraja.repartir_carta()