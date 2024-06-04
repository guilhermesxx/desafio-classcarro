class Carro:
    def __init__(self):
        self.nome = "ftype"
        self.marca = "jaguar"
        self.idade = "11"
        self.cor_carro = "vermelho"

    def acelerar(self):
        return f"O carro {self.nome} está andando."

    def frear(self):
        return f"O carro {self.nome} está freando."

meu_carro = Carro()
print(meu_carro.acelerar())  
print(meu_carro.frear())  
