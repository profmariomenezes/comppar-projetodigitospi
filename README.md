# Projeto Dígitos do Pi

Desenvolver um programa para o cálculo do maior número de dígitos do número Pi

Nosso objetivo nesse projeto será calcular o valor da Pi com o máximo de dígitos.
Pi é um número irracional; veja os links abaixo para entender o conceito de números irracionais:

- https://www.mathsisfun.com/irrational-numbers.html
- https://www.cuemath.com/numbers/irrational-numbers/
- https://en.wikipedia.org/wiki/Irrational_number

Etapas da solução:

1 - Apresente uma solução serial que funcione corretamente; você deverá conferir o seu resultado com alguns resultados certificados, com o maior número de casas decimais que conseguir para ter confiança em sua implementação.

2 - Apresente uma solução paralela com PThreads que funcione corretamente; você deverá também apresentar a certificação do seu resultado.

3 - Apresente uma solução paralela com OpenMP, que funcione corretamente, certificando sua solução.

Os dígitos de Pi deverão ser calculados a partir da fórmula abaixo:

$$\pi = 4 \left( 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots + (-1)^n \frac{1}{2n + 1} + \dots \right)$$

Ou seja, é para calcular na _força bruta_.

Não existe requisito de linguagem de programação. Contudo, a solução proposta deve utilizar os mesmos conceitos apresentados no projeto e atender os mesmos requisitos, o que é facilitado na linguagem C.

Não se pode fazer nenhuma relação lógica, sendo necessário o cálculo massivo dos valores. Ou seja, não se pode igualar ao valor de Pi para se chegar a uma aproximação do resultado, nem utilizar nenhum meio de aproximações.

Este projeto poderá ser feito em grupos de até 3 alunos. As entregas serão pelo GitHub, com as seguintes datas:

* Etapa 1 - Entrega em 22/10/2023
* Etapa 2 - Entrega em 05/11/2023
* Etapa 3 - Entrega em 19/11/2023

Deverão ser entregues, em pastas separadas no repositório, com os nomes **etapa1**, **etapa2** e **etapa3**:

- código fonte de cada etapa
- arquivo com os dígitos do Pi que foram calculados, a partir do ponto decimal, em txt.
- evidências da comparação da precisão em cada etapa.
- o tempo T que levou para calcular o número Pi apresentado.
- em cada etapa, um relatório sucinto do desenvolvimento, incluindo dificuldades encontradas e soluções adotadas, e obrigatoriamente, discriminando a contribuição de cada componente do grupo para o projeto; máximo 3 páginas, em Markdown (md).

Links de interesse:

- https://www.piday.org/million/
- http://newton.ex.ac.uk/research/qsystems/collabs/pi/
- https://cloud.google.com/blog/products/compute/calculating-100-trillion-digits-of-pi-on-google-cloud

