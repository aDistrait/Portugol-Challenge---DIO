programa
{
	
	funcao inicio()
	{
		real mes1,mes2,mes3,mes4,media,total
		cadeia funcionario

		escreva("Digite o nome do funcionário: ")
		leia(aluno)

		escreva("Agora, insira o total de vendas realizado no mês de janeiro do funcionario " +funcionario +", por favor: ")
		leia(nota1)
		escreva("Digite o total de vendas realizado no mês de fevereiro do funcionário " +funcionario +", por favor: ")
		leia(nota2)
		escreva("Digite o total de vendas realizado no mês de março do funcionário " +funcionario +", por favor: ")
		leia(nota3)
		escreva("Digite o total de vendas realizado no mês de abril do funcionário " +funcionario +", por favor: ")
		leia(nota4)

		media = (mes1+mes2+mes3+mes4)/4
		total = (mes1+mes2+mes3+mes4)
		
		escreva("O funcionário "+funcionario "realizou um total de venda de " +total " e teve a seguinte média de vendas: " +media )
		
	}
}
