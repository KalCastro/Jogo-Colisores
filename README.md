# Jogo-Colisores
## Colaboradores

- Kauã de Castro(KalCastro)
- Vincenzo Monaco(VincenMonaco)

## Conceitos adicionados
- Static Collider
- Rigidbody Collider
- Kinematic Rigidbody collider
- Static Trigger Collider
- Rigidbody Trigger Collider
- Kinematic Rigidbody Trigger Collider

## Demonstração

https://github.com/KalCastro/Jogo-Colisores/assets/129300311/14421d87-c96b-4a55-8340-17999767a631

## Explicação

Nesta cena os colisores pesquisados anteriormente foram utilizados na pratica, cada objeto da cena possui algum colisor.
   
  - Nas paredes: Foi aplicado o Static. 
  - Na esfera: Foi aplicado o Rigidbody.
  - No Cubo do meio: Foi aplicado o Kinematic Rigidbody
  - No Cubo a Direita: Foi aplicado o Rigidbody.
    
Na cena tambem há objetos transparentes um abaixo da esfera, um abaixo do Cubo a direita e outro atras do cubo ao meio.

 - Na esfera acima do objeto foi aplicado o Rigidbody Trigger quando a esfera cai sobre o objeto com a tag "Player" ela é destruida.
 - No objeto abaixo do cubo a direita foi aplicado o Static Trigger quando o cubo cai sobre ele o cubo é repelido na direção oposta.
 - No ultimo objeto transparente foi aplicado o Kinematic Rigidbody Trigger quando o cubo do meio que tem um script de movimento passa por ele, o cubo é destruido e aparece uma mensagem abaixo na tela escrito objeto coletado.

## Codigo

![Captura de tela 2023-10-29 144629](https://github.com/KalCastro/Jogo-Colisores/assets/129300311/9b7f1c1f-b79c-4f59-9d03-67c794ac68a6)

![Captura de tela 2023-10-29 144650](https://github.com/KalCastro/Jogo-Colisores/assets/129300311/6800c16f-b357-48c7-a029-e7a373a4e726)

![Captura de tela 2023-10-29 144718](https://github.com/KalCastro/Jogo-Colisores/assets/129300311/8ce0f61c-ade5-4821-9d2d-fb4d8a23a1b0)

![Captura de tela 2023-10-29 144739](https://github.com/KalCastro/Jogo-Colisores/assets/129300311/0151f23d-9828-41c0-8877-69401ca6b837)
