<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->


<!-- .slide: class="slide-title" data-background-color="#262626" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h1 id="talk-title">
  Apresentação do Plano de Aula
</h1>

## Introdução à Sísmica (Teoria)

<p id="talk-authors">
  <a>Yago M Castro</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
05 de Novembro de 2024
<span style="margin: 0 20px"></span>
Atividade 10 | Preparação Pedagógica

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Sinta-se à vontade para tirar capturas de tela/compartilhar/reutilizar esta apresentação
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
  <a href="https://www.compgeolab.org"><img src="assets/compgeolab-banner-light.svg" alt="Computer-Oriented Geoscience Lab"></a>
  <a href="https://www.iag.usp.br/"><img src="assets/iag.png" alt="Instituto de Astronomia, Geofísica e Ciências Atmosféricas"></a>
  <a href="https://www.usp.br/"><img src="assets/usp.png" alt="Universidade de São Paulo"></a>
</div>
</div>

</div>
</div>

===============================================================================

# Objetivos da Aula

- Compreender os conceitos fundamentais de sísmica e a **propagação de ondas sísmicas em diferentes meios**.
- Classificar as ondas sísmicas em ondas **P, S e de superfície**, identificando suas principais características e comportamentos.
- Relacionar a propagação de ondas sísmicas com **aplicações práticas na exploração geofísica**, como a análise de estruturas da subsuperfície e a detecção de recursos naturais.
- Preparar os alunos para as próximas aulas sobre **aquisição e processamento de dados sísmicos**, conectando teoria à prática.

===============================================================================

# Contextualização no plano semestral

## Programa da Disciplina

- Apresentada na **semana 11**
- Primeira aula sobre **sísmica**
- Marca a transição do estudo de **métodos potenciais** (gravimetria e magnetometria) para os **métodos sísmicos**

===============================================================================


# Contextualização no plano semestral

## Base Prévia 
- **Propriedades físicas** das rochas
- **Estrutura interna** da Terra
- Fundamentos da **aquisição e processamento de dados geofísicos** aplicados a gravimetria e magnetometria

===============================================================================

# Contextualização no plano semestral
## Continuidade 
- **Aquisição** de dados sísmicos
- Aulas sobre **processamento de dados**
- **Integração** com outros métodos geofísicos

===============================================================================

# Etapas da Aula e Recursos Utilizados

1. **Abertura (10 minutos)**
    - **Discussão Guiada**: Qual é a importância da sísmica na geofísica moderna? (7 minutos)
    - **Apresentação em vídeo**: [3-component Seismograms—Capturing the motion of an earthquake. (Educational)](https://www.youtube.com/watch?v=Za_22xo7ZQQ) (3 minutos)
2. **Fundamentos Teóricos (20 minutos)**
    - **Tipos de Ondas Sísmicas**:
        - **Ondas P (primárias)**: compressão e propagação rápida. $V_p = \sqrt{\frac{K + \frac{4}{3} \mu}{\rho}}$
        - **Ondas S (secundárias)**: cisalhamento e propagação mais lenta. $V_s = \sqrt{\frac{\mu}{\rho}}$
        - **Ondas de Superfície**: ondas Love e Rayleigh.

===============================================================================

# Etapas da Aula e Recursos Utilizados

3. **Apresentação (10 minutos)**
    - Como as ondas sísmicas podem ser usadas para detectar diferentes camadas da Terra.
    - [Tremelique](https://github.com/leouieda/tremelique)
4. **Exercícios em sala (10 minutos)**
    - Cálculos de tempos de chegada de ondas em diferentes meios usando exemplos simplificados.

===============================================================================

# Etapas da Aula e Recursos Utilizados

5. **Exercícios para casa (slide da aula e Moodle)**
    - Exercícios relacionados aos conteúdos abordados em sala de aula
    - **Desafios**: 
        - Utilizar [Tremelique](https://github.com/leouieda/tremelique) para representar um sistema com propriedades específicas 
        - Representar um "terremoto" utilizando [Tremelique](https://github.com/leouieda/tremelique) 

===============================================================================

# Propagação de ondas P e S


<iframe  width="860" height="615" src="https://www.youtube.com/embed/2rYjlVPU9U4?si=8fZzRzOA7suyE9tH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<iframe width="860" height="615" src="https://www.youtube.com/embed/en4HptC0mQ4?si=OdREj9k6w64bi0Rx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

===============================================================================

# Propagação de ondas Love e Rayleigh

<iframe width="860" height="615"  src="https://www.youtube.com/embed/t7wJu0Kts7w?si=0pa12uo0d42ZVmqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<iframe width="860" height="615"  src="https://www.youtube.com/embed/6yXgfYHAS7c?si=lXhPp5DKIyJTUFVp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

===============================================================================

# Tremelique

<div class="row">
<div class="col-small small">

```python
import tremelique as tr
import numpy as np

shape = (300, 400)
spacing = 5
extent = [0, shape[1]*spacing, shape[0]*spacing, 0]
velocity = np.zeros(shape, dtype='float32') + 1500  # m/s
density = np.zeros(shape, dtype='float32') + 1000  # kg/m³

pwave = tr.Acoustic(velocity, density, spacing=spacing)
pwave.add_point_source((0, shape[1]//2), tr.RickerWavelet(1, 60))
pwave.run(800)
pwave.animate(every=10, embed=True, dpi=50, cutoff=0.5)
```
</div>
<div class="col-large small">

<video  controls>
  <source src="assets/simulation1.mp4" type="video/mp4">

</video>

</div>


===============================================================================


# Tremelique

<div class="row">
<div class="col-small">

```python
import tremelique as tr
import numpy as np

shape = (300, 400)
spacing = 5
extent = [0, shape[1]*spacing, shape[0]*spacing, 0]
velocity = np.zeros(shape, dtype='float32') + 1500  # m/s
density = np.zeros(shape, dtype='float32') + 1000  # kg/m³

pwave = tr.Acoustic(velocity, density, spacing=spacing)
pwave.add_point_source((0, shape[1]//2), tr.RickerWavelet(1, 60))
pwave.add_point_source((0, 50), tr.RickerWavelet(1, 60))
pwave.add_point_source((0, 350), tr.RickerWavelet(1, 60))
pwave.run(800)
pwave.animate(every=10, embed=True, dpi=50, cutoff=0.5)
```
</div>
<div class="col-large">

<video  controls>
  <source src="assets/simulation2.mp4" type="video/mp4">

</video>

</div>


===============================================================================


# Tremelique

<div class="row">
<div class="col-small small">

```python
import tremelique as tr
import numpy as np

shape = (300, 400)
spacing = 5
extent = [0, shape[1]*spacing, shape[0]*spacing, 0]
velocity = np.zeros(shape, dtype='float32') + 1500  # m/s
density = np.zeros(shape, dtype='float32') + 1000  # kg/m³
velocity[50:] = 3000
density[50:] = 2000
velocity[70:] = 3500
density[70:] = 4500

pwave = tr.Acoustic(velocity, density, spacing=spacing)
pwave.add_point_source((0, shape[1]//2), tr.RickerWavelet(1, 20))
pwave.add_point_source((0, 50), tr.RickerWavelet(1, 20))
pwave.add_point_source((0, 350), tr.RickerWavelet(1, 20))
pwave.run(1000)
pwave.animate(every=10, embed=True, dpi=50, cutoff=0.5)
```
</div>
<div class="col-large">

<video  controls>
  <source src="assets/simulation3.mp4" type="video/mp4">

</video>

</div>


===============================================================================

# Tremelique

<div class="row">
<div class="col-small">

```python
import tremelique as tr
import numpy as np

shape = (300, 400)
spacing = 5
extent = [0, shape[1]*spacing, shape[0]*spacing, 0]
velocity = np.zeros(shape, dtype='float32') + 1500  # m/s
density = np.zeros(shape, dtype='float32') + 1000  # kg/m³

pwave = tr.Acoustic(velocity, density, spacing=spacing)
pwave.add_point_source((100, 200), tr.RickerWavelet(1, 60))
pwave.run(300)
pwave.animate(every=10, embed=True, dpi=50, cutoff=0.5)
```
</div>
<div class="col-large">

<video  controls>
  <source src="assets/simulation4.mp4" type="video/mp4">

</video>

</div>


===============================================================================

# Referências Pedagógicas

- **Teoria da Aprendizagem Significativa**: Aplicação da teoria de David Ausubel para conectar novos conceitos de ondas sísmicas aos conhecimentos prévios sobre física de ondas.
- **Aprendizagem Ativa**: Uso de demonstrações práticas para facilitar a compreensão, apoiado nas ideias de John Dewey.


===============================================================================

<!-- .slide: data-background-color="#262626" data-background-size="contain" -->

<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contato:
<a href="yagomcastro@usp.br">yagomcastro@usp.br</a>

<i class="fab fa-github"></i>
<br>
Código-fonte para esta apresentação:
<br>
[github.com/YagoMCastro/preparacao-pedagogica-seminario2-msc-2024/](https://github.com/YagoMCastro/preparacao-pedagogica-seminario2-msc-2024/)
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
<br>
Tremelique:
<br>
[https://github.com/leouieda/tremelique](https://github.com/leouieda/tremelique)

<br>

Salvo indicação em contrário,
o conteúdo desta apresentação está
licenciado sob a
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>