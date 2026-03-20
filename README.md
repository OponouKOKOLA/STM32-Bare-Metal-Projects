# STM32 Bare-Metal Projects — ARM Cortex-M

Projets de programmation bare-metal sur STM32L152RE
sans couche d'abstraction HAL — configuration directe
des registres.

## 🛠️ Matériel utilisé
- STM32 Nucleo-L152RE (ARM Cortex-M3)
- LED externe
- Breadboard + fils Dupont
- Câble USB

## 📁 Projets réalisés

### 1. LED  bare-metal
- Configuration GPIO en sortie via MODER
- Clignotement via ODR + HAL_Delay

### 2. Bouton + LED
- Configuration GPIO en entrée (PC13)
- Lecture IDR — contrôle LED PC0

### 3. UART — Communication série
- Configuration USART2 bare-metal
- PA2/PA3 en AF7 via AFR
- Envoi de texte vers PC via PuTTY (9600 baud)

## 🔧 Concepts maîtrisés
- Registres RCC, MODER, ODR, IDR, AFR
- Protocole UART bare-metal
- Manipulation de bits (|=, &=~, ^=, <<)

## 📌 Environnement
- STM32CubeIDE
- PuTTY (terminal série)
- Git / GitHub

  ## 📸 Démonstration

### LED externe qui clignote
[![LED Bare-Metal](images/led.jpg)](https://s2.ezgif.com/tmp/ezgif-27c6250ef999f2d1.gif)

### Communication UART sur PuTTY
<img width="302" height="41" alt="image" src="https://github.com/user-attachments/assets/408d3b5d-e471-4fc5-b23e-57a4fc287d10" />


## 👤 Auteur
Emmanuel Oponou KOKOLA — M1 Électronique
Université de Rennes
github.com/OponouKOKOLA

## 📬 Contact
- 📧 manuelkokola@gmail.com
- 💼 LinkedIn : linkedin.com/in/oponou-emmanuel-kokola-44054b292
