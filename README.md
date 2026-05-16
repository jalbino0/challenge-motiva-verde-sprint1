# Motiva Verde

Aplicativo mobile proposto para o **Challenge CCR Motiva**, com foco no registro, acompanhamento e priorização de ocorrências relacionadas à vegetação em rodovias.

## Integrantes

| Integrante | RM |
|---|---|
| Fernando Caires Silva | 563415 |
| Giovanna Fernandes Pereira | 565434 |
| Guilherme Martins Rezende | 563500 |
| João Pedro de Moura Albino | 565323 |
| Kauê Silva Matheus | 561675 |
| Raphael Mischiatti de Souza | 563567 |

## Link do protótipo

[Figma - Motiva Verde](https://www.figma.com/make/1NaP87mmIRBySLItqw7qig/Motiva-Verde-App-Prototype?code-node-id=0-9&p=f&fullscreen=1)

## Link do repositório

[GitHub - challenge-motiva-verde-sprint1](https://github.com/jalbino0/challenge-motiva-verde-sprint1)

---

## 1. Contexto do projeto

A Motiva atua na gestão de infraestrutura de mobilidade, incluindo rodovias concessionadas. Dentro da operação rodoviária, uma das atividades importantes é a conservação da faixa de domínio, que envolve o controle da vegetação em acostamentos, canteiros, trevos, praças de pedágio e demais áreas próximas à via.

O problema escolhido pelo grupo está relacionado à dificuldade de registrar e acompanhar, de forma organizada, ocorrências de vegetação fora do padrão, como mato alto, obstrução de placas, risco à visibilidade ou necessidade de roçada e poda.

Em muitos casos, essas informações podem depender de inspeções manuais, comunicação direta entre equipes e registros pouco centralizados. Isso dificulta a priorização dos trechos mais críticos e reduz a velocidade da tomada de decisão.

---

## 2. Problema escolhido

A gestão de vegetação em rodovias precisa lidar com três pontos principais:

- identificação de trechos com vegetação fora do padrão;
- registro claro da localização e do tipo de ocorrência;
- priorização das intervenções de conservação.

Quando essas informações não estão organizadas, a equipe pode ter dificuldade para saber quais trechos exigem atenção imediata, quais ocorrências já foram tratadas e quais ainda estão pendentes.

---

## 3. Proposta de solução

O **Motiva Verde** é uma proposta de aplicativo mobile para apoiar operadores de campo e equipes de conservação no registro e acompanhamento de ocorrências de vegetação.

A solução permite que o usuário registre uma ocorrência informando o trecho da rodovia, o quilômetro, o tipo de problema, a criticidade e uma evidência visual. Após o registro, a ocorrência aparece no acompanhamento e pode ser consultada no histórico.

A proposta da Sprint 1 não é entregar um sistema completo, mas sim um protótipo navegável que demonstre o fluxo principal da solução.

---

## 4. Usuário principal

### Operador de Campo

O usuário principal da solução é o **Operador de Campo**, responsável por realizar inspeções nas rodovias e registrar situações que possam exigir manutenção ou atenção da equipe de conservação.

Esse usuário precisa de uma interface simples, rápida e objetiva, pois o uso do aplicativo acontece em ambiente operacional, muitas vezes durante deslocamentos ou inspeções em campo.

### Necessidades do Operador de Campo

- Registrar ocorrências com poucos passos.
- Informar o trecho ou KM da rodovia.
- Classificar o tipo de problema encontrado.
- Indicar a criticidade da ocorrência.
- Anexar uma imagem como evidência.
- Acompanhar se a ocorrência foi recebida, analisada ou concluída.

---

## 5. Outros usuários envolvidos

Além do operador de campo, a solução também considera outros perfis operacionais:

- **Supervisor de Conservação:** acompanha os registros enviados e organiza prioridades.
- **Gestor Operacional:** consulta dados consolidados para apoiar decisões de manutenção.
- **Equipe de Roçada/Poda:** executa as intervenções planejadas com base nas ocorrências priorizadas.

---

## 6. Funcionalidades previstas no protótipo

O protótipo desenvolvido no Figma contempla as principais telas do fluxo inicial da aplicação:

- login;
- dashboard;
- visualização de trechos;
- registro de ocorrência;
- confirmação do registro;
- acompanhamento de status;
- histórico de ocorrências.

---

## 7. Fluxo principal do usuário

O fluxo principal apresentado no protótipo é:

**Login → Dashboard → Trechos → Nova Ocorrência → Confirmação → Acompanhamento → Histórico**

Esse fluxo permite demonstrar a jornada básica do usuário: acessar o app, consultar a situação dos trechos, registrar uma ocorrência e acompanhar seu andamento.

---

## 8. Stack tecnológica prevista

A stack pensada para a evolução do projeto na Sprint 2 é:

| Tecnologia | Uso previsto |
|---|---|
| React Native | Desenvolvimento mobile multiplataforma |
| Expo | Ambiente de desenvolvimento e testes |
| JavaScript/TypeScript | Linguagem principal da aplicação |
| React Navigation | Navegação entre telas |
| Expo Location | Simulação ou uso de localização |
| Expo Image Picker / Camera | Registro de imagens das ocorrências |
| AsyncStorage ou Context API | Armazenamento local e mocks |
| Figma | Protótipo navegável |

---

## 9. Justificativa técnica

A escolha por **React Native com Expo** permite criar um aplicativo mobile compatível com Android e iOS, mantendo uma única base de código. Essa stack também facilita a integração futura com recursos importantes para a solução, como câmera, localização e armazenamento local.

Para a Sprint 1, o foco está no protótipo navegável e no planejamento da solução. Na Sprint 2, a mesma estrutura poderá ser usada para criar as telas funcionais com dados mockados.

---

## 10. Estrutura do repositório

```txt
challenge-motiva-verde-sprint1/
├── README.md
└── REQUISITOS.md
```

---

## 11. Próximos passos

Na Sprint 2, o projeto poderá será desenvolvido em React Native/Expo.
