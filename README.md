# Inversor PWM - Simulador Interativo

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Online-green?logo=github)](https://eder-queiroz.github.io/inversor-pwm/)

> **Acesse a simulação online:**  
> [https://eder-queiroz.github.io/inversor-pwm/](https://eder-queiroz.github.io/inversor-pwm/)

---

## ⚡ Sobre o Projeto

Este repositório apresenta uma simulação visual e interativa de um **inversor PWM senoidal**, muito utilizado em eletrônica de potência para geração de sinais de saída alternada (AC) a partir de uma fonte contínua (DC).

O projeto permite:
- Gerar e visualizar **onda senoidal** e **onda triangular** com frequências ajustáveis.
- Visualizar o **sinal PWM** gerado a partir da comparação entre a senoide (referência) e a triangular (portadora).
- Ajustar em tempo real a frequência das ondas e o número de períodos exibidos no gráfico.
- Entender o funcionamento do controle PWM aplicado em inversores.

---

## 🎯 Como funciona

O inversor PWM utiliza a técnica de **modulação por largura de pulso** para criar uma onda de saída "retangular" (PWM) que, após filtragem, se aproxima de uma senoide.  
Neste simulador, a onda PWM é gerada comparando ponto a ponto uma senoide (modulante) com uma onda triangular (portadora).

- **Senoide:** referência de saída (por exemplo, 60 Hz).
- **Triangular:** sinal de comparação de alta frequência (portadora).
- **PWM:** sinal digital, em nível alto quando a senoide está acima da triangular, e baixo caso contrário.

---

## 🖥️ Acesse agora

Você pode acessar e testar o simulador diretamente pelo GitHub Pages:  
👉 [https://eder-queiroz.github.io/inversor-pwm/](https://eder-queiroz.github.io/inversor-pwm/)

---

## 🚀 Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/eder-queiroz/inversor-pwm.git
2. Abra o arquivo index.html em qualquer navegador moderno.

## 📚 Mais sobre Inversores PWM

O inversor PWM (Modulação por Largura de Pulso) é uma tecnologia fundamental na eletrônica de potência moderna, permitindo a conversão eficiente de tensão contínua (DC) em tensão alternada (AC). Esse processo é indispensável em diversas aplicações, como sistemas fotovoltaicos, acionamento de motores elétricos e fontes de alimentação para equipamentos que necessitam de energia alternada.

O princípio de funcionamento do inversor PWM consiste em comparar uma onda senoidal, que serve como referência e define a forma de onda desejada, com uma onda triangular de frequência mais alta, conhecida como portadora. Sempre que o valor da senoide é superior ao da triangular, o sinal PWM assume nível alto; caso contrário, permanece em nível baixo. O resultado é uma sequência de pulsos de largura variável ao longo do tempo — daí o nome da técnica.

Quando este sinal PWM é aplicado a um circuito de filtragem (normalmente utilizando filtros do tipo LC), é possível reconstruir uma forma de onda alternada bastante próxima da senoide original. Esse método oferece várias vantagens: possibilita o ajuste preciso da frequência e da amplitude da tensão de saída, aumenta a eficiência do sistema, reduz perdas por aquecimento e proporciona um controle mais refinado em cargas como motores elétricos.

Neste simulador, você pode visualizar de forma interativa as ondas senoidal, triangular e o sinal PWM gerado pela comparação entre elas. Isso facilita a compreensão do conceito e da importância dos inversores PWM em aplicações do dia a dia, além de ser uma ótima ferramenta didática para quem está estudando eletrônica de potência.
