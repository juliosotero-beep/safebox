# SafeBox

## Sistema Inteligente de Monitoramento de Ambientes

Projeto acadêmico desenvolvido pela empresa fictícia **SafeBox Tecnologia**, como parte do curso de Análise e Desenvolvimento de Sistemas.

---

## 1. Sobre a Empresa

A SafeBox Tecnologia é uma empresa fictícia voltada ao desenvolvimento de soluções tecnológicas de baixo custo utilizando sistemas embarcados.

A empresa busca desenvolver soluções simples e acessíveis para automação, monitoramento e segurança de ambientes.

---

## 2. Sobre o Projeto

O SafeBox é um sistema embarcado desenvolvido para realizar o monitoramento de determinadas condições de um ambiente.

O sistema utiliza um ESP32 conectado a sensores e atuadores para coletar informações, processar os dados e apresentar informações ao usuário por meio de um display.

---

## 3. Problema

Pequenos ambientes, como salas, laboratórios, escritórios e pequenos estabelecimentos, podem não possuir uma solução de baixo custo para acompanhar informações básicas do local.

Entre os principais problemas estão:

- Falta de monitoramento da temperatura;
- Falta de acompanhamento da umidade;
- Dificuldade para identificar presença;
- Falta de identificação de abertura de portas;
- Ausência de alertas locais.

---

## 4. Solução

O SafeBox propõe uma solução utilizando um ESP32 e diferentes sensores para realizar o monitoramento do ambiente.

O sistema será capaz de:

- Medir temperatura;
- Medir umidade;
- Detectar presença;
- Detectar abertura de porta;
- Exibir informações em um display;
- Emitir alertas visuais;
- Emitir alertas sonoros.

---

## 5. Tecnologias

### Hardware

- ESP32
- DHT11
- HC-SR04
- Reed Switch
- Display OLED
- LED verde
- LED vermelho
- Buzzer
- Protoboard
- Jumpers
- Resistores

### Software

- Arduino IDE
- C/C++
- Git
- GitHub

---

## 6. Funcionalidades

- [ ] Inicialização do sistema
- [ ] Leitura de temperatura
- [ ] Leitura de umidade
- [ ] Detecção de presença
- [ ] Detecção de abertura de porta
- [ ] Exibição das informações no display
- [ ] LED de indicação
- [ ] Alerta visual
- [ ] Alerta sonoro
- [ ] Testes do sistema
- [ ] Documentação do projeto

---

## 7. Arquitetura

O funcionamento básico do sistema será:

```text
              +----------------+
              |    Sensores    |
              +-------+--------+
                      |
                      v
              +----------------+
              |      ESP32     |
              +-------+--------+
                      |
          +-----------+-----------+
          |           |           |
          v           v           v
       Display       LEDs       Buzzer