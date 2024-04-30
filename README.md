# conversor_binario.py
este código interage com o usuário, e converte em numeros binários o numero decimal que ele escolher
def c_binario(n):
    binario = bin(n)[2:]
    return binario
n = (int(input('digite um numero para ser convertido:')))
resultado = c_binario(n)
print(f"O número {n} em binário é: {resultado}")
