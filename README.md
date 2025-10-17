# Limites definidos pela escola
limite_ingressos = 100
limite_convidados = 20

# Leitura dos dados
alunos = int(input("Digite a quantidade de alunos: "))
monitores = int(input("Digite a quantidade de monitores: "))
convidados = int(input("Digite a quantidade de convidados: "))

# Cálculo do total de pessoas
total_pessoas = alunos + monitores + convidados

# Verificações das condições
if total_pessoas > limite_ingressos:
    print("❌ O total de pessoas excede o limite de 100 ingressos!")
elif convidados > limite_convidados:
    print("❌ O número de convidados ultrapassa o limite de 20 permitido!")
else:
    print("✅ Tudo certo! O evento está dentro dos limites permitidos.")
    print(f"Total de pessoas: {total_pessoas}")

