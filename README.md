# Projeto-1-FE

## Conceitos aprendidos em aula usados no site:

Semântica -> Usado em quase todos os elementos presentes no texto.
Divisoes -> Utilizado divisões apropriadas para cada assunto, não apenas div.
Elementos estruturais -> ul - presente no nav, br e strong - presente na experiência acadêmica, h1, h2, h3 - presente em todos as sections, no footer e no header. hr - presente no header,
Elementos genéricos -> span - presente na experiência profissional, ID - presente em cada section para funcionar com o href do nav, class - presente em quase todos os elementos para modificá-los no css, a - utilizado no footer e no nav com caminhos diferentes, img - várias imagens pelo site, assim como um slideshow de 4 imagens que se alteram dentro de 4 segundos no hobby.
Mídia incorporada -> utilizado no Projeto, mostrando uma gameplay dos 2 projetos.
Elementos formulário -> utilizado input checkbox na parte de experiência profissional para ser como se fosse um click, tirando o hidden quando desse checked na checkbox. 

CSS -> irei citar algumas propriedades CSS utilizadas, font-size, font-weight, color, background-image, background-color, margin, padding, text-align, width, height, display, position, top, right, bottom, left, overflow, border-radius, box-shadow, text-decoration.

Seletores -> pseudo-classes - utilizado no pess.css e em outros, pseudo-elementos - utilizado na experiência acadêmica, como ::after e ::before, float - utilizado também na experiência acadêmica

Posicionamento -> utilizado position: em quase todos os files .css, z-index - usado no cabeçalho (z-index: 999;)para sempre estar na frente, assim como position: fixed para ficar em cima e sem nada atrás dele, a ideia do z-index seria mais para caso o header viesse junto com o scroll da pagina, com o position: sticky, porém eu descartei esta ideia e o z-index perdeu meio que a funcionalidade, porém para previnir de bugs, eu preferi deixar para manter o cabeçalho em evidência.

Responsividade -> Todas os arquivos .css estão com @medias queries de tamanho, para se ajustar tanto para celular, quanto pra monitores de maior e menor tamanho.

Transições -> usadas no pess.css, prof.css e proj.css, para fazer a transição, como exemplo temos o slideshow do pess.css que a cada tempo o keyframe muda a imagem exibida, fazendo um transition de uma cena para outra, transform - utilizado tanto no pess.css quanto no prof.css.

Importação de fontes externas -> exportado fonte externa para ser usada no h1, presente no style.css, esse que exporto todos os outros arquivos .css para evitar confusões futuras.

Propriedades personalizadas -> criado propriedades no style.css, sendo elas, font-weight, font-family e background-color, utilizadas no header.