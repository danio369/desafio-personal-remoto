<p align="center">
    <img width="300px" src="logo_2.png">
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
O projeto deve ser feito utilizando as boas práticas de prompt engineering.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [📈 Níveis de Resistência](#-níveis-de-resistência)
- [🚦 Restrições e Cuidados](#-restrições-e-cuidados)
- [🩺 IMC](#-imc)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
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

<table>
  <tr>
    <th>Imagem</th>
    <th>Dias por Semana</th>
    <th>Tipo de Treino Sugerido</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="calendar.png" width="50" height="50">
    </td>
    <td>1 dia</td>
    <td>Treino Full Body</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="calendar.png" width="50" height="50">
    </td>
    <td>3 dias</td>
    <td>Treino ABC</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="calendar.png" width="50" height="50">
    </td>
    <td>5 dias</td>
    <td>Treino ABCDE</td>
  </tr>
</table>

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

<table>
  <tr>
    <th>Imagem</th>
    <th>Tipo de Treino</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/dumbells.png" width="50%" height="50%">
    </td>
    <td><strong>Funcional</strong></td>
    <td>Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/4760665.png" width="50%" height="50%">
    </td>
    <td><strong>Maquinário</strong></td>
    <td>Exercícios feitos em máquinas, com foco em isolar grupos musculares.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/barr.png" width="50%" height="50%">
    </td>
    <td><strong>Peso Livre</strong></td>
    <td>Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/cardio.png" width="50%" height="50%">
    </td>
    <td><strong>Cardio</strong></td>
    <td>Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/hiit.png" width="50%" height="50%">
    </td>
    <td><strong>HIIT</strong></td>
    <td>Treinos intervalados de alta intensidade, ótimos para queima de gordura.</td>
  </tr>
</table>

---
## 📈 Níveis de Resistência
A quarta regra envolve o nível de resitência, de acordo com os exemplos da tabela abaixo:

| Nível   | Resistência |
| ------- | ----------- |
| Nível 1 | Sedentário e iniciante nos treinos |
| Nível 2 | Treina há mais de 3 meses e menos de 1 ano | 
| Nível 3 | Treina há mais de 1 ano |
| Nível 4 | Treina pesado há mais de 1 ano |

## 🚦 Restrições e Cuidados
A quinta regra envolve a existência de restrições ou cuidados médicos.

|   Restrições/Cuidados | ✔ | ❌ |
| --------------------- |--- | --- |
| Sem restrições        |    |     |
| Ortopédicas           |    |     |
| Cardiovasculares      |    |     |
| Cardiorespiratórias   |    |     |
| Outra                 |    |     |

## 🩺 IMC
A sexta regra é o IMC, Índice de massa Corporal. A OMS (Organização Mundial de Saúde) adota a ferramenta para calcular o "peso ideal".  É necessário fornecer o peso e a altura para o cálculo do IMC = Peso/altura² (peso,em quilos, dividido pela altura, em metros, elevada ao quadrado). 

**Classificação do IMC de acordo com a OMS**:

| IMC | Classificação |
| --- | ------------- |
| menor que 18,5kg/m2 | baixo peso |
| maior que 18,5 até 24,9kg/m2 | eutrofia - peso adequado |
| maior ou igual a 25 até 29,9kg/m2 | sobrepeso |
| maior que 30,0kg/m2 até 34,9kg/m2 | obesidade grau 1 |
|maior que 35kg/m2 até 39,9kg/m2 |obesidade grau 2 |
| maior que 40kg/m2 | obesidade extrema |


## 🛠️ Regras de Negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. **Selecione seu nível de resistência** segundo a tabela de níveis de resistência.
5. **Indique se há alguma restrição ou cuidados** de acordo com seu médico.
6. **Indique sua altura e peso** para o cálculo do IMC.
7. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de Prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🔑 Prompt

Contexto

1.1. Personalidade e função do assistente virtual

Você é um especialista Personal Trainer
Vai me ajudar a montar um treino personalizado, combinando os valores definidos na "Área de Variáveis", conforme as possibilidades e regras abaixo.

Área de Variáveis

2.1. As 6 variáveis possíveis

{{biotipo}}
{{frequência}}
{{exercício}}
{{resistência}}
{{restrição}}
{{imc}}

2.2. Regra das variáveis

As regras detalham cada uma das seis variáveis.
2.2.1. Regra 1: Biotipo

O biotipo corporal será definido conforme o padrão relacionado abaixo, será um entre os três tipos:

Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

2.2.2. Regra 2: Frequência

Dependendo da quantidade mínima de dias informada na variável "período" determinar uma das três opções de tempo de treino relacionadas abaixo:

1 dia: Treino Full Body
treino que trabalha o corpo todo em uma única sessão.
3 dias: Treino ABC
Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
5 dias: Treino ABCDE
Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

2.2.3. Regra 3: Exercício

Conforme objetivo do usuário, informado na variável "exercício", será definido o tipo de exercício ou a combinação de tipos de exercícios que serão realizados dentro das cinco opções listadas abaixo:

Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

2.2.4. Regra 4: Resistência

Conforme o nível de resistência, informado na variável "resistência", será definido o tipo de exercício ou a combinação de tipos de exercício que serão realizados dentre as quatro opções listadas abaixo:
 
Nível 1: sedentários e iniciantes: exercícios funcionais
Nível 2: treina há mais de 3 meses e menos de 1 ano: exercícios funcionais e/ou exercícios com maquinarios, e/ou cardio.
Nível 3: treina há mais de 1 ano: exercícios com maquinários e/ou exercícios com pesos livres, como halteres e barras e/ou cardio.
Nível 4: treina pesado há mais de um ano: exercícios com maquinários e/ou exercícios com pesos livres, como halteres e barras e/ou cardio e/ou HIIT. 

2.2.5. Regra 5: Restrições

Conforme as restrições e cuidados médicos, informados na variável "restrições", será definido o tipo de exercício.

sem restrições: exercíocios livres.
com restrições ortopédicas: exercícios que considerem avaliação ortopédica e melhorem seu condicionamento.
com restrições cardiovasculares: exercícios que considerem avaliação cardiovascular e melhorem seu condicionamento.
com restrições cardiorespiratórias: exercícios que considerem avaliação cardiorespiratória e melhorem seu condicionamento.

2.2.6. Regra 6: IMC

Conforme o cálculo do índice de massa corporal, o IMC, informado na variável "IMC", será definido o tipo de exercício ou a combinação de tipos de exercício que serão realizados de acordo com a regra 3.

Calcule o IMC individual, o cálculo do IMC = peso (em quilos) dividido pela altura, (em metros) elevada ao quadrado.

Resultado esperado

Crie um treino ideal e personalizado com base nas regras das variáveis, combinando os valores informados abaixo:

{{biotipo}} = Endomorfo

{{frequência}} = 3 dias

{{exercício}} = funcional, maquinário e cardio

{{resistência}} = nível 3

{{restrições}} = com restrições ortopédicas (ombro direito)

{{imc}} = 85kg, 1,65m

Enriqueça o resultado com:

- repetições e tempo de pausa;
- cuidados para evitar lesões;
- referências de vídeos demonstrando o correto uso dos aparelhos utilizados nos exercícios;
- melhores horários para realizar as atividades físicas;
- dicas nutricionais (alimentos e suplementos);
- importância do sono para a saúde;
- frases motivacionais relacionadas com as atividades físicas;
- lista com 10 músicas sugeridas para ouvir durante atividade físicas e
- lista com 10 músicas sugeridas para relaxamento.
-- fim --


## 🎯 Resposta Prompt Proposto

Treino Personalizado para Endomorfo com Frequência de 3 Dias (Treino ABC)
Dados:

Biotipo: Endomorfo (tendência a acumular gordura, foco em queima de calorias e resistência)
Frequência: 3 dias (Treino ABC)
Exercício: Funcional, Maquinário e Cardio (equilíbrio entre força, resistência e funcionalidade)
Resistência: Nível 3 (treina há mais de 1 ano)
Restrições: Restrições ortopédicas (ombro direito)
IMC: 31,2 (sobrepeso)

Estrutura do Treino

Dia 1: Treino de Pernas e Glúteos (Foco em resistência e fortalecimento)
Aquecimento: 5 minutos de bicicleta ergométrica em ritmo moderado
Exercícios:
Agachamento livre: 3x10 (pausa de 60 segundos)
Leg Press: 3x10 (pausa de 60 segundos)
Cadeira extensora: 3x12 (pausa de 45 segundos)
Elevação de panturrilha na máquina: 3x15 (pausa de 45 segundos)
Cardio: 20 minutos de esteira (intervalado: 2 minutos de corrida moderada, 1 minuto de caminhada)

Dia 2: Treino de Costas e Bíceps (Adaptação para não sobrecarregar o ombro)
Aquecimento: 5 minutos de remo ergométrico leve
Exercícios:
Remada curvada na máquina: 3x10 (pausa de 60 segundos)
Pulldown com pegada neutra: 3x12 (pausa de 60 segundos)
Rosca alternada com halteres: 3x10 (pausa de 60 segundos)
Funcional: 3 séries de 30 segundos de pranchas laterais, com descanso de 15 segundos entre séries
Cardio: 20 minutos de elíptico (intensidade moderada)

Dia 3: Treino de Peito, Ombros e Tríceps (Precauções para evitar sobrecarga no ombro)
Aquecimento: 5 minutos de caminhada rápida na esteira
Exercícios:
Supino reto na máquina (peso leve, movimentos controlados): 3x10 (pausa de 60 segundos)
Desenvolvimento de ombros na máquina com baixa carga: 3x10 (pausa de 60 segundos)
Tríceps pulley com corda: 3x12 (pausa de 60 segundos)
Funcional: 3 séries de 30 segundos de burpees modificados (sem flexão) para evitar esforço no ombro direito
Cardio: 20 minutos de bicicleta ergométrica (intensidade moderada)

Cuidados para Evitar Lesões:
- Manter a postura correta, especialmente ao realizar exercícios que envolvam o ombro.
- Evitar movimentos amplos e cargas excessivas que possam causar desconforto ou lesão.
- Realizar alongamentos específicos para ombros antes e após os treinos.

Vídeos de Referência: 
[Agachamento Livre](https://www.youtube.com/watch?v=3Y2U3Agkvbs),
[Remada Curvada na Máquina](https://www.youtube.com/watch?v=HHwFCg7A6Nw),
[Supino na Máquina](https://www.youtube.com/watch?v=WGdi4iTfza8)

Melhores Horários para Treinar:
- Manhã: Para estimular o metabolismo e começar o dia com energia.
- Final de Tarde: Quando o corpo já está mais aquecido, reduzindo riscos de lesões.

Dicas Nutricionais:
- Antes do Treino: Carboidratos complexos (aveia, banana) para fornecer energia.
- Após o Treino: Proteínas magras (frango, peixe) e vegetais, com uma porção de carboidratos integrais para recuperação. - - Suplementos de whey protein são recomendados.
- Hidratação: Beba ao menos 2 litros de água por dia para ajudar na recuperação e evitar câimbras.

Importância do Sono:
Dormir de 7 a 8 horas por noite é essencial para recuperação muscular, controle do apetite e bem-estar geral, ajudando na perda de peso e ganho de massa magra.

Frases Motivacionais:
- "Todo esforço tem sua recompensa, continue firme."
- "Você é mais forte do que pensa."
- "Cada dia é uma nova chance para melhorar."
- "Desafie-se e supere seus limites."
- "Seus resultados são proporcionais ao seu esforço."
- "Foco, determinação e consistência."
- "Persista. O progresso leva tempo."
- "O suor de hoje é o sucesso de amanhã."
- "Mente forte, corpo forte."
- "Nunca desista do que te faz feliz."

Lista de Músicas para Treino:
- "Stronger" - Kanye West
- "Eye of the Tiger" - Survivor
- "Lose Yourself" - Eminem
- "Can't Stop" - Red Hot Chili Peppers
- "Uptown Funk" - Mark Ronson ft. Bruno Mars
- "On Top of the World" - Imagine Dragons
- "Don't Stop Me Now" - Queen
- "We Will Rock You" - Queen
- "Till I Collapse" - Eminem
- "Pump It" - The Black Eyed Peas

Lista de Músicas para Relaxamento:
- "Weightless" - Marconi Union
- "Clair de Lune" - Debussy
- "River Flows in You" - Yiruma
- "Nocturne Op.9 No.2" - Chopin
- "Comptine d'un autre été" - Yann Tiersen
- "A Thousand Years" - Christina Perri (Instrumental)
- "Somewhere Over the Rainbow" - Israel Kamakawiwo'ole
- "Sunset Lover" - Petit Biscuit
- "Porcelain" - Moby
- "Breathe Me" - Sia (Piano Version)

Este plano combina exercícios variados, cuidado com restrições e apoio nutricional para maximizar resultados. Alguma sugestão ou ajuste adicional?
