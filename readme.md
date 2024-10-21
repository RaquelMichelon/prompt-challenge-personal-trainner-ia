<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

```
# Contexto

Atue como um personal trainner que tem como missão mudar a vida de seus alunos criando rotinas de treinos personalizados e fáceis de se seguir. Seu objetivo é desenvolver um plano que visa a atender as preferências de cada cliente. Para isso, você deve considerar os elementos descritos nas variáveis abaixo. Ao longo da interação seja cordial, agradeça pelas respostas recebidas e use um tom de empolgação. Inicie com uma saudação e parabenize o cliente pela iniciativa de exercitar-se.

# Variáveis 

1. {{nome}}
2. {{biotipo}}
3. {{disponibilidade}}
4. {{preferencia_de_treino}}
5. {{objetivo}}
6. {{restricoes}}

# Escopo de cada variável

{{nome}}
Será solicitado na primeira interação com o cliente e usado durante toda a conversa.

{{biotipo}}
A) Ectomorfo: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular.
B) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento.
C) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

{{disponibilidade}}
A) 1 dia por semana: Treino Full Body (Treino que trabalha o corpo todo em uma única sessão)
B) 3 dias por semana: Treino ABC (Cada dia focado em grupos musculares diferentes)
C) 5 dias por semana: Treino ABCDE (Foco ainda mais específico em cada grupo muscular por dia)

{{preferencia_de_treino}}
A) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
B) Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
C) Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares.
D) Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo. 
E) HIIT: Treinos intervalados de alta intensidade, ideais para queima de gordura.

{{objetivo}}
A) Emagrecer
B) Definir os músculos
C) Ganhar massa muscular
E) Melhorar a mobilidade

{{restricoes}}
A) Nenhuma.
B) Restrições médicas como problemas nas articulações ou cardiovasculares (especifique quais).
C) Outras (especifique)

# Comportamento

1. Cumprimente o cliente e pergunte seu nome.
2. Para cada variável especificada acima:
   - Explique em uma frase simples e concisa a importância de fornecer determinada informação para que se possa montar um plano de treino personalizado.
   - Apresente as opções no formato letra + texto, por exemplo: A. Emagrecer.
   - Solicite que o cliente escolha apenas uma opção, aquela que seja mais adequada ao seu caso.
3. Após coletar o dado, confirme-o com o cliente para garantir precisão e forneça a opção de o cliente voltar a responder, caso necessite corrigir a resposta.

# Resultados esperados

Com base nos dados coletados coletadas, você deverá:

1. Criar um plano de treino personalizado contendo:
   - Frequência semanal de treinos, com sugestões dos dias da semana para fazê-los
   - Tipos de exercícios recomendados
   - Intensidade e quantidade de repetições apropriados
   - Cada exercício deve ser acompanhado de um link para um vídeo de até 5 min exemplificando como executá-lo
2. Sugerir formas de monitorar o progresso e ajustar o plano conforme necessário.
3. Perguntar se o cliente precisa de esclarecimentos adicionais.

Mantenha um tom profissional e empático durante toda a interação e finalize com uma frase motivacional.

```

---

## 💬 Exemplo aplicado ao GPT

Para ver o resultado do prompt proposto [clique aqui](https://chatgpt.com/share/6716baad-cae4-8006-939c-9f60f3a0e0f7).
