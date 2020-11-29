# Anotações e resumo sobre o funcionamento do Flexbox.

 <h3>Display:</h3> Define o elemento como flex-container, e torna todos os seus filhos flex-itens

  * display: flex; → O elemento se torna um flex-container, e automaticamente transforma tabém seus filhos diretos em flex-itens
  <p align="center"><img src="https://i.imgur.com/3R9W1Nr.png"/></p>
    
  Apenas com o "display: flex;" os itens podem estourar o container!

  * "flex-wrap" Define se o item quebra ou não quebra, por padrão ele vem setado como "flex-wrap: nowrap" (não quebra), então caso desejamos ter quebra nos itens         para não estourar o container devemos utilizar o "flex-wrap: wrap".

  No primeiro container da imagem abaixo o flex-wrap esta padrãp ("nowrap") já no segundo container ele foi setado para "flex-wrap: wrap" portando ele quebrou os       elementos para a linha debaixo

  Uma outra diferença também é que temos os elementos ocupando o total do container, diferente da primeira imagem, para isso utilizamos o comando "flex: 1".
    
  <p align="center"><img src="https://i.imgur.com/00DNFmc.png"/></p>
  
  <h3>Flex-direction:</h3>
    Define a direção que os flex-itens devem ter.
    
   * "flex-direction: row;" Define os itens em linha</br>
   <p align="center"><img src="https://i.imgur.com/37N4J67.png"/></p>
   * "flex-direction: row-reverse;" Inverte os itens da linha (3-2-1)</br>
   <p align="center"><img src="https://i.imgur.com/uhh9K2O.png"/></p>
   * "flex-direction: column;" Define os itens em coluna, um abaixo do outro</br>
   <p align="center"><img src="https://i.imgur.com/m2uWqel.png"/></p>
   * "flex-direction: column-reverse;" Define os itens em coluna, um abaixo do outro porém invertido (3-2-1)</br>
   <p align="center"><img src="https://i.imgur.com/qiQJC6l.png"/></p>
   
   
