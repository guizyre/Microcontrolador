# ⚡ STM32F407 Microcontroller Projects

Este repositório é dedicado ao desenvolvimento de firmware e aplicações para o microcontrolador **STM32F407 (ARM Cortex-M4)**. O objetivo é documentar a implementação de drivers, o controle de periféricos e a lógica de sistemas embarcados de alta performance.

---

## 🛠️ Especificações Técnicas
* **Core:** ARM® 32-bit Cortex®-M4 CPU com FPU.
* **Frequência:** Até 168 MHz.
* **Memória:** 1 MB Flash / 192 KB RAM.
* **Periféricos Explorados:** GPIO, UART/USART, SPI, I2C, ADC, DAC e Timers Avançados.

---

## 📂 Organização do Repositório

| Pasta | Descrição | Status |
| :--- | :--- | :--- |
| `Drivers/` | Implementações de baixo nível e abstrações (HAL/LL). | 🏗️ Em progresso |
| `Control/` | Algoritmos de PWM, controle de motores e PID. | ✅ Estável |
| `Communication/` | Protocolos de rede e comunicação serial. | 🛠️ Testando |
| `Projects/` | Aplicações completas (Ex: Fechadura Digital, Sensores). | ✅ Estável |

---

## 🚀 Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  **Abra o projeto:** Importe a pasta desejada no **STM32CubeIDE** ou sua IDE de preferência.
3.  **Build & Flash:** Compile o código e faça o upload para a placa usando um ST-LINK.

---

## 🧠 Conceitos Aplicados
* **Máquinas de Estados (FSM):** Lógica estruturada para transições de estados complexas.
* **Interrupções:** Gerenciamento eficiente de prioridades e eventos em tempo real.
* **DMA:** Transferência de dados sem sobrecarga da CPU.

---

## 🤝 Contribuidores
Este projeto é desenvolvido como parte dos estudos de engenharia e colaborações acadêmicas:

* **Guilherme Gonçalves** - *Desenvolvedor Principal*
* **João Pedro** - *Colaborador Acadêmico*

---

> **Nota:** Este projeto foi desenvolvido seguindo as melhores práticas de codificação para sistemas críticos e documentação técnica.
