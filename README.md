# MaratonKenzie---Kenzie-Academy
Entrega para treinar os conceitos de Javascript e de lógica.


🏁 Entrega - Funções e Arrays
Importante!

Lembre-se de que essa entrega é individual e qualquer suspeita de plágio ou interferência na entrega de outro aluno pode ser questionada pela equipe de ensino.

Você está trabalhando nos bastidores do Maraton Kenzie. Não tem mais hipóteses do cenário mudar além dos três que já lideram a prova, a distância para o quarto colocado já é enorme.

Rafael, Manoel e Daniel estão em uma disputa acirrada para conquistar a primeira posição.

Daniel tem vantagem, pois, no percurso, conseguiu cumprir a tarefa extra. Desenvolva a função para criarmos o pódio.
🧠 Lógica - Maraton Kenzie

Para esta entrega você irá exercitar os conceitos de funções, condicionais e array's

    Crie uma array que contenha os nomes de Rafael, Manoel e Daniel.
    
    Crie uma função chamada positions. Esta função deverá receber como parâmetro o array contendo os nomes dos atletas.
    A posição do elemento no array representa sua posição na corrida.
    
    O competidor Daniel realizou o desafio extra, e ganhou um bônus. Ele sempre vai subir uma posição.
    
    Sendo assim, o Daniel trocará de lugar com quem estiver na posição a frente dele, caso haja.
    
    Verifique se a posição do elemento 'Daniel' no array é diferente de 0, caso seja, ele deverá trocar de lugar com quem está à sua frente. Caso contrário retorne; 'Daniel é o vencedor'
    
    Retorne o array resultante concatenado com a frase: 'Este é o pódio'.
    Chame a função usando o console.log(), para conseguir ler seu retorno.
    

Dica!

Para definir o pódio com base no índice no retorno, será necessário que se tratem os valore o valores dos índices.

Lembre-se um array se inicia na posição 0, em uma competição o primeiro colocado é 1 e não 0.

Desenvolva a lógica que vai relacionar a posição do array com a posição do competidor.

Exemplo

function position(arrayCompetidores){
  if(condição){
    Lógica
    return 
  }else{
    Lógica 
    return
  }
}

Dica!

Lembre-se dos conceitos das aulas passadas. Vimos anteriormente algumas formas de concatenar posição de array's com string's.

Você deverá pensar em uma forma de realizar a troca de posições em um array sem perder valores.

Use uma variável auxiliar para armazenar o valor do elemento cuja posição receberá o elemento 'Daniel'. Use o método indexOf para capturar a posição de Daniel.
