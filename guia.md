# 1. INTRODUÇÃO

### O que é Markdown?
É uma sintaxe amigável para formatação de texto sem formatação.

### Por que utiliziamos ele no Github?
É usado frequentemente para formatar arquivos README (introdução do repositório).

# 2. Elementos Básicos do Markdown
### Cabeçalhos
Podemos utilizar
```
# <- maior tamanho
...
###### <- menor tamanho possível
```

### Parágrafos e quebra de linhas
Para criar parágrafos utilizamos a tag em html < p >
Já para quebrarmos linhas damos dois espaços normais, assim ocorre a quebra de linha.

### Linhas horizontais
Para fazer as linhas horizontais, existem diversas maneiras, todavia a que eu indico é três hífens

```
---
```
<p>Fica assim:</p>

---

# 3. Formatação de Texto
### Ênfases
```
**palavra** = negrito
*palavra* = itálico
~~palavra~~ = riscado
```
**Exemplo de negrito**  
*Exemplo de tálico*  
~~Exemplo de riscado~~  

### Citações e blocos de citação

Utilizando o simbolo de maior ">" fazemos uma citação
>Exemplo de citação

Agora, para fazer um bloco de citação utilizamos as três crases


```
Exemplo
```

# 4. Trabalhando com Listas
### Listas ordenas e não ordenadas

Para fazermos a lista ordenada colocamos 1. e automaticamente a lista vai se ordenando.
1. lista ordenada 1
2. lista ordenada 2

Agora para as não ordenas usamos:
\* ou \- ou \+
```
+ lista 1
  * lista 2
    - lista 3
```

Para usarmos listas com numeração não sequencial, usamos o \ antes do .
exemplo:
```
numero 1\.
```

# 5. Links e Referências 
### Criando links simples
Para usarmos links colocamos colchetes ([]) na palavras que escolhemos como link, e depois a url entre parenteses. Exemplo:

[teste](https://www.google.com.br/?hl=pt-BR)

### Criando âncoras
Para usarmos âncoras, utilizamos o [^], exemplo:
```
[^teste]    
[^teste]: teste para âncora de rodapé
```

# 6. Imagens e Mídias
## Inserindo imagens locais e externas

Usar imagens externas:
```
![Nome a sua escolha](URL)
```
![logo-markdown](https://static-00.iconduck.com/assets.00/markdown-icon-2048x2048-2zsi74vy.png)

Para imagem interna
```
[Nome a sua escolha](local onde a imagem está em sua máquina)
```
![logo-markdown](imagem/markdown-icon.png)

### Código inline e em blocos
Para fazer isso, você deve envolver o código com crases simples (`).

`teste1`

Você pode criar um bloco de código usando três crases (```), exemplo:

```
bloco
```

### Uso de destaque para diferentes linguagens

Usamos as três crases e ao lado o nome da linguagem
```
```python
printf("teste");
```

# Elementos Avançados

### Tabelas e alinhamentos

para fazer tabelas usamos o |  
exemplo:  
```
| teste | teste |
``` 
|:---:| Este comando vai alinhar no meio
