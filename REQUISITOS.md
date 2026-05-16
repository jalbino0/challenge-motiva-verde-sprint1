# Requisitos do Projeto — Motiva Verde

## 1. Visão geral

O **Motiva Verde** é uma proposta de aplicativo mobile para auxiliar no registro e acompanhamento de ocorrências de vegetação em rodovias administradas pela Motiva.

A solução busca melhorar a organização das informações coletadas em campo e apoiar a priorização de trechos que necessitam de roçada, poda ou atenção da equipe de conservação.

---

## 2. Escopo da Sprint 1

Nesta Sprint, o projeto contempla:

- definição do problema;
- definição da proposta de solução;
- levantamento de requisitos;
- identificação do usuário principal;
- criação do protótipo navegável no Figma;
- documentação no GitHub.

A Sprint 1 não contempla o desenvolvimento do aplicativo funcional. A implementação será prevista para a Sprint 2.

---

## 3. Usuário principal

### Operador de Campo

Função responsável por identificar e registrar ocorrências durante inspeções em rodovias.

O aplicativo deve atender principalmente esse usuário, oferecendo uma experiência simples e rápida para registro das informações essenciais.

---

## 4. Atores do sistema

| Ator | Responsabilidade |
|---|---|
| Operador de Campo | Registra ocorrências de vegetação na rodovia |
| Supervisor de Conservação | Analisa ocorrências e define prioridades |
| Gestor Operacional | Consulta informações para tomada de decisão |
| Equipe de Roçada/Poda | Executa a intervenção no trecho indicado |

---

## 5. Requisitos funcionais

| Código | Requisito | Descrição |
|---|---|---|
| RF01 | Acessar o aplicativo | O usuário deve conseguir acessar o app por uma tela inicial de login. |
| RF02 | Visualizar dashboard | O sistema deve apresentar um resumo das ocorrências e dos trechos monitorados. |
| RF03 | Visualizar trechos | O sistema deve exibir trechos da rodovia com indicação de situação ou criticidade. |
| RF04 | Registrar ocorrência | O operador deve conseguir cadastrar uma nova ocorrência de vegetação. |
| RF05 | Informar localização | O cadastro da ocorrência deve permitir informar KM, trecho ou localização aproximada. |
| RF06 | Selecionar tipo de ocorrência | O usuário deve selecionar o tipo de problema encontrado. |
| RF07 | Informar criticidade | O sistema deve permitir indicar se a ocorrência é baixa, média, alta ou crítica. |
| RF08 | Anexar evidência visual | O registro deve prever o uso de foto como evidência da ocorrência. |
| RF09 | Confirmar envio | Após o cadastro, o sistema deve exibir uma confirmação de registro. |
| RF10 | Acompanhar status | O usuário deve conseguir acompanhar o andamento da ocorrência. |
| RF11 | Consultar histórico | O sistema deve exibir registros anteriores de ocorrências. |
| RF12 | Retornar ao dashboard | O usuário deve conseguir voltar para a tela principal a partir das telas do fluxo. |

---

## 6. Requisitos não funcionais

| Código | Requisito | Descrição |
|---|---|---|
| RNF01 | Usabilidade | A interface deve ser simples e adequada para uso em campo. |
| RNF02 | Clareza visual | As informações devem ser apresentadas de forma objetiva. |
| RNF03 | Consistência | O protótipo deve manter padrão visual entre telas, botões e cards. |
| RNF04 | Acessibilidade | O app deve usar textos legíveis, bom contraste e elementos fáceis de identificar. |
| RNF05 | Responsividade | A interface deve ser pensada para dispositivos móveis. |
| RNF06 | Organização | O fluxo deve ser fácil de entender sem explicações externas. |
| RNF07 | Evolução futura | A solução deve permitir evolução para uso de câmera, GPS e mocks na Sprint 2. |
| RNF08 | Manutenibilidade | A futura implementação deve manter separação entre telas, componentes e dados. |
| RNF09 | Compatibilidade | O app deve ser planejado para desenvolvimento em React Native/Expo. |
| RNF10 | Segurança | Futuramente, o acesso deve considerar autenticação e controle de usuários. |

---

## 7. Regras de negócio iniciais

| Código | Regra |
|---|---|
| RN01 | Toda ocorrência deve possuir uma localização ou trecho identificado. |
| RN02 | Ocorrências que afetam visibilidade ou segurança devem ser tratadas como prioridade alta ou crítica. |
| RN03 | Toda nova ocorrência deve iniciar com status de registro recebido ou aguardando análise. |
| RN04 | Ocorrências registradas devem aparecer no acompanhamento e no histórico. |
| RN05 | O histórico deve permitir consultar ocorrências concluídas, pendentes ou em andamento. |

---

## 8. Tipos de ocorrência previstos

O protótipo considera os seguintes tipos de ocorrência:

- vegetação alta;
- obstrução de placa;
- risco à visibilidade;
- necessidade de roçada;
- necessidade de poda;
- árvore ou galho em situação de risco.

---

## 9. Status previstos

As ocorrências podem passar pelos seguintes status:

1. Registrada;
2. Em análise;
3. Programada;
4. Em execução;
5. Concluída.

---

## 10. Fluxo do protótipo

```txt
Login
  ↓
Dashboard
  ↓
Trechos da rodovia
  ↓
Nova ocorrência
  ↓
Confirmação
  ↓
Acompanhamento
  ↓
Histórico
```

---

## 11. Entrada, processamento e saída

### Entrada

Dados informados pelo operador:

- trecho ou KM;
- tipo de ocorrência;
- criticidade;
- descrição;
- imagem da ocorrência.

### Processamento

O sistema organiza o registro, atribui status inicial e exibe a ocorrência no acompanhamento.

### Saída

O usuário visualiza:

- confirmação do registro;
- status da ocorrência;
- histórico;
- indicação de trechos com atenção ou criticidade.

---

## 12. Restrições técnicas

- O protótipo deve ser navegável no Figma.
- A Sprint 1 não exige app funcional.
- O desenvolvimento futuro deve ser compatível com React Native/Expo.
- A Sprint 2 deverá utilizar dados mockados.
- Funcionalidades como câmera, GPS e banco de dados real podem ser simuladas inicialmente.

---

## 13. Links do projeto

### Protótipo Figma

https://www.figma.com/make/1NaP87mmIRBySLItqw7qig/Motiva-Verde-App-Prototype?code-node-id=0-9&p=f&fullscreen=1

### Repositório GitHub

https://github.com/jalbino0/challenge-motiva-verde-sprint1
