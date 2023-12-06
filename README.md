# ......
class MensajeDeAmor:
    def __init__(self, destinatario, contenido):
        self.destinatario = destinatario
        self.contenido = contenido

    def imprimir_mensaje(self):
        print(f"Querido/a {self.destinatario},\n{self.contenido}")

def main():
    destinatario = "Lucía"
    contenido = "Espero que este mensaje te haga sonreír. Te quiero mucho."
    
    mensaje = MensajeDeAmor(destinatario, contenido)
    mensaje.imprimir_mensaje()

if __name__ == "__main__":
    main()
