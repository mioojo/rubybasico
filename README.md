# Basico do ruby
## por Iago Dorea
Nessa pagina tu vai aprender ruuby do basico ate aonde eu sei kkkkkk
simbora

#Capitulo 1 / Uma simples mensagem
Para imprimir uma simples mensagem no terminal utilizamos o
´´´sh
puts
´´´
* "puts" significa put string
seguiudo das tao famosas aspas
´´´sh
puts "Olá Mundo!"
´´´
Maaas se vc quiser, podemos usar variabeis tambem.
´´´sh
mensagem = "Oi"
puts mensagem
´´´
#Capitulo 2 / Variaveis
Bem.. não tem muito oque falar sobre as variaveis. Sao objetos que nao tem um valor fixo (ou seja, que dê para mudar o valor)
Vai ai um exemplo: 
´´´sh
vara = "oi "
varb = "tudo bem?"
´´´
Você definiu os valores de vara para oi e varb para tudo bem

Agora vamos printar
´´´sh
vara = "oi "
varb = "tudo bem?"

puts vara + varb
´´´
## =Terminal
´´´sh
oi tudo bem?
´´´

Podemos usar valores tambem
´´´sh
vara = 2
varb = 2
puts vara + varb
´´´
## =Terminal
´´´sh
4
´´´
#Capitulo 3 / Pegar e Armazenar respostas
Ok ok ta cansado das coisas basicas! Agora vamos para algo mais avançado!
vamos criar nesse exemplo um chatbot!
usamos "gets" para pegar uma resposta! mas eu recomendo altamente adicionar .chomp no final ficando
´´´sh
gets.chomp
´´´
aqui vai o codigo completo
´´´sh
puts "Oi qual o seu nome"
gets.chomp
puts "Ata ola!"
´´´
quer que fique mais interessante? guarde numa variavel!
´´´sh
puts "Oi qual o seu nome?"
nome = gets.chomp
puts "Ata oi #{nome}"
´´´
* utilizamos #{} para printar uma variavel dentro do programa mas tambem podemos usar + ficando "oi " + nome + " como vai?"
 