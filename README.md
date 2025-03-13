# Verifica-o-de-Tri-ngulos
Um programa que recebe três valores numéricos e determina se eles podem formar um triângulo. 

programa {

	
	funcao inicio() {
	

		real lado1, lado2, lado3

		escreva("Digite a medida do primeiro lado: ")
		leia (lado1)

		escreva("Digite a medida do segundo lado: ")
		leia (lado2)

		escreva("Digite a medida do terceiro lado: ")
		leia (lado3)

		se ((lado1 + lado2 > lado3) e (lado1 + lado3 > lado2) e (lado2 + lado3 > lado1)){
			escreva("É um triangulo ")
		
		se ((lado1 == lado2) e (lado2 ==lado3)){
			escreva("equilatero (Tres lado iguais)")
		} senao se ((lado1 == lado2) ou (lado1 == lado3) ou (lado2 == lado3)){
			escreva("isóceles(Dois lados iguais)")
		} senao {
			escreva("escaleno (Todos os  lados diferentes)")
		}
		
		} senao {
			escreva("Os valores informados não formam um triangulo")
		}
	}
}