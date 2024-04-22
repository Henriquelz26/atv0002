# Guia Básico de Marcação Markdown 

Este guia oferece um passo a passo detalhado sobre como utilizar a marcação Markdown para
formatação de texto em documentos. Iniciando desde os conceitos básicos, como títulos e
parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada tópico
é acompanhado por uma descrição simples e exemplos práticos em Markdown, permitindo que os
usuários aprendam e apliquem rapidamente a marcação Markdown em seus próprios documentos.

##Títulos
São usados para criar diferente niveis de titulos em uum documento markdown.

Exemplo:
# Titulo 1
## Titulo 2
### Titulo 3

## Parágrafos
Simplesmente escreva seu texto como parágrafos normais. Não é necessário nenhum tipo de marcação adicional.

Exemplos: Aqui eu tenho um parágrafo


## Listas
permitem criar listas ordenadas ou não ordenadas 

Ex.:
Lista não ordenada:

* Item 1
* Item 2
* Item 3

## Links
Criam link para outras paginas da web.

Exemplo:

[[URL](https://www.correiobraziliense.com.br/brasil/2021/07/4940046-youtuber-raulzito-e-preso-acusado-de-estupro-de-vulneravel.html)] para criar um link

## Imagens
Insere imagens em um documento Markdown.

![Imagem](https://github.com/Henriquelz26/atv0002/assets/135260061/0adfabcf-c2f9-4d58-a894-c836e8f893d2)


## Ênfase
Permitem enfatizar texto, com itálico, negrito, tachado, subscrito, subscrito e sobrescrito.

Exemplo:

*Texto em itálico* ou _Texto em itálico_ para itálico.

**texto em negrito** ou __texto em negrito__ para negrito.

~~Texto em tachado~~

Aqui é um texto <sub> subscrito </sub>

Aqui é um texto <sup> sobrescrito </sup>


## Citações em Bloco
São usadas para detacar uma situação ou bloco de texto.

Exemplo: 

>Isso é uma citação em bloco


## Linhas Horizontais
São usadas para criar uma linha horizontal para separar seções do documento.

Exemplo:

---


## Código
Permitem inserir blocos de código ou destacar código dentro do texto.

Exemplo:

Use crases (\`) para inserir código `inline`.



```
idade = 18
print(f"a idade é{idade}")
```

## Tabelas
Criam tabelas organizadas em colunas e linhas.

Exemplo:

|Cabeçalho 1 | Cabeçalho 2|
| ---------- | ---------- |
|   Dado 1   |   Dado 2   |
|   Dado 3   |   Dado 4   |


## Lista de Tarefas
Criam listas de tarefas que podem ser marcadas como concluídas ou pendentes

Exemplo:

- [x] Tarefa concluída
- [ ] Tarefa pendente

## Referências e Notas de Rodapé
Permitem adicionar notas de rodapé para fornecer mais informações sobre o conteúdo do documento.

Exemplo:
Aqui é um exemplo de marcação em rodapé[^1].

A aula é com o Ricardo[^2].

[^1]: Rodapé: conteúdo inferior do documento.
[^2]: Ricardo: Professor da turma de Git.
 

## Alertas
são usados para destacar informações importantes, como notas, avisos ou mensagens.
Exemplo:

› *Note*
› Esta é uma Nota

› [!NOTE]
› Destaca informações que os usuários devem levar em consideração, mesmo durante a leitura superficial.

› [!IMPORTANT]
› Informações cruciais necessárias para o sucesso dos usuários.[

› [!IMARNING].
› conteúdo crítico que exige atenção imediata do usuário devido a riscos potenciais.




