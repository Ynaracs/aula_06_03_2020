# aula_06_03_2020
Repositório para pesquisa de CSS da aula.

# CSS - conceitos e aplicações;

O Cascading Style Sheets (CSS) é uma "folha de estilo" composta por “camadas” e utilizada para definir a apresentação (aparência) em páginas da internet que adotam para o seu desenvolvimento linguagens de marcação (como XML, HTML e XHTML).

### Inline: aplicadas a um elemento específico num documento.
### Internal: definidas num documento específico. Permitem aplicar o estilo apenas a esse documento.
### External: definidas num ficheiro externo e associadas a vários documentos HTML.

# CSS - Seletores

## Seletor Universal 
Os conteúdos de cada um dos elementos da marcação, ao serem renderizados em um navegador, são estilizados com regras CSS mínimas (por exemplo: cor e tipo de fonte, margens, paddings, etc.) que fazem parte de uma folha de estilos nativa do navegador e que na ordem de cascata tem a prioridade mais baixa, ou seja, qualquer declaração de estilo do autor ou usuário sobrescreve a folha de estilos nativa.
### Exemplo:
 {
  margin: 0;
  padding: 0;
  }
  
## Seletor tipo
Usado para estilizar os elementos da marcação que são de um mesmo tipo; por exemplo: elemento do tipo p (parágrafo), do tipo div, do tipo ol, do tipo strong, e assim por diante.
### Exemplo:
 { color: orange }

## Seletores de atributo
Você não está restrito aos dois atributos especiais, class e id. Você pode especificar outros atributos usando colchetes. Dentro dos colchetes você insere o nome do atributo, opcionalmente seguido por um operador correspondente e um valor.
### Exemplo:
[class~="b"] { color: orange; }

## Seletores de pseudo-classes
Uma pseudo-classe em CSS é uma palavra-chave adicionada aos seletores que especifica um estado especial do elemento a ser selecionado.
### Exemplo:
a:link {
  color: red; 
  text-decoration: none;  
}

## Seletor classe
Use o atributo class em um elemento para atribuir o elemento a uma determinada classe. O nome da classe é de sua escolha. Muitos elementos em um documento podem pertencer a mesma classe.
### Exemplo:
um { background: moccasin; }

## Seletores com ID
Use o atributo id em um elemento para atribuir um ID a esse elemento. O nome do ID é de sua escolha e ele deve ser único no documento.
### Exemplo :
#dois { background: honeydew; }
        
  
## Seletor descendente 
Um seletor descendente é uma combinação de dois ou mais seletores simples separados por um espaço em branco. Casa com elementos que sejam descendentes do primeiro elemento simples declarado no seletor. 
### Exemplo:
div.um i { color: crimson; } 
div.dois * * i { color: orangered; } 

  
## Seletor filho
O combinador > selecina nós que são filhos diretos do elemento especificado anteriormente.
### Exemplo:
.um > i { color: red; }
.dois > p > i { color: blue; }
.dois > div > p > i { color: orange; }

# Referencia CSS local (na pagina)
É colocado na seção <head> de uma determinada página. As classes e IDs podem ser usados para se referir ao código CSS, mas eles só estão ativos nessa página específica. CSS estilos incorporados desta forma são baixados cada vez que a página carrega para que ele possa aumentar a velocidade de carregamento. 

# Referencia local externa (diretorios e web)
Quaisquer alterações feitas em um arquivo CSS externo serão refletidas em seu site globalmente. 

# Frameworks
## Bootstrap
O Bootstrap é um framework desenvolvido pelo Twitter, que traz consigo características bem definidas de inicialização rápida, ou seja, possuem estilos predefinidos (prontos). Com a utilização do Bootstrap é possível a criação de sites responsivos, que são aqueles que se adaptam ao tamanho da tela que estará sendo utilizada pelo usuário.

## Pure.CSS
Pure é um CSS (Cascading Style Sheet) desenvolvido pela YAHOO. Ajuda na criação de sites mais rápidos, bonitos e responsivos. É muito experiente em termos de espaço e tem um tamanho muito pequeno, comparável a 4 KB. Este tutorial explica todos os conceitos fundamentais do Pure.

## Foundation
 Completamente personalizável, o Foundation é um framework que possui como forte característica sua responsividade, sem a necessidade de adicionar classes, facilitando assim a criação de sites, aplicativos e muito mais.
 
 
 
