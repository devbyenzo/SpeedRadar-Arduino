# 🚗 Radar de Velocidade

<div align="center">

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge)
![Sistemas Embarcados](https://img.shields.io/badge/Sistemas%20Embarcados-000000?style=for-the-badge)

# Radar de Velocidade

### Sistema Inteligente de Monitoramento de Velocidade com Arduino

Projeto desenvolvido para monitorar e registrar a velocidade de veículos em tempo real utilizando Arduino e sensores de detecção.

</div>

---

## 📖 Sobre o Projeto

O **SmartVelocityMonitor** é um projeto de sistemas embarcados voltado para a medição e monitoramento de velocidade de veículos.

O sistema utiliza sensores para detectar a passagem dos veículos, calcular sua velocidade e exibir ou armazenar os dados coletados para futuras análises.

Este projeto foi desenvolvido com foco em:

- Sistemas embarcados
- Programação em Arduino
- Processamento de dados
- Engenharia da Computação
- Internet das Coisas (IoT)
- Monitoramento de tráfego

---

## 🎯 Objetivos

- Medir a velocidade de veículos em tempo real;
- Realizar cálculos de velocidade com precisão;
- Registrar informações coletadas;
- Demonstrar aplicações práticas de sistemas embarcados;
- Servir como projeto acadêmico e educacional;
- Possibilitar futuras expansões e melhorias.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| Arduino IDE | Desenvolvimento |
| C++ | Linguagem de Programação |
| Arduino / ESP32 | Microcontrolador |
| Sensores de Detecção | Coleta de Dados |
| Comunicação Serial | Monitoramento |
| Módulo SD (Opcional) | Armazenamento |

---

## 🏗️ Arquitetura do Sistema

```text
Detecção do Veículo
          │
          ▼
      Sensor
          │
          ▼
   Arduino / ESP32
          │
   ┌──────┴──────┐
   ▼             ▼
Display     Armazenamento
          │
          ▼
    Processamento
```

---

## ✨ Funcionalidades

- ✅ Detecção de veículos
- ✅ Monitoramento em tempo real
- ✅ Cálculo automático de velocidade
- ✅ Exibição dos dados coletados
- ✅ Registro de informações
- ✅ Compatibilidade com Arduino e ESP32
- ✅ Estrutura expansível para futuras melhorias

---

## 📂 Estrutura do Projeto

```text
SmartVelocityMonitor/
│
├── src/
│   ├── main.ino
│   ├── sensores.cpp
│   ├── sensores.h
│   ├── calculos.cpp
│   └── calculos.h
│
├── docs/
│   ├── diagramas/
│   └── relatorios/
│
├── imagens/
│
├── README.md
│
└── LICENSE
```

---

## 🚀 Como Executar

### Pré-requisitos

- Arduino IDE instalada
- Arduino Uno, Nano, Mega ou ESP32
- Sensores compatíveis
- Cabo USB

### Instalação

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/SmartVelocityMonitor.git
```

Abra o projeto na Arduino IDE:

```text
Arquivo → Abrir → main.ino
```

Selecione sua placa, porta serial e envie o código para o dispositivo.

---

## 📊 Exemplo de Saída

```text
Veículo Detectado

Velocidade: 43 km/h

Horário:
15:22:17

Status:
Tráfego Normal
```

---

## 🔮 Melhorias Futuras

- Integração com Wi-Fi
- Dashboard Web
- Aplicativo Mobile
- Armazenamento em Nuvem
- Relatórios Automáticos
- Histórico de Velocidades
- Integração com Inteligência Artificial
- Monitoramento de múltiplos veículos

---

## 🎓 Aplicações Educacionais

Este projeto pode ser utilizado em disciplinas como:

- Sistemas Embarcados
- Arduino
- Eletrônica
- Internet das Coisas (IoT)
- Engenharia da Computação
- Automação
- Programação em C++

---

## 📜 Licença

Este projeto é distribuído sob a licença MIT.

---

# 👨‍💻 Equipe do Projeto

<div align="center">

<table>

<tr>
<td align="center">
<a href="https://github.com/devbyenzo">
<img src="https://github.com/devbyenzo.png" width="100px">
<br><b>Enzo Pietrantonio</b>
</a>
</td>

<td align="center">
<a href="https://github.com/profniltonbarros">
<img src="https://github.com/profniltonbarros.png" width="100px">
<br><b>Prof. Nilton Barros</b>
</a>
</td>

<td align="center">
<a href="https://github.com/marcelorodpin-jpg">
<img src="https://github.com/marcelorodpin-jpg.png" width="100px">
<br><b>Marcelo Rodrigues</b>
</a>
</td>

<td align="center">
<a href="https://github.com/Marcoantoniosodre">
<img src="https://github.com/Marcoantoniosodre.png" width="100px">
<br><b>Marco Antonio Sodré</b>
</a>
</td>
</tr>

<tr>
<td align="center">
<a href="https://github.com/jaktmo-star">
<img src="https://github.com/jaktmo-star.png" width="100px">
<br><b>Elcio Silveira</b>
</a>
</td>

<td align="center">
<a href="https://github.com/matheusangelini01">
<img src="https://github.com/matheusangelini01.png" width="100px">
<br><b>Matheus Angelini</b>
</a>
</td>

<td align="center">
<a href="https://github.com/raphaelsquilaro">
<img src="https://github.com/raphaelsquilaro.png" width="100px">
<br><b>Raphael Squilaro</b>
</a>
</td>

<td align="center">
<a href="https://github.com/GabrielaSouzaDev">
<img src="https://github.com/GabrielaSouzaDev.png" width="100px">
<br><b>Gabriela Souza</b>
</a>
</td>
</tr>

<tr>
<td align="center">
<a href="https://github.com/ddudazk">
<img src="https://github.com/ddudazk.png" width="100px">
<br><b>Eduarda Martins</b>
</a>
</td>

<td align="center">
<a href="https://github.com/moraesvzk">
<img src="https://github.com/moraesvzk.png" width="100px">
<br><b>Débora Martins</b>
</a>
</td>

<td></td>
<td></td>
</tr>

</table>

</div>

---

## 🏫 Instituição

Projeto desenvolvido pelos alunos da turma FIC (Formação Inicial e Continuada) do curso de Programação em Python do SENAI de Alumínio - SP.

O Sistema foi criado com o objetivo de aplicar conceitos de programação, eletrônica, sensores e sistemas embarcados através do desenvolvimento de um sistema de monitoramento de velocidade utilizando Arduino.

---

<div align="center">

### 🚀 Projeto Acadêmico

**Turma FIC - Programação em Python**  
**SENAI Alumínio - SP**  
**2026**

</div>
