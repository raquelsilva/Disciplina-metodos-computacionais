#Brief description of the topics to be studied along the course MCOM

####First steps in Python

> The contents of this topic are at the directory: `first_steps_Python`

It presents a basic introduction of Python programming. 
I would like to stress that the main goal in 
this part of the course IS NEITHER TEACHING PROGRAMMING NOR PYTHON.
Rather, it gives the required background to follow the classes.

The content of this topic is mostly based on the lessons
[Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
of the [Software Carpentry](http://software-carpentry.org/).

* Software Carpentry Lessons (`SC\analyzing_patient_data.ipynb`)

* Simple moving average filter (`SMA\sma.ipynb`)

    - [x] Exercise: implement the SMA filter

####Basic matrix operations

It presents some basic concepts about vectors and matrices.
Besides that, it is also presented some algorithms for computing:

* scalar-vector product (`scalar-vector.ipynb`)

* dot product (`dot.ipynb`)

* other products of vectors (`other.ipynb`)

    - [x] Exercise 1: Hadamard product
    - [x] Exercise 2: Outer product
    - [x] Exercise 3: Outer product versus `numpy.meshgrid` function

* matrix-vector product (`matrix-vector.ipynb`)

    - [ ] Exercise 1: matrix-vector product functions
    - [ ] Exercise 2: comparison with the moving average code developed in a previous class
    - [ ] Exercise 3: computation of first derivative by using the central finite difference

* matrix-matrix product (`matrix-matrix.ipynb`)

####Numerical solution of linear systems

Present some classical algorithms for solving linear systems.

- [ ] Introduction (`intro-sistemas-lineares.ipynb`)

- [ ] Especial linear systems (`sistemas-especiais.ipynb`)

* Eliminação de Gauss - Introdução (`elim-gauss.ipynb`)

* Eliminação de Gauss com pivotamento parcial - parte 1 (`elim-gauss-piv-parcial1.ipynb`)

* Eliminação de Gauss com pivotamento parcial - parte 2 (`elim-gauss-piv-parcial2.ipynb`)

* Decomposição LU

* Decomposição de Cholesky

* *Decomposição em valores singulares (SVD)*

####Solução numérica de sistemas não-lineares

* Método de Newton

* Método steepest descent (descida mais íngreme)

* Método de Gauss-Newton

* Método de Levenberg-Marquardt

* *Método dos gradientes conjugados*

####Interpolação

* Ajuste polinomial

* *Série de Fourier*

* Splines

* *Mínima curvatura*

####Solução numérica de equações diferenciais

* Diferenças finitas

* *Elementos finitos*

####*Integração numérica*

* *Fórmulas de Newton-Cotes*

* *Quadratura Gaussiana*

####*Transformadas*

* *Transformada de Fourier*

* *Transformada de Hilbert*

**OBSERVAÇÃO**: Os tópicos destacados em *itálico* poderão ser abordados ou não,
dependendo do andamento do curso.

#### Template para a elaboração dos códigos

Todos os códigos a serem desenvolvidos durante a disciplina deverão
seguir a formatação do Jupyter Notebook `template-codigo.ipynb`, que está
dentro do diretório `Conteudo`.