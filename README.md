# Passos para instalar e utilizar Git, Github, Atom e GitKraken :+1:

## Nesta demonstração você verá:

- Utilizar Atom para uma ampla gama de aplicações;
- Entender ideia de controle de versões;
- Trabalhar com Git e Github através do GitKraken;
- ~~Otras cositas más, que ainda vou ver.~~

~~Depois vou complementando o material disponível.~~
## Em primeiro lugar:

- [GitHub](https://github.com "Faça sua conta")

Se ainda não possui uma conta no Github, clique no link e crie a sua, lembrando de registrar também seu e-mail da UFRGS para ter direito ao Student Pack (serviços **PRO** gratuitos).

- [Student pack](https://education.github.com/pack "Student Pack")

Utilizando seu login do Github, no site acima, clique em *Get the Pack*. Faça o *login* com sua conta do Github para obter serviços **PRO** gratuitamente.

## Programas a serem instalados (nesta ordem, preferencialmente):

### [Python](https://www.python.org/ "Python")

Se pretende trabalhar com Python, instale a versão do Python de sua preferência. Mesmo se não for trabalhar com Python, faça este procedimento.

#### Instalando bibliotecas do python

- procurar *python3.dll* na busca do windows. (~~foi o jeito mais fácil para encontrar o lugar correto que eu achei~~)
- abrir pasta local do arquivo anterior;
- clicar com o botão direito do mouse segurando o Shift e clicar em "Abrir janela de comando aqui" ou algo similar;
- no terminal que abrir, escrever "pip install *nomedabiblioteca*"

#### Principais Bibliotecas Python:

- _Básicas_:
  - NumPy (https://numpy.org/)
  - SciPy (https://www.scipy.org/)
  - Pandas (https://pandas.pydata.org/)
- _Gráficas_:
  - MatplotLib (https://matplotlib.org/)
  - Plotly (https://plot.ly/python/)
  - Bokeh (https://bokeh.pydata.org/en/latest/)
  - VPython - para gráficos animados em 3D (https://vpython.org/)
- _Outras_:
  - NetworkX (https://networkx.github.io/)
  - Theano - processamento paralelo e otimização (http://deeplearning.net/software/theano/)
  - PyTables - manipulação de dados em tabelas (https://www.pytables.org/)
  - Numba - permite que o Python execute processos em velocidade de código em linguagem de máquina nativa (baixo nível) (https://numba.pydata.org/)
  - Jypiter - permite utilizar Python diretamente de seu browser (https://jupyter.org/)
  - Tensor Flow - ampla biblioteca para trabalhar com inteligência artificial (https://www.tensorflow.org/?hl=pt-br)
- ~~(tem várias outras)~~

**Recomento instalar todas estas para bom funcionamento do Atom na maioria das aplicações pretendidas.**

### [Git](https://git-scm.com/ "Git")

Instale o Git, disponível no link acima. Siga as instruções [desta página](http://robertovormittag.net/ebooks/git-and-github/git-for-windows-installation-screenshots/ "Instalando Git").

### [Atom IDE](https://atom.io/ "Atom")

Este é um editor de texto avançado que serve para praticamente tudo, desde escrita do código até compilação.

Uma vez instalado o Atom, instale também os _packages_ básicos para ter uma boa experiência de uso (instalação dos _packages_ é realizada nas configurações do Atom).

Packages básicos:
- Hydrogen
- atom-live-server
- autocomplete-python
- linter
- linter-ui-default
- linter-flake8
- python-autopep8

Se for trabalhar com LaTeX no Atom:

- atom-latex
- latex
- language-latex

### [GitKraken](https://www.gitkraken.com/)

GitKraken é basicamente um *manager* das tuas versões de código, linkado aos teus repositórios no GitHub ou outro.

Faça login no GitKraken com sua conta do GitHub. Assim você terá também a versão **PRO** do GitKraken, concedida por anteriormente ter feito a autenticação da sua conta no Student Pack com o e-mail institucional.

Para associar o GitKraken à sua conta do GitHub e acessar seus repositórios remotamente não basta ter feito o login com sua conta do GitHub. Você deve dizer ao GitHub que você é efetivamente _você_ autenticando sua conta. Para tanto, vá em *Preferences*, *Authentication*, *GitHub.com* e gere uma *SSH Key*. Sua conta estará automaticamente associada ao seu GitHub.

## *Para quem pensa em usar o* LaTeX *na escrita da dissertação/tese, instale também*:

- [MiKTeX](https://miktex.org/ "MiKTeX")
  - Após instalar o MiKTeX, execute o console e instale o package _latexmk_.
- [Strawberry Perl](http://strawberryperl.com/ "Strawberry Perl")

## Outros links úteis:

- [Git workflow](https://www.youtube.com/watch?time_continue=5&v=3a2x1iJFJWc "GitKraken workflow")
- [Git for noobs](https://www.youtube.com/watch?v=_ALeswWzpBo "Git explained")
- [Gitkraken introduction](https://www.youtube.com/watch?v=ZKkMwTeAij4 "intro")
- [Gitflow](https://www.youtube.com/watch?v=eTOgjQ9o4vQ "Gitkraken Gitflow") (avançado)
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/ "Commit naming") (importante)
