# 🌱 EcoAir

**Monitoramento Inteligente da Poluição Industrial.**

O EcoAir é um projeto de baixo custo que utiliza sensores e uma plataforma web para monitorar gases em ambientes industriais, emitir alertas e disponibilizar informações sobre as emissões.

---

## 📌 Informações Gerais

- **Nome do Projeto:** EcoAir
- **Equipe:** Arthur Farias, Maurício Moreira, Miguel Veríssimo, Nicole Aparecida, Rúbia Cristina e Ryan Christopher.
- **Curso:** Técnico em Informática
- **Instituição:** FUNEC Riacho
- **Evento:** XIII Mostra de Tecnologia
- **Ano:** 2026
- **Orientador:** Matheus Matos Oliveira
- **Coorientadora:** Adriely Werneck
- **Local:** Contagem – MG

---

## 🎯 Objetivo do Projeto

Desenvolver um protótipo de baixo custo para monitorar gases poluentes em ambientes industriais e disponibilizar os dados coletados em uma plataforma web, contribuindo para a transparência das informações ambientais.

### Objetivos específicos

- Detectar gases utilizando o sensor MQ-135 e o microcontrolador ESP32.
- Emitir alertas visuais por meio de LEDs e sonoros por meio de um buzzer.
- Desenvolver um site para armazenar e apresentar os dados coletados.
- Auxiliar no acompanhamento das emissões industriais.

---

## 👥 Público-Alvo

- Indústrias e empresas do setor industrial.
- Órgãos de fiscalização ambiental.
- Profissionais da área ambiental.
- População interessada em acompanhar informações sobre a poluição industrial.

---

## 🧩 Problema a Ser Resolvido

A poluição atmosférica de origem industrial pode causar doenças respiratórias, intensificar o efeito estufa e prejudicar a fauna e a flora.

Além disso, a dificuldade de acompanhar continuamente as emissões industriais e a falta de acesso a informações transparentes prejudicam o monitoramento ambiental.

---

## 💡 Solução Proposta

O EcoAir propõe um sistema composto por sensores eletrônicos e uma plataforma web.

O sensor MQ-135 realiza a leitura do ar, enquanto o ESP32 processa os sinais recebidos e controla os alertas visuais e sonoros.

Os dados coletados são enviados para uma plataforma web, onde poderão ser armazenados e apresentados, permitindo o acompanhamento das medições.

---

## ⚙️ Funcionalidades do Sistema

- [x] Leitura do ar utilizando o sensor MQ-135.
- [x] Processamento das informações pelo ESP32.
- [x] Alertas visuais por meio de LEDs.
- [x] Alertas sonoros por meio de buzzer.
- [x] Desenvolvimento do protótipo eletrônico.
- [x] Desenvolvimento inicial da plataforma web.
- [ ] Aprimoramento do armazenamento dos dados.
- [ ] Implementação de monitoramento remoto.
- [ ] Melhorias na precisão dos sensores.

---

## 🚦 Sistema de Alertas

O EcoAir utiliza três indicadores para representar as condições detectadas:

| Indicador | Significado |
|---|---|
| 🟢 LED verde | Condição considerada segura |
| 🟡 LED amarelo | Atenção |
| 🔴 LED vermelho + buzzer | Alerta |

---

## 🛠️ Tecnologias Utilizadas

### Hardware
- ESP32 – Microcontrolador responsável pelo processamento.
- MQ-135 – Sensor utilizado para leitura de gases e qualidade do ar.
- LEDs verde, amarelo e vermelho.
- Buzzer.
- Resistores.
- Jumpers.
- Protoboard.

### Software e ferramentas
- Arduino IDE – Programação do microcontrolador.
- HTML, CSS e JavaScript – Desenvolvimento web.
- Visual Studio Code – Edição de código.
- Figma – Prototipação de interfaces.
- Tinkercad – Representação de circuitos.
- Git e GitHub – Versionamento e armazenamento do projeto.

### Banco de Dados
A tecnologia específica para armazenamento dos dados será definida conforme a implementação da plataforma web.

---

## 🧪 Requisitos Funcionais

- **RF01** – O sistema deve realizar a leitura do ar utilizando o sensor MQ-135.
- **RF02** – O ESP32 deve processar os sinais recebidos pelo sensor.
- **RF03** – O sistema deve identificar valores acima dos limites configurados.
- **RF04** – O sistema deve acionar LEDs conforme as condições detectadas.
- **RF05** – O sistema deve emitir alertas sonoros por meio do buzzer.
- **RF06** – O sistema deve enviar os dados coletados para a plataforma web.
- **RF07** – A plataforma deve armazenar as medições.
- **RF08** – A plataforma deve apresentar as informações coletadas.

---

## 🚫 Requisitos Não Funcionais

- **RNF01** – O sistema deve possuir baixo custo de implementação.
- **RNF02** – A plataforma deve apresentar uma interface simples e intuitiva.
- **RNF03** – Os dados devem ser apresentados de maneira organizada.
- **RNF04** – O sistema deve permitir o acompanhamento das medições.
- **RNF05** – A comunicação entre o dispositivo e a plataforma deve ser confiável.
- **RNF06** – A plataforma deve facilitar o acesso às informações ambientais.

---

## 📅 Cronograma do Projeto

| Etapa | Descrição | Período |
|---|---|---|
| 1 | Planejamento e pesquisa | Junho/2026 |
| 2 | Aquisição e teste dos componentes | Junho–Julho/2026 |
| 3 | Montagem do circuito | Julho/2026 |
| 4 | Desenvolvimento do site | Julho–Agosto/2026 |
| 5 | Integração do site com o dispositivo | Setembro–Outubro/2026 |
| 6 | Testes finais | Outubro/2026 |
| 7 | Finalização e apresentação | Novembro/2026 |

---

## 🧑‍💻 Integrantes da Equipe

| Nome |
|---|
| Arthur Farias |
| Maurício Moreira |
| Miguel Veríssimo |
| Nicole Aparecida |
| Rúbia Cristina |
| Ryan Christopher |

**Orientador:** Matheus Matos Oliveira

**Coorientadora:** Adriely Werneck

---

## 💰 Custo do Projeto

O custo total dos componentes utilizados no protótipo foi de:

**R$ 113,97**

O baixo custo é uma das características do EcoAir, facilit