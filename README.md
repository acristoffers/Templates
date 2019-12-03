# XeLaTeX-Templates
Temaplates para o curso de Eng. Mecatrônica do CEFET-MG.

Os templates devem ser compilados utilizando XeLaTex (e não pdflatex) e biber
(não bibtex). No Overleaf basta trocar o compilador para XeLaTeX. O template de
slides é um pouco lento no Overleaf (motivo desconhecido, o template é bem
simples).

O diferencial desses templates é já vir com vários pacotes pré-carregados e
configurados, não precisar de comandos especiais para acentos (como \'{a}) e ter
copiar/colar no PDF final que não quebra todos os acentos (graças ao XeLaTeX).
Eles também possuem alguns comandos especiais para definir autores,
orientadores, coorientadores, etc; tornando a criação de um projeto muito mais
simples.

Recomendo não colocar seu texto diretamente no arquivo document.tex (arquivo
principal dos 3 exemplos), mas sim criar um arquivo por capítulo (ou seção) e
usar o comando \include pra inserir esses documentos no document.tex, como é
feito nos exemplos. Isso melhora a organização do projeto.
