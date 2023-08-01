 <div align="center">
 <img width="250" alt="Markdown logo" src="image.png"/>
 </div>


 <div align=center>

 <font size='70' color=#F11A7B> Markdown Sintaxe Básica </font>
 
 </div>



<br>

 <h1 > O que é Markdown ? </h1>

É uma linguagem de marcação leve e fácil de usar, criada por John Gruber em 2004 com colaborações de Aaron Swartz. Markdown converte seu texto em HTML válido. É projetado para ser fácil de ler e escrever, mais usado para formatar arquivos README entre outros. Sua sintaxe é intuitiva e compreensível.

<div align="center">
 <img width="150" alt="Markdown logo" src="/img/good.gif"/>
 </div>


<br>
<br>


## 📌 Títulos

Para criar uma estrutura clara e organizada no seu documento. Use de um a seis sinais de cerquilha `#` para indicar diferentes níveis de títulos.

```
# Título de nível 1
## Título de nível 2
### Título de nível 3
#### Título de nível 4
##### Título de nível 5
###### Título de nível 6
```

_**ou**_

```
Título de nível 1
====

Título de nível 2
------
```

 👇

![Titulos](img/Screenshot_4.png 'exemplos de Cabeçalho')

<br>

## 📌Ênfase
 Ao combinando negrito e itálico, dê preferência ao uso de três asteriscos, para evitar problemas de compatibilidade com aplicativos Markdown  
Ex:

#### ***Italico&negrito***:

```
 ***Italico&negrito***
```

#### *Italico*:

```
 *Italico*
```

#### **NEGRITO**:

```
 **NEGRITO**
```

#### ~~TACHADO~~

Para riscar a palavra em um linha horizontal
basta colar dois simbolos de til `~~`.

**assim:** 👇
```
Segundo especialistas em ~~numismática~~, existem moedas de Real com defeitos de fabricação que fazem com que sejam muito valiosas.
```

###### Segundo especialistas em ~~numismática~~, existem moedas de Real com ~~defeito~~s de fabricação que fazem com que sejam muito valiosas.

<br>

## 📌Links

Existe duas formas de inserir link em Markdown, através de um link direto ou usando um texto-âncora.

**Link direto**: envolva o endereço da web em chaves `<>` , o endereço ficará visível e será clicável pelo usuário.

🔗 <https://duckduckgo.com>

```
	<https://duckduckgo.com>
```

**Texto-âncora:** `[]()`

🔗 [Duck Duck Go](duckduckgo.com 'mecanismo de buscas com mais privacidade')

```
  [Duck Duck Go](https://duckduckgo.com "mecanismo de buscas com mais privacidade")
```

💡 **Dica:** Para inserir uma frase informativa quando o usuário passar o mouse sobre o link. Coloque entre **aspas** `" "` após o **URL**.

<br>

## 📌Listas

Crie listas com um hífen `-` , `+` ou `*` seguido de um espaço

### Lista não ordenada

```
- Javascript
+ Typescript
* React
```

- Javascript
- Typescript
- React

### Lista Ordenadas

coloque um número na frente de cada linha seguindo de um ponto `.`

1. Ruby
2. Node.js
3. PHP

### Listas aninhadas

1. Fullstack
   - Front End
     - Back End

```
1. Fullstack
   - Front End
     - Back End
```

### Listas de tarefas

```
- [x] #739
- [ ] klll
- [ ] Add delight
```
<br>

## 📌Imagens

Você pode exibir uma imagem adicionando `!` e colocando o texto entre `[ ]`, o texto alternativo é um texto curto equivalente às informações da imagem. Em seguida, coloque o link da imagem entre parênteses `()`.
Sintaxe de imagem se assemelha à sintaxe para links, permitindo dois estilos.

```
![descrição](/img.png)
```

_**ou**_

```
![descrição](URL da imagem "texto opocional")
```

👇

![if](img/if.png 'Qual a opção?')

###### passe o mause sobre a imagem

<br>

## Emoji 👋😎

Há duas maneiras de adicionar emoji a arquivos _Markdown_: **copiar** e **cola**r o emoji em seu texto formatado em Markdown ou digitar códigos de acesso de emoji .

[Emojipedia](https://emojipedia.org/ 'emojipedia') 🔗

<br>

## Tabelas 

Crie tabelas organizadas com barras verticais `|` e hífens `-` para delimitar as células e dois pontos `:` como abaixo.

| Dev       |   Local    | Quant |
| --------- | :--------: | ----: |
| Front End |   Remoto   |  3500 |
| Back End  |  Híbrido   |   200 |
| FullStack | Presencial |    40 |

💡 ***Dica: Para alinha o texto  usando*** `:`  👇

```
A esquerda   |:----|
Centralizado |:---:|
A direita    |----:|
```

<br>

## 📌Citações

Para criar um blockquote, adicione um `>` na frente do paragrafo.

```
> Não gosto de domingo, é o dia mais _modorrento_ da semana.
```

A saída renderizada fica assim👇

> Não gosto de domingo, é o dia mais _modorrento_ da semana.

<br>

## 📌Réguas horizontais

Insira uma linha horizontal para separar seções no seu documento usando três hífens `---` ou asteriscos `***` ou `___` .

**Dessa forma:**

💡**Dica**: Em uma unica linha.

```
---
```

A saida sera assim 👇

---


<br>

### Teste seu Markdown:

**Editor de codigo**   
[VS Code](https://code.visualstudio.com/)

**Editores online**

- [Dillinger](https://dillinger.io/)
- [Markdown Preview](https://markdownlivepreview.com/)
- [Meditor](https://pandao.github.io/editor.md/en.html)





