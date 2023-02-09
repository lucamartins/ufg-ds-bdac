# Biblioteca Digital de Artigos Científicos

Disciplina de Design de Software (INF/UFG)

Professor orientador: Fabio Nogueira de Lucena

## Integrantes do grupo
- Adriel Lenner Mori (202004741)
- Igor Moreira Pádua (202009567)
- João Pedro Soares Nery (202204197)
- Luca Santos Martins (202004765)
- Paulo Roberto Vieira (202009580)

## Escopo e objetivos
A Biblioteca Digital de Artigos Científicos tem como objetivo registrar e arquivar a produção científica realizada por pesquisadores de diversas instituições do país.

Hoje em dia, nos eventos científicos não há algum tipo de registro dos artigos apresentados. O sistema foca justamente em resolver essa problemática, impulsionando a divulgação científica e servindo como uma base de apoio para que pesquisadores consigam mais facilmente encontrar tais produções.

Os Requisitos que levantamos foram especificados em um documento que esta no seguinte arquivo:[Documento de Requisitos](https://github.com/lucamartins/DS-BDAC/blob/main/Documento%20de%20Requisitos%20de%20Software.pdf).

## Design e Arquitetura
No âmbito mais geral do contexto de divulgação científica, o sistema não funcionará como substituto para bibliotecas digitais existentes. Assim, produções como teses e dissertações continuam nas famosas Bibliotecas Digitais de Teses e Dissertações (BDTD). Da mesma forma, artigos científicos permanecem com seus respectivos produtores. O contexto que envolve o sistema proposto pode ser verificado através do seguinte diagrama: [Diagrama de Contexto](https://github.com/lucamartins/DS-BDAC/blob/main/Diagrama%20de%20Contexto.pdf).

De forma de alto nível, mas especificando um pouco mais o software proposto, apresentamos os containers que possuem a pretensão de mostrar como os diferentes componentes interagem uns com os outros e como eles são agrupados em containers, tal diagrama pode ser verificado em: [Diagrama de Containers](https://github.com/lucamartins/DS-BDAC/blob/main/Diagrama%20de%20Containers.pdf).

Inicialmente os sistemas externos que prevemos interação com o nosso sistema de Biblioteca Digital de Artigos Científcios (BDAC) não serão muitos estes podem ser conferidos em: [Sistemas externos](https://github.com/lucamartins/DS-BDAC/blob/main/DS%20-%20Sistemas%20externos.pdf).

Uma API de biblioteca digital pode ser utilizada para integrar a BDAC com outros sistemas, como sistemas de gerenciamento de conteúdo, sistemas de e-commerce, sistemas de recomendação, entre outros. Os componentes da API construídos para Biblioteca Digital de Artigos Científicos podem ser conferidos em: [Diagrama Componenste da API](https://github.com/lucamartins/DS-BDAC/blob/main/Components%20Diagram%20(API).pdf).

Elencamos as camadas que **podem** compor um sistema de biblioteca digital e seus sub componentes, ressaltamos que nem tudo que foi citado neste documento deve compor a arquitetura e o design de uma biblioteca digital, cabe analisar o contexto, assim sendo, este não se propõe a ser exaustivo e nem determinista nas possibilidades tanto de arquitetura quando design, verifique as possiveis camada e seus sub componentes no documento, [Arquitetura e Design](https://github.com/lucamartins/DS-BDAC/blob/main/Arquitetura_E_Design_Sistema_Biblioteca.pdf).

Esboçamos a modelagem de banco de dados para o sistema no seguinte diagrama:[Banco de Dados](https://github.com/lucamartins/DS-BDAC/blob/main/Banco%20de%20dados.png).

Construímos também a modelagem das classes em outro documento que pode ser conferido em:[Diagrama de Classes](https://github.com/lucamartins/DS-BDAC/blob/main/diagrama_classe.png).

Um esboço de tela inicial apresentamos em [Protótipo](https://www.figma.com/file/CcuZC9CIQjf0X2kTvhrVyZ/MS-Dashboard?node-id=10634%3A71644).

Palavras-chave:
- Biblioteca Digital

- Artigos Científico

- Produção Científica
