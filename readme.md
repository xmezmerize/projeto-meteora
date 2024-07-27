# Projeto Meteora #

# WireFrame do projeto no Figma: https://www.figma.com/file/TT8Uq6LmVELALMKs4G4HE2/Meteora---Projeto-Bootstrap-5?node-id=2386%3A2430&t=k7CWzKKFpothsH69-0

*data-bs-ride="carousel"* atributo de dados que faz o carrossel mover de forma autônoma.

*favicon*
<link rel="shortcut icon" href="#caminho" type="image/x-icon">

*grid & breakpoints*
Largura(eixo x - horizontal):
<div class="w-25 p-3">Width 25%</div>
<div class="w-50 p-3">Width 50%</div>
<div class="w-75 p-3">Width 75%</div>
<div class="w-100 p-3">Width 100%</div>
<div class="w-auto p-3">Width auto</div>

Altura(eixo y - vertical):
<div style="height: 100px; background-color: rgba(255,0,0,0.1);">
  <div class="h-25 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 25%</div>
  <div class="h-50 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 50%</div>
  <div class="h-75 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 75%</div>
  <div class="h-100 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 100%</div>
  <div class="h-auto d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height auto</div>
</div>

Breakpoints:
``Extra small (xs):``
Tamanho: Menos de 576px
Exemplo de classe: d-block d-sm-none

``Small (sm):``
Tamanho: 576px ou mais
Exemplo de classe: d-none d-sm-block d-md-none

``Medium (md):``
Tamanho: 768px ou mais
Exemplo de classe: d-none d-md-block d-lg-none

``Large (lg):``
Tamanho: 992px ou mais
Exemplo de classe: d-none d-lg-block d-xl-none

``Extra large (xl):``
Tamanho: 1200px ou mais
Exemplo de classe: d-none d-xl-block d-xxl-none

``Extra extra large (xxl):``
Tamanho: 1400px ou mais
Exemplo de classe: d-none d-xxl-block

Grid:
>O sistema de grid é baseado em linhas (row) e colunas (col), e permite dividir a largura horizontal da tela em 12 colunas.

row:
>Ela representa uma linha horizontal na qual as colunas são organizadas.
<div class="row">
  <div class="col-sm-6">Coluna 1</div>
  <div class="col-sm-6">Coluna 2</div>
</div>
row: Define uma nova linha no layout.
col-sm-6: Cada coluna (col) dentro da row possui uma classe que indica quantas colunas ela ocupará. No exemplo acima, cada coluna (col-sm-6) ocupará 6 colunas em telas pequenas (sm) ou maiores. Isso totaliza 12 colunas, que é a largura máxima disponível em uma row.

col:
>As colunas (col) dentro de uma row são usadas para dividir horizontalmente o espaço disponível. Cada coluna é projetada para ocupar um número específico de colunas na grade de 12 colunas do Bootstrap, dependendo do tamanho da tela.
<div class="row">
  <div class="col-md-4">Coluna 1</div>
  <div class="col-md-8">Coluna 2</div>
</div>
col-md-4 e col-md-8: Na primeira coluna, col-md-4, ela ocupará 4 colunas (1/3 do espaço total) em telas médias (md) e maiores. Na segunda coluna, col-md-8, ela ocupará 8 colunas (2/3 do espaço total) em telas médias (md) e maiores.

>Total de 12 colunas: Cada row pode conter até 12 colunas. Você pode combinar diferentes classes de col para criar layouts complexos que se ajustam dinamicamente ao tamanho da tela.

*tipos de display*
d-inline

>Define um elemento como um elemento de nível inline. Isso significa que ele não quebrará a linha após ele mesmo.
Exemplo: <span class="d-inline">Texto inline</span>
d-inline-block

>Similar ao d-inline, mas permite definir largura e altura, além de aceitar margens e preenchimentos.
Exemplo: <div class="d-inline-block">Elemento inline-block</div>
d-block

>Define um elemento como um elemento de nível de bloco, ocupando toda a largura disponível e iniciando uma nova linha antes e depois dele.
Exemplo: <div class="d-block">Elemento de bloco</div>
d-flex

>Define um contêiner como um contêiner flexível. Os itens dentro dele podem ser organizados em uma linha ou coluna e ter seus tamanhos ajustados automaticamente.
Exemplo: <div class="d-flex">Contêiner flexível</div>
d-grid

>Define um contêiner como um contêiner de grade, permitindo organizar os itens filhos em uma grade usando linhas e colunas.
Exemplo: <div class="d-grid">Contêiner de grade</div>
d-table

>Define um elemento como um elemento de tabela. Isso permite que o layout e o comportamento do elemento se assemelhem ao de uma tabela HTML.
Exemplo: <div class="d-table">Elemento de tabela</div>
d-table-row

>Define um elemento como uma linha de uma tabela.
Exemplo: <div class="d-table-row">Linha de tabela</div>
d-table-cell

>Define um elemento como uma célula de uma tabela.
Exemplo: <div class="d-table-cell">Célula de tabela</div>
d-none

>Esconde um elemento, removendo-o do fluxo de layout da página.
Exemplo: <div class="d-none">Elemento oculto</div>
d-xxl-none (e outras variações responsivas como d-lg-none, d-md-block, etc.)

>Controla a visibilidade do elemento dependendo do tamanho da tela usando breakpoints responsivos (xxl, lg, md, sm, xs).
Exemplo: <div class="d-lg-none">Elemento visível apenas em telas menores que large</div>

*cores*
<h2 class="text-center mt-5 mb-3">Temas para Botões no Bootstrap 5</h2>
<div class="d-flex justify-content-center gap-2">
  <button type="button" class="btn btn-default border-dark-subtle">Padrão</button>
  <button type="button" class="btn btn-primary">Primário</button> azul
  <button type="button" class="btn btn-secondary">Botão Secundário</button> cinza
  <button type="button" class="btn btn-success">Sucesso</button> verde
  <button type="button" class="btn btn-info">Informação</button> azul claro
  <button type="button" class="btn btn-warning">Alerta</button> amarelo
  <button type="button" class="btn btn-danger">Erro</button> vermelho
  <button type="button" class="btn btn-dark">Botão Escuro</button> escuro
  <button type="button" class="btn btn-link">Link</button> estilizado como link
</div>