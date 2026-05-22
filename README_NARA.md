# 🦽 NARA — Cadeira de Rodas Autônoma

<div align="center">

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![ROS2](https://img.shields.io/badge/ROS_2-22314C?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

**Primeira cadeira de rodas autônoma desenvolvida no Brasil**  
Projeto de pesquisa do [GIPAR](https://www.ifba.edu.br) — Instituto Federal da Bahia, Campus Vitória da Conquista

</div>

---

## 📖 Sobre o Projeto

O **NARA** (*Navegação Autônoma para Reabilitação e Acessibilidade*) é uma plataforma robótica móvel baseada em cadeira de rodas motorizada, desenvolvida para oferecer autonomia e independência a pessoas com mobilidade reduzida.

O projeto combina técnicas de robótica móvel, processamento de sensores e inteligência artificial para permitir que a cadeira navegue de forma autônoma em ambientes internos, desviando de obstáculos e seguindo rotas pré-definidas.

---

## ✨ Funcionalidades

- 🗺️ **Mapeamento autônomo** do ambiente com sensores LiDAR
- 📍 **Localização em tempo real** (SLAM — Simultaneous Localization and Mapping)
- 🚧 **Desvio de obstáculos** dinâmico e estático
- 🎮 **Controle manual via teleoperação** (teclado / joystick)
- 🤖 **Navegação autônoma** ponto a ponto com planejamento de trajetória
- 📡 **Comunicação via ROS 2** com arquitetura de nós distribuída

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| ROS 2 | Framework de robótica |
| Nav2 | Stack de navegação autônoma |
| SLAM Toolbox | Mapeamento e localização |
| LiDAR RPLiDAR | Sensor de distância 2D |
| Python | Desenvolvimento dos nós ROS 2 |
| Ubuntu 22.04 | Sistema operacional |

---

## 🏗️ Arquitetura do Sistema

```
NARA
├── Percepção         → LiDAR, sensores de proximidade
├── Mapeamento        → SLAM Toolbox
├── Localização       → AMCL (Adaptive Monte Carlo Localization)
├── Planejamento      → Nav2 (Planner + Controller)
└── Controle          → Interface cmd_vel / Ackermann
```

---

## 🔒 Disponibilidade do Código

Este projeto é desenvolvido no âmbito de um grupo de pesquisa institucional (**GIPAR/IFBA**) e o código-fonte **não está disponível publicamente** por questões de propriedade intelectual e política interna do instituto.

Caso tenha interesse em colaborações acadêmicas ou mais informações sobre o projeto, entre em contato através das informações no perfil.

---

## 👥 Equipe

Desenvolvido pelo **GIPAR — Grupo de Inovação e Pesquisa em Automação e Robótica**  
Instituto Federal da Bahia — Campus Vitória da Conquista, BA

---

## 📬 Contato

Para colaborações, dúvidas ou informações acadêmicas:

[![GitHub](https://img.shields.io/badge/GitHub-pdaugusto-181717?style=for-the-badge&logo=github)](https://github.com/pdaugusto)

---

<div align="center">
<sub>Desenvolvido com 🤖 pelo GIPAR/IFBA</sub>
</div>
