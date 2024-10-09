-est={}
def menu():
    print('-'*30)
    print(f'{"Dicionário"}:^30')
    print('-'*30)

def gerenciar():
    est={}

def adicio(n1,n2):
    total = n1 + n2
    return total

def altera(n1,n2):
    total = n1 - n2
    return total

def remove(n1,n2):
    total = n1 * n2
    return total

def exibi(n1,n2):
    total = n1 / n2
    return total

def calcula(n1,n2,op):
    if op == "+":
       print(somar(n1,n2))
    elif op == "-":
        print(subtrair(n1,n2))
    elif op in ("*","x","X"):
        print(multiplicar(n1,n2))
    elif op == "/" or op == ":":
        print(dividir(n1,n2))
