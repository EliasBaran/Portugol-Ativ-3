# Portugol-Ativ-3

Exercício 1-A e B

programa {
	funcao inicio() {
	    
	    inteiro MesA, DiaA, MesR, DiaR
	    
	    escreva("que mês é este? ")
	    leia (MesA)
	    
	    escreva ("que dia é hoje? ")
	    leia (DiaA)
	    
	    MesR = 12 - MesA
	    DiaR = MesR * 30 - DiaA
	    
	    escreva ("restam ", MesR, " meses ou ", DiaR, " dias")
		
	}
}

Exercício 2-A e B

programa {
	funcao inicio() {
		
		real produto1 = 800, produto2 = 1200, Total, Desconto, Total2 
		
		Total = produto1 + produto2 
		escreva ("o total é de ", Total, " v-bucks \n")
		
		Desconto = Total * 0.3
		Total2 = Total - Desconto
		escreva("mas com o desconto fica ", Total2, " v-bucks")
	}
}
