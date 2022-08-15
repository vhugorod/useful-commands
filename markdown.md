# Lista de comandos em Markdown

Veja abaixo uma lista dos comandos em markdown e alguns exemplos de seu uso:

## Título

**Sintaxe**
```txt
# Título
## Título
### Título
#### Título
##### Título
###### Título
```

Exemplo:
# Título
## Título
### Título
#### Título
##### Título
###### Título

----------

## Negrito

Sintaxe:
```language
**Escreva algo em negrito**
```

Exemplo:

**Escreva algo em negrito**

----------

## Código não formatado
```
`Escreva seu código entre as aspas simples`
```

Exemplo:

`Escreva seu código entre as aspas`

----------

## Código formatado
Sintaxe:
```
Escreva seu código entre as aspas simples tripla seguindo nome da linguagem.

```javascript ESCREVA SEU CÓDIGO AQUI```

```
Exemplo:

```javascript
function mostrarProps(obj, nomeDoObj) {
  var resultado = "";
  for (var i in obj) {
    if (obj.hasOwnProperty(i)) {
        resultado += nomeDoObj + "." + i + " = " + obj[i] + "\n";
    }
  }
  return resultado;
}
```
----------

## Quebra de linha com traço


Sintaxe:
```language
----------
```

Exemplo:

----------

## Imagem

Sintaxe:
```language
![alt](https://link)
```

Exemplo:

![codiub](https://miro.medium.com/max/1125/1*dDNpLKu_oTLzStsDTnkJ-g.png)


----------

## Itálico
Sintaxe:
```language
*Escreva seu texto aqui*
```
Exemplo:

*Escreva seu texto aqui*

----------

## Link

Sintaxe:
```language
[text](https://link)
```
Exemplo:
[link site codiub](www.codiub.com.br)

----------

## Lista ordenada

Sintaxe:
```language
1. first
2. second
3. third
```
Exemplo:
1. first
2. second
3. third

----------

## Citação

Sintaxe:
```language
> Escreva seu texto aqui
```

Exemplo:
> Escreva seu texto aqui

----------

## Lista desordenada

Sintaxe 
```
- first
- second
- third
```

Exemplo:
- first
- second
- third
