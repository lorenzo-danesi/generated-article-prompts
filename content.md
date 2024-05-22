### O que são diretivas

Diretivas no Angular são como superpoderes que você dá aos elementos do HTML. Elas ajudam a mudar o comportamento ou a aparência desses elementos. Pense nelas como etiquetas mágicas que dizem ao Angular o que fazer com uma parte específica da sua página.

### O que são diretivas estruturais

Diretivas estruturais são como arquitetos. Elas podem adicionar, remover ou alterar partes inteiras da sua página. É como construir e derrubar paredes em uma casa para criar novos cômodos.

Aqui vão dois exemplos:

```html
<div *ngIf="mostrarMensagem">Olá, Mundo!</div>
```
Este código mostra a mensagem "Olá, Mundo!" só se a variável `mostrarMensagem` for verdadeira.

```html
<ul>
  <li *ngFor="let item of itens">{{ item }}</li>
</ul>
```
Este outro exemplo cria uma lista com itens. Ele repete o `<li>` para cada item na lista `itens`.

#### Exemplos de diretivas estruturais

- `*ngIf`: Mostra ou esconde um elemento com base em uma condi��o booleana.
- `*ngFor`: Repete um elemento para cada item em uma lista.
- `*ngSwitch`: Exibe um dos vários elementos com base em uma express�o.
- `*ngSwitchCase`: Define um caso dentro de uma estrutura `ngSwitch`.
- `*ngSwitchDefault`: Define o caso padrão para uma estrutura `ngSwitch`.

### O que são diretivas atributivas

Diretivas atributivas são como pintores. Elas mudam a aparência ou comportamento de um elemento existente, sem adicionar ou remover nada. Elas podem alterar cores, tamanhos, e outras características visuais.

Veja esses exemplos:

```html
<p [ngClass]="{'destaque': isDestaque}">Este texto pode ser destacado!</p>
```
Aqui, o texto ganha uma classe CSS chamada `destaque` se a variável `isDestaque` for verdadeira.

```html
<button [disabled]="estaDesativado">Clique aqui</button>
```
Esse botão só fica desativado se a variável `estaDesativado` for verdadeira.

#### Exemplos de diretivas atributivas

- `ngClass`: Adiciona ou remove classes CSS de um elemento com base em uma expressão.
- `ngStyle`: Adiciona ou remove estilos inline de um elemento com base em uma expressão.
- `ngModel`: Cria uma ligação bidirecional de dados entre o valor do input e uma variável no componente.
- `ngForm`: Associa um formulário HTML ao modelo de dados do Angular, permitindo validação e gerenciamento do formulário.
- `ngModelGroup`: Agrupa controles de formulário, permitindo validação e gerenciamento de subgrupos de controles dentro de um formulário.

### Conclusão

Gostou de aprender sobre diretivas do Angular? Esse conteúdo foi gerado por inteligência artificial, mas foi revisado por alguém 100% Humano. Se quiser se conectar comigo siga-me no [LinkedIn](https://www.linkedin.com/in/lorenzo-dalla-corte-danesi/)

Ilustrações de capa: gerada pela Lexica.art
Conteúdo gerado por: ChatGPT e revisões humanas

#programação #angular #frontend