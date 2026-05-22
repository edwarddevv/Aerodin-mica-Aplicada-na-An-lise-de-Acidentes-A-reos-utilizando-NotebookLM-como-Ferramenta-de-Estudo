# Aerodinâmica Aplicada a Acidentes Aéreos

## Sobre o Projeto

Este projeto foi desenvolvido como atividade prática para o Bootcamp
Afya - Automação de Dados com IA utilizando o NotebookLM como ferramenta de apoio ao
aprendizado.
------------------------------------------------------------------------
O objetivo principal foi estudar conceitos de aerodinâmica aplicados a acidentes aéreos reais,
utilizando Inteligência Artificial para compreender eventos,fenômenos físicos. Com o intuito de
adquirir uma melhor compreensão sobre segurança aeronáutica.
---

# Objetivos

- Compreender conceitos fundamentais de aerodinâmica;
- Relacionar conceitos aerodinâmicos e acidentes aéreos reais;
- Utilizar o NotebookLM como ferramenta de aprendizagem;
- Desenvolver pensamento crítico sobre investigação aeronáutica;
- Praticar engenharia de prompts utilizando NotebookLM.
---

# Conceitos Estudados

- Sustentação (Lift)
- Arrasto (Drag)
- Ângulo de ataque (AOA)
- Stall (Estol)
- Fluxo de ar
- Formação de gelo
- Estol assimétrico
- Parafuso Chato (Flat Spin)
- Autorrotação
- Perda de controle em voo
---

# Acidentes Estudados
## Air France 447
Principais tópicos analisados:
- congelamento das sondas Pitot;
- perda de velocidade indicada;
- desconexão do piloto automático;
- estol em alta altitude;
- fatores humanos.
---
## Voepass 2283
Principais tópicos analisados:
- formação de gelo nas superfícies aerodinâmicas;
- degradação de sustentação;
- estol assimétrico;
- autorrotação;
- flat spin.
---

# Fontes Utilizadas

1. https://bea.aero
2. https://www.gov.br/cenipa
3. https://skybrary.aero
4. https://www.faa.gov
5. https://www.ntsb.gov
---

# Engenharia de Prompts
## Prompt 1
> Qual foi a dinâmica do acidente ocorrido com a aeronave da Air France no voo AF447?
Demonstre, com vocabulário de fácil compreensão, suas principais causas e efeitos.

### Resultado Obtido
Resumidamente, a IA explicou: A dinâmica do acidente do voo AF447 da Air France envolveu uma
combinação de falhas técnicas e erros humanos durante uma tempestade sobre o Oceano Atlântico.
O problema começou quando cristais de gelo congelaram as sondas Pitot da aeronave, responsáveis 
por medir a velocidade do avião. Isso causou informações incorretas no painel e levou ao
desligamento involuntário do piloto automático. Surpreendido pela situação, o copiloto
iniciou uma manobra excessiva no manche para trás,aumentando o ângulo de ataque da aeronave até
ultrapassar o limite crítico de sustentação. Com isso, a aeronave entrou em stall (estol),
perdendo sustentação aerodinâmica e iniciando uma queda até atingir o oceano.

Tendo como causas do acidente:
- congelamento das sondas Pitot;
- perda de velocidade indicada;
- desconexão do piloto automático;
- aumento excessivo do ângulo de ataque;
- entrada em stall;
- perda de sustentação da aeronave.

### Aprendizados
Consegui compreender como falhas de instrumentação, erros de interpretação e desorientação
espacial podem levar uma aeronave ao stall em alta altitude.
---

## Prompt 2

> Explique detalhadamente o porque a elevação repentina do ângulo de ataque levou a aeronave a
situação descrita como stall.

### Resultado Obtido

Resumidamente, a IA explicou que o ângulo de ataque (AOA) representa o ângulo entre a asa da
aeronave e o vento relativo. Durante condições normais, o ar passa sobre as
asas, gerando sustentação. Porém, quando o ângulo de ataque aumenta de forma excessiva, o fluxo
de ar deixa de acompanhar a superfície da asa e se separa dela, formando uma corrente de ar
turbulenta. Esse fenômeno gera:
- perda de sustentação;
- aumento de arrasto;
- turbulência sobre as asas;
- entrada em stall (estol).
A IA também destacou que o stall não ocorre apenas por baixa velocidade, mas principalmente
pelo excesso de ângulo de ataque.

### Aprendizados
Foi possível entender que o stall ocorre principalmente devido ao excesso de ângulo de ataque,
e não apenas pela baixa velocidade.
---

## Prompt 3
> Levando em consideração os relatórios finais dos órgãos de investigações aeronáuticas
disponibilizados em sua base de dados, compare, de forma detalhada, o acidente da Air France
com o da Voepass, explique suas diferenças técnicas e causas.

### Resultado Obtido

A IA comparou de forma técnica os dois acidentes, destacando diferenças importantes na origem
dos problemas. No acidente do AF447:
- ocorreu congelamento das sondas Pitot;
- houve perda de informações confiáveis de velocidade;
- o piloto automático foi desconectado;
- a tripulação elevou excessivamente o ângulo de ataque;
- a aeronave entrou em stall em alta altitude.
Já no acidente da Voepass:
- ocorreu acúmulo de gelo diretamente nas asas e superfícies aerodinâmicas;
- houve degradação física da sustentação;
- o piloto automático aumentou automaticamente o ângulo de ataque;
- a aeronave sofreu estol assimétrico;
- ocorreu autorrotação e flat spin.
A IA também destacou diferenças:
- na automação das aeronaves;
- nos fatores humanos;
- no comportamento aerodinâmico;
- na dinâmica da queda.

### Aprendizados
Aprendi que acidentes aparentemente semelhantes podem possuir causas completamente diferentes.
---

## Prompt 4

> Qual o motivo do parafuso chato (flat spin) ocorrido na aeronave envolvida no acidente da
Voepass ser uma condição extremamente difícil de ser recuperada?

### Resultado Obtido

A IA explicou que o flat spin (parafuso chato) é uma condição extremamente perigosa porque a
aeronave perde praticamente toda a eficiência aerodinâmica necessária para recuperar o controle.
Durante o flat spin:
- as superfícies de controle entram em estol;
- o fluxo de ar deixa de atuar corretamente sobre o leme e profundores;
- a aeronave perde estabilidade nos três eixos de rotação;
- ocorre autorrotação contínua.
A IA também explicou que o ATR 72-500 perdeu velocidade horizontal suficiente para que o leme
pudesse gerar força aerodinâmica capaz de interromper a rotação.
Além disso, a distribuição de massa da aeronave ajudou a manter o avião em uma atitude quase
plana, dificultando ainda mais a recuperação.

### Aprendizados
Aprendi que o flat spin é uma das situações mais críticas da aviação porque a aeronave perde
não apenas sustentação, mas também toda sua capacidade de controle de voo.
---

# Dificuldades Encontradas
- Alguns conceitos aerodinâmicos eram muito técnicos;
- Certos prompts geravam respostas genéricas inicialmente;
- Foi necessário melhorar a forma de perguntas para obter respostas melhores;
---

# Glossário
## Stall (Estol)
Perda de sustentação causada pelo excesso de ângulo de ataque.
## Ângulo de Ataque
Ângulo entre a asa da aeronave e o vento relativo.
## Lift
Força responsável por sustentar a aeronave no ar.
## Drag
Resistência aerodinâmica ao avanço da aeronave.
## Flat Spin
Parafuso chato caracterizado por rotação estabilizada e baixa capacidade de recuperação.
## Autorrotação
Fenômeno em que diferenças aerodinâmicas entre as asas mantêm a rotação contínua da aeronave.
---

# Conclusão
O projeto demonstrou como conceitos de aerodinâmica podem ser aplicados para facilitar a
compreensão de acidentes aéreos reais. Além disso, fui capaz de perceber como ferramentas de
Inteligência Artificial podem auxiliar no aprendizado de temas considerados complexos de forma
eficaz.
---

# Tecnologias e Ferramentas Utilizadas
- NotebookLM
- Ferramentas de busca online
- Inteligência Artificial Generativa
