<!-- Título -->
# Estrutura `while()` — Teoria em C

***Conteúdo da Aula:***

O `while()` é o equivalente ao `enquanto-faça` do *Scratch*:

* Nós o utilizamos quando não sabemos ao certo quantas vezes um determinado trecho de código deverá ser repetido.

A sintaxe do `while()` é demonstrada abaixo:

```c
while (<condição de repetição>) {
    // Código a ser repetido.
}
```

Lembra-se do exemplo que vimos anteriormente, onde nós deveríamos aproveitar a vida enquanto tivermos dinheiro e saúde?

Pois então, podemos escrever este algoritmo com o **C** também!

O código poderia ficar similar ao abaixo:

```c
int saude = 100;
int dinheiro = 100;
while (saude > 0 && dinheiro > 0) {
    printf("Estou aproveitando a vida! :D");
    saude -= 10;
    dinheiro -= 10;
}
```

Perceba, mais uma vez o código acima:

* Nós estamos aproveitando a vida enquanto tivermos saúde e dinheiro.
* Mas nós sabemos o momento exato onde não teremos saúde ou dinheiro?
* Por sabermos que o **“aproveitar a vida”** deverá ser repetido, mas por nós não sabermos ao certo até quando teremos saúde ou dinheiro, nós devemos implementar este algoritmo com o `while()`.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-est-whi-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
