# CONSIDERAÇÕES

## Estrutura
- Definida uma classe de _init_ para lançar as layers. Foi necessária para as mudanças dinâmicas do estilo de mapa;
- Optado pela organização das classes de acordo com a notação _BEM CSS_;
- Os popups tiveram seu estilo inicial zerado e foi incluído um outro wrapper/container para eles a fim de flexibilizar efeito da animação;
- Há importação direta de _.css_ entre eles, no entanto, seria mais oneroso preparar um ambiente com bundler (e tudo que acaba vindo por necessidade)... e eu estou conciliando o desafio com as últimas entregas do meu trampo anterior, então... 😅

## Estilização
-  Paleta de cores que remeta à cana-de-açucar;
-  Variáveis CSS de cores utilizam valores de _R, G, B_ para poderem ser usadas com as funções _RGB()_ e _RGBA()_;

## Dados/JSON
-  Fez-se necessário incluir um _id_ para cada _feature_ a fim do bom funcionamento do hover (de acordo com a documentação também);
-  Área no mock são imprecisos, podendo gerar estranhamento na comparação de áreas com referência real;
-  Considerei as áreas brutas como sendo em _metros quadrados_, formatando-as para exibição em _hectares_ (conforme referências encontradas no site da SIGMA);
-  Aplicada formatação _pt-BR_ para a área (i.e.: 1.234,56);
