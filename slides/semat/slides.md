% title: Computação Científica com Python
% subtitle: Introdução e ferramentas
% author: Lincoln de Macêdo
% author: 
% thankyou: Obrigado a todos!
% thankyou_details: 
% contact: <span>www</span> <a href="http://www.google.edu/">website</a>
% contact: <span>github</span> <a href="http://github.com">username</a>
% favicon: 

---
title: Sobre mim
build_lists: true

- Aluno de Licenciatura Plena em Computação
- Membro da comunidade Python de Pernambuco - PUG-PE
- Pesquiso sobre IA desde o 2º período
- Estudo especialmente sobre inteligência de enxame de partículas

---
title: Quem são vocês?

- Curso
- O quanto sabem programar
- Motivações de estar aqui
- Interesses futuros acerca dos assuntos abordados

---
title: Dia 1
subtitle: Breves noções sobre Computação Científica
class: segue dark nobackground

---
title: Computação como ciência 
subtitle: O que fazemos nesta área
build_lists: true

- Foco no método
- Conceitos de outras ciências
- Forte embasamento estatístico e matemático
- Se espalha em diversas categorias:
    + Inteligência Artificial
    + Reconhecimento de padrões
    + Ciência dos dados
    + Computação Quântica
    + ...

---
title: Computação como ciência 
subtitle: Desafios
build_lists: true

- Problemas com solução exponencial X solução polinomial
- Expressar de forma legível procedimentos complexos
- Custo computacional
    + Muitos calculos: exige muito do processador
    + Muitos dados: exige muito de memória
- Precisamos de números aleatórios de qualidade

---
title: Exemplos
subtitle: 
class: segue dark nobackground
 

---
title: MDC

<pre class="prettyprint" data-lang="Python">
def mdc(a, b):
    if b == 0:
        return a
    else:
        return mdc(b, a % b)
</pre>

---
title: Análise Combinatória

Fatorial:

<pre class="prettyprint" data-lang="Python">
def fatorial(n):
    if n == 1:
        return n
    else:
        return n * fatorial(n-1)
    
</pre>

Permutação:

<pre class="prettyprint" data-lang="Python">
def permutacao(a, b):
    return fatorial(a) / fatorial(a - b)
</pre>
 
---
title: busca

???

---
title: Dia 2
subtitle: Ferramentas
class: segue dark nobackground

---
title: Manipulação de dados

- Numpy
- Pandas


---
title: Bibliotecas científicas

- SciKit Learning (sklearn)
- SciPy

---
title: Visualização de dados

- Matplotlib
- Lightning Viz
- PyQtGraph

---
title: Dia 3
subtitle: Aplicações
class: segue dark nobackground
