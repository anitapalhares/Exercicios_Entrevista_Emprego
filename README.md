# Exercicios_Entrevista_Emprego

Video de 1h do pythonando




3. Encontrar o Segundo Maior Número (Tempo sugerido: 10 minutos)

# Pergunta: Dada uma lista de números, escreva uma função que retorna o segundo maior número.

[10, 20, 4, 45, 99, 99]

def segundo_maior(lista):
    lista = list(set(lista))  # Removendo duplicatas
    lista.sort(reverse=True)  # Ordenando em ordem decrescente
    return lista[1] if len(lista) > 1 else None
print(segundo_maior([10, 20, 4, 45, 99, 99]))
# Saída esperada: 45


