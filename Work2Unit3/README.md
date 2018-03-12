# Análise de Confiabilidade através de Distribuições Contínuas 

 Este repositório contém um notebook contendo um estudo sobre diferentes configurações de redundância:
**TMR**, **5MR** e **paralela** com 2, 3 e 4 dispositivos. Internamente é utilizada as distribuições 
exponenciais e hipoexponenciais. Sem falar que, ao término do notebook, é apresentado uma análise quanto 
a justificativa do uso da redundância mediante ao valores temporais analisados.

	Obs.: MTTF = tempo médio de vida

## Redundância TMR e 5MR

A Redundância Tripla Modular, também conhecida por _Redundância TMR_ é uma técnica de redução de falhas 
que funciona triplicando-se o hardware, fazendo com que trabalhem em paralelo. Por conseguinte, 
o resultado final será o valor o valor mais aproximado em relação aos 3 sistemas. Além disso, caso 1 ou 
2 dos sistemas falhem, haverá o 3 para cobrir a falha.

Em contrapartida a TMR que utiliza da triplicação de hardware, a  5M5 quintuplica o hardware. Consequentemente,
tudo que ocorre com a TMR também acontece com a 5MR modicando-se que, trata-se de 5 hardwares e, por isso, haverá
4 hardwares para cobrirem as falhas.

# Link
 https://youtu.be/br4DHhi3F04
## Autor

Samuel Lucas de Moura Ferino(_samuel797@gmail.com_)