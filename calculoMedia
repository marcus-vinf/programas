# média
# =média(c7+e7)


# p1 p2 p3 div 10
# =média(c7 + e7 +h7) / 10


# p1 p2 div 6
# =MÉDIA(C7+E7)/6


#recebendo as notas e multiplicando


print("""
                                                                       
eeee eeeee e     eeee e   e e     eeeee eeeee eeeee eeeee  eeeee
8  8 8   8 8     8  8 8   8 8     8   8 8   8 8  88 8   8  8   8
8e   8eee8 8e    8e   8e  8 8e    8eee8 8e  8 8   8 8eee8e 8eee8
88   88  8 88    88   88  8 88    88  8 88  8 8   8 88   8 88  8
88e8 88  8 88eee 88e8 88ee8 88eee 88  8 88ee8 8eee8 88   8 88  8
                                                                 
      """)


while True:
	n1 = float(input("digite a 1º nota: "))
	n1m = n1 * 2

	n2 = float(input("digite a 2º nota: "))
	n2m = n2 * 4

	mNota = n1m + n2m
	mNotaFinal = 0




	if mNota >= 30:
		mNotaFinal = mNota / 6
		print(f"Nota1: {n1}, Nota2: {n2}, Média Final: {mNotaFinal}")


	elif mNota < 30:
		print("aluno abaixo da média")
		mNotaAtual = mNota / 10
		print(f"Média atual: {mNotaAtual}")
		n3 = float(input("caso houver, digite a 3º nota: "))
		n3m = n3 * 4
		mNotaFinal = (mNota + n3m) / 10

		print(f"Nota1: {n1}, Nota2: {n2}, Média Final: {mNotaFinal}")
	else:
		print("valor inválido")

		resp = input("deseja calcular média ? (s/n): ")
		if resp != "s":
			break
