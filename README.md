# kjkkkkkk


def introdução():
    print("blablablabla.")
    print("blablablablablablabmanmablabmablablablablablablablabla")

players =[
    {"nome":"personagem1","vida":25,"ataque":3},
    {"nome":"personagem2","vida":30,"ataque":4.5},
    {"nome":"personagem3","vida":42.0,"ataque":7}

]

inimigo= [
    {"nome1":"inimigo1", "vida":15,"ataque":10},
    {"nome2":"inimigo2","vida":20,"ataque":15},
    {"nome3":"inimigo3","vida":25,"ataque":17}
]

def escolha_persongem():
    print("Escolha seu persongem:")
    for i in range(len(players)):
        player = players[i]
        
    while True:
        escolha = input("digite o numero do player escolhido: ")
        if escolha.isdigit() and 1 <= int(escolha) <= len(players):
            player_escolhido = player[int(escolha)- 1]:
                return player_escolhido
        else:
        print("opção inválida")

        
def batalha(player,inimigo):
    print(f "blablablablabmablabman")
    eai =input("blablablablablanlanms? (atacar/fugir))")
    
    while inimigo["vida"] > 0:
        if eai == "atacar":
            while player_escolhido["vida"] >= inimigo["nome1","ataque"]
 itens = ["coisa1","coisa2","coisa3"]
inventario = []

def explorar():
    print("vc encontrou tal coisa blanlanlan? (sim/nao)")
    if acao.lower() == "sim":
        item_encontrado = random.choice(itens)
        inventario.append(item_encontrado)
        print(f"vc encontrou um {item_encontrado}")
        return
    elif acao.lower() == "nao":
        print("vc nao quis e blablablabla")
        return
    else:
        print("opçao inválida")           
    
caminho = input("qual caminho vc escolhe entrar? (esquerda/direita)")
    if ruas == "direita":
        print("blablablanlanlan")
    elif ruas == "esquerda":
        print("blablablablablablablab")
    else:
        print("opção invalida.")
    batalha(player,inimigo)
