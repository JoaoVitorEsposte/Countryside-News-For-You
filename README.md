# Countryside-News-For-You
Site fictício de notícias do interior

Meu obejetivo com este projeto foi me desafiar ao máximo no HTML e CSS, e construir um site totalmente estruturado com Grids e Flex-box. Utilizar essas duas
tecnologias em conjunto foi um desafio, porém percebi que elas potencializam o controle que temos sobre o layout do site. Por exemplo, na página principal todas as chamadas para as notícias estão perfeitamente alinhadas, isso só foi possível graças à grid que contem as notícias, como se nota na imagem abaixo: 

![index](https://user-images.githubusercontent.com/102496892/165867169-4d627e7e-0fb3-49fc-b8d1-3e9b9245bb85.png)

Ainda na imagem em questão se percebe que cada item do header está composto por vários elementos, como ícone, título e legenda, e que esse padrão se repete. Cada item do header é uma grid que contém esses elementos menores, e as três grids estão alinhadas dentro de um Flex-box com flex-direction: row;, o qual está dentro da primeira linha da grid principal que organiza toda a página.

O formulário da página de contato também foi estruturado com CSS Grid, e o resultado foi o seguinte:
![form](https://user-images.githubusercontent.com/102496892/165867715-edc65c99-ca06-42d9-ac67-07739e0f31d2.png)

Com relação à página que exibe o conteúdo das notícias, o menu lateral não ficou dentro de uma Grid, pois utilizei o position: sticky, dessa forma o menu se mantém na mesma posição mesmo que o usuário desça a página com o scroll. Esse menu é responsável por posicionar a tela do usuário nos pontos marcados no corpo da notícia através de âncoras com a tag <a>.
