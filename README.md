# the-art-of-software-testing
Anotações feitas da leitura do livro [_The Art of Software Testing_](https://www.amazon.com/Art-Software-Testing-Glenford-Myers/dp/1118031962) dos autores Glenford J. Myers, Corey Sandler e Tom Badgett.

## Prefácio

> Em 1979, Glenford Myers publicou um livro que se tornou um clássico.
> The Art of Software Testing resistiu ao teste do tempo.
>
> O livro por si só deu à indústria um guia fundamental e duradouro para um dos tópicos mais importantes: Como garantir que todo o software que você produz faça o que foi projetado para fazer?
>

## Introdução

> Na época em que o livro foi lançado, em 1979, era uma regra prática bem conhecida que, em um projeto de programação típico, aproximadamente 50% do tempo decorrido e mais de 50% do custo total eram gastos no teste do programa ou sistema em desenvolvimento.
>
> Hoje, um terço de século e duas atualizações de livros depois, o mesmo se aplica. Novos sistemas de desenvolvimento, linguagens com ferramentas integradas e programadores que estão acostumados a desenvolver mais rapidamente. Mas os testes continuam a desempenhar um papel importante em qualquer projeto de desenvolvimento de software.
>
> - Os testes de programas deveriam ser refinados e transformados em uma ciência exata, mas na verdade parece que sabemos menos sobre teste de software do que sobre qualquer outro aspecto do desenvolvimento de softwrare.
>
> - Apesar de existirem mais livros e artigos hoje em dia, mas mesmo assim os testes permanecem entre as "artes obscuras" do desenvolvimento de softwrare.
>
> - Objetivo do livro é o mesmo em 1979 e 2004: preencher as lacunas de conhecimento. É um livro de discussão prática e não teorica.
>
>

## Um teste de autoavaliação

> O Teste de software se tornou mais difícil e fácil do que nunca.
>
> - Difíceis devido à vasta gama de linguagens de progamação, sistemas operacionais e plataformas de hardware que evoluíram décadas seguintes.
> - Fáceis, em alguns aspectos, porque o conjunnto de softwrae e sistemas operacionais são muito mais sofisticados do que no passado, fornecendo rotinas intrísecas e bem testadas que podem ser incorporadas em aplicações sem a necessidade de um programador para desenvolvê-los do zero.
>
>
## Capítulo 2: A psicologia e a economia dos testes de software

> O teste de software é uma tarefa técnica, mas também envolve algumas considerações importantes de economia e psicologia humana.
>
> "No mundo ideal, gostariamos de testar absolutamente tudo em um programa, mas na maioria dos casos, porém, isso simplesmente não é possível. Mesmo um programa simples pode ter centenas ou milhares de combinações possíveis de entradas e saídas."
>
> "O teste completo de uma aplicação complexa levaria muito tempo e exigiria muitos recursos humanos para ser economicamente viável. Além disso, o testador de software precisa da atitude adequada (talvez "visão" seja uma palavra melhor) para testar com sucesso um aplicativo de software. Em alguns casos, a atitude do testador pode ser mais importante do que o próprio processo em si."
>
> ### A psicologia dos testes
>
> " Uma das principais causas de testes de aplicativos inadequados é o fato de que a maioria dos programadores começa com uma definicação falsa do termo."
>
> "Agregar valor por meio de testes significa aumentar a qualidade ou a confiabilidade do programa. Aumentar a confiabilidade do programa significa encontrar e remover erros. Portanto, não teste um programa para mostrar que ele funciona; em vez disso, comece com a suposição de que o programa contém errps (uma suposição válida para quase todos os programas) e então teste o programa para encontrar o maior número de erros possíveis."
>
> "Teste é o processo de execução de um programa com a intenção de encontrar erros."
>
> "Os seres humanos tendem a ser altamente orientados para objetivps, e estabelecer o objetivo adequado tem um egeito psicológico importante sobre eles. Se nosso objetivo é demonstrar que um programa não contém erros, então seremos subconscientemente direcionados para esse objetivo, ou seja, tendemos a selecionar dados de teste que tenham baixa probabilidade de causar falha no programa. Por outro lado, terão maior probabilidade de encontrar erros."
>
>