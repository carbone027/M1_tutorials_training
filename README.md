# Tutorial Markdown Inteli

:tada::tada::tada: Oi pessoa! Se você chegou aqui é porque está interessada(o) em escrita **Markdown**, que é o formato de documento de texto que utilizamos nas documentações dos projetos dos módulos no Inteli! Markdown é meio assim... limitado, sabe? Não dá para colocar o texto na fonte Comic Sans, por exemplo, e isso pode ser triste... Mas é justamente por ser limitado que ele se torna rápido de escrever, e produz documentos organizados! Neste tutorial você vai aprender alguns fundamentos que te ensinam na prática como escrever e organizar um documento markdown, cuja extensão de arquivo é .md

Um arquivo markdown muito comum da gente observar aqui no Github é o tal do README.md (este arquivo aqui que você está lendo é um README.md!). Eles geralmente são usados com esse nome README como um padrão de arquivo que já é aberto automaticamente toda vez que abrimos um repositório Github. Por exemplo, experimente abrir esse link aqui [https://github.com/Intelihub/Template_M1](https://github.com/Intelihub/Template_M1) e repare que o arquivo README.md já está aberto como se fosse a "capa" do repositório. Percebeu? Se você não der o nome de README a esse arquivo .md, há chances dele não ser aberto automaticamente :confused:

Mas vamos lá praticar markdown e aprendermos a explicar nossa documentação e entregas em termos dele? Let's bora! :rocket::rocket::rocket:

## 1. Iniciando

Antes de mais nada, é preciso que você consiga editar esse arquivo aqui para praticar. Para isso, você pode fazer um fork deste repositório aqui para sua conta no Github (não sabe como fazer isso? Tem esse tutorial [aqui](https://www.youtube.com/watch?v=q-QTbNu8Ybc)). Daí, quando estiver pronto, já na sua cópia pronta, volte a esse arquivo aqui e repare no ícone de lápis aqui acima, à direita. Clica nele e você vai entrar no modo de edição! (**Só continue a ler o resto desse documento depois que estiver no modo de edição, tá bom?**)

Você pode chavear entre o modo *Edit*, para editar, e *Preview*, para visualizar como está ficando. E é isso o que você vai precisar ficar fazendo daqui pra frente para praticar, tá bom? Por enquanto pode continuar lendo em modo *Preview*.

## 2. Negrito, itálico, fontes monoespaçadas e imagens

Você sabe colocar negrito, itálico e outras firulas nas suas mensagens do Whatsapp? Então, quando você faz isso, você está usando **notação Markdown**, sabia? A gente vai trabalhar de forma semelhante aqui. Veja a tabelinha abaixo: na coluna *Notação Markdown* você entende como pode escrever envolvendo suas palavras com notações, e na coluna *Como fica* você vê o resultado.

Notação Markdown | Como fica
--- | ---
`**negrito**` | **negrito**
`*itálico*` ou `_itálico_` | *itálico*
`~~strikethrough~~` | ~~strikethrough~~
`` `Monospace` `` (use para inserir pequenos trechos de código) | `Monospace`
`[Um link](https://www.inteli.edu.br)` | [Um link](https://www.inteli.edu.br)
`![Uma imagem](assets/Logo-Container.png)` | ![Uma imagem](assets/Logo-Container.png)

Markdown é uma notação construída a partir de elementos HTML, mas ao invés de você usar aquelas tags que às vezes deixam a escrita um pouco burocrática, você simplesmente usa caracteres especiais que raramente aparecem no meio de um texto comum.

Experimente editar as linhas abaixo e transforme o texto conforme o que for pedido (entre em modo *Edit* para modificar e *Preview* para visualizar)

Transforme esta linha em negrito

Transforme esta linha em itálico e depois faça o strikethrough

if(code == "hard"): studyMore() #me transforme em um código com Monospace

Coloque uma imagem aqui no meu lugar (dica: se não quiser usar um link, você pode subir uma imagem de seu computador a partir do botão de Inserir Imagem na barra de ferramentas de edição desta célula)

🥇🥇🥇Desafio: coloque aqui uma outra imagem que acessa um link quando clicar sobre ela

## 3. Tabelas

`"Legal, mas como que faz aquela tabela esperta ali acima? É no markdown também?"` Sim! Se você clicar duas vezes sobre a célula da tabela ali acima, você vê como ela foi montada com Markdown. Você pode usar o caractere *pipe* `|` para separar palavras em colunas, e cada linha escrita depois deve seguir essa mesma separação. Mas para que tudo se transforme em tabela, você precisa reservar a segunda linha para repetir a expressão `---` separada por `|` conforme o total de colunas que você tem. Edite o exemplo a seguir e *aproveite para colocar emojis para seus professores* (para adicionar um emoji no Markdown, digite `:` e comece a digitar o nome em inglês do emoji. Por exemplo, digite `:bus:` e vai aparecer 🚌)

Coordenadores | Orientadores | Programação | Matemática e Física | Negócios | UX | Liderança
--- | --- | --- | --- | --- | --- | ---
Ana | Reginaldo | Cristiano | Geraldo | Egon | Julia | Filipe
Egon | Laíza | Kizzy | Henrique | Natalia | Fabiana | Claudio
Michele | Fabiana | André G. | Ricardo | Pedro | Francisco | Marcelo
Monica | Julia | Fillipe | Cristina | Lisane | Sergio | Michele
Sergio | Marcelo | Jefferson | Pizzo | Rafael J. | Guilherme | Ana 
| | Claudio | Hayashi | Diogo |  | Bruna | Monica
| | Renato | Afonso | | | | Vanessa
| | Tomaz | Nicola | | | | Laíza
| | Murilo | Goya | | | | 
| | Vanessa | Rafael W. | | | | 
| | Rafael M. | Goya | | | | 
| | Rafael G. M. | Hermano 
| | Cesar | Afonso
| | Romualdo | Hallison

## 4. Títulos e sub-títulos
Agora vamos falar dos títulos de seções, ou Headings. Use o caracter `#` em diferentes combinações para criar títulos e sub-títulos. Veja abaixo a notação, e logo em seguida o resultado dessa notação.

```markdown
# Seção 1
# Seção 2
## Sub-seção da Seção 2
### Sub-seção da sub-seção da Seção 2
# Seção 3
```

# Seção 1
# Seção 2
## Sub-seção 1 da Seção 2
### Sub-seção 1 da sub-seção 1 da Seção 2
# Seção 3

Organize seus documentos usando Headings, elas são importantes não apenas para uma organização visual e textual, mas agregam algumas funcionalidades, como as âncoras aí abaixo 🙂

## 5. Âncoras 


## 6. Blocos de código
Você também pode inserir blocos de código não funcional no meio do seu texto. Para isto, basta usar a seguinte notação de string multilinhas usando ``` (você pode colocar "javascript" na abertura do trecho para especificar a linguagem, assim o Github vai colorir funções, variáveis, valores etc.)
````
```javascript
let a = "olá"
let b = 10
print(a)
```
````
Digitar isso aqui acima na edição da célula de texto resulta assim:
```javascript
let a = "olá"
let b = 10
print(a)
```

## 7. Listas e indentações

Se você é daquelas pessoas que adoram uma lista, essa notação a seguir é pra você - antes de cada texto, use números `1, 2, 3, 4...` com ponto `.` e espaço, para transformá-los em uma lista numerada. Ou use `*` e espaço para criar uma lista não-ordenada. Ah! E se você usar `tab` antes dos itens você cria indentações e pode criar sub-listas!

```
1. abacate
2. abacaxi
3. banana
4. laranja
5. morango

* Professores módulo 1
  * Computação
    * [ ] Cristiano
    * [x] Fillipe Resina
    * [ ] André Godoi
    * [x] Kizzy
  * UX
    * [x] Bruna
    * [ ] Francisco
    * [ ] Julia
```

1. abacate 🥑
2. abacaxi 🍍
3. banana 🍌
4. laranja 🍊
5. morango 🍓

* Professores módulo 1
  * Computação
    * [ ] Cristiano
    * [x] Fillipe Resina
    * [ ] André Godoi
    * [x] Kizzy
  * UX
    * [x] Bruna
    * [ ] Francisco
    * [ ] Julia

Ah, reparou que usamos `[ ]` e `[x]` junto com os itens de lista? Isso cria checkboxes para você transformar sua lista em uma lista de tarefas (mas infelizmente ela não é interativa) 😎

## 8. LaTeX
Agora é uma dica pra deixar esse documento MUITO profissional: Você pode usar LaTeX aqui no Colab, pra deixar suas equações perfeitas! Veja os exemplos abaixo, acessando o modo *Edit* pra ver como foi feito, e aí corra atrás dos professores de Matemática para aprender mais sobre LaTeX 📐📏

$y=x^2$

$e^{i\pi} + 1 = 0$

$\frac{n!}{k!(n-k)!} = {n \choose k}$

## 9. Finalmentes

Se você fez bagunça aqui nesse README.md, gostou do que fez e quer salvar, você pode fazer um commit + push para seu repositório próprio.

Enfim, use o Markdown para uma escrita mais organizada, que ajude a quebrar a monotonia e o tédio de um texto puro. Capriche na narrativa, na linguagem, crie ritmo de leitura ao posicionar imagens, equações, listas, tabelas, usar negritos e títulos. E mais importante:
> Nunca deixe de ler pensando em como seu cliente faria a leitura. Como será a experiência dele em seu README.md?

Divirta-se!
