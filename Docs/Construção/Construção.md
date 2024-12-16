# Construção 

A montagem do levitador magnético utiliza uma bobina de cobre com aproximadamente 300 espiras de fio AWG 22, enroladas em um núcleo de aço 1020 com dimensões de 5 cm de comprimento e 2 cm de diâmetro. 
Esse conjunto é capaz de gerar um campo magnético suficiente para levitar um ímã de neodímio. 
A alimentação da bobina é controlada por um MOSFET, que atua como uma chave para regular o campo magnético conforme a necessidade do sistema, com o auxílio de um comparador baseado em um amplificador operacional (ampop).
O circuito é alimentado por uma fonte de bancada de 12 V, capaz de fornecer até 2 A de corrente máxima, garantindo uma operação estável e segura.
O controle do campo magnético é realizado por um circuito eletrônico que monitora a posição do objeto a ser levitado, utilizando um sensor de efeito Hall modelo 49E.
Este sensor permite ativar e desativar o sistema de controle.

Foram realizados testes iniciais em bancada para verificar o funcionamento do sistema de controle do levitador magnético. O primeiro teste avaliou a malha de controle formada pelo amplificador operacional (ampop) e pelo sensor de efeito Hall. Este teste apresentou resultados satisfatórios, funcionando perfeitamente conforme mostrado nas imagens abaixo.

O segundo teste, que consiste na avaliação da malha completa (ampop, bobina e MOSFET), ainda não foi realizado devido à demora na chegada de um dos componentes necessários. Este teste será fundamental para validar a integração dos componentes e garantir o controle eficiente do campo magnético gerado pela bobina. (Este parágrafo será atualizado após a realização do teste.)


Lista de componentes utilizados:

Sensor de efeito hall 3144E

Transistor MOSFET IRF9630

Regulador de tensão 7805 

Amplificador operacional(ampop) LM358

Reistor : 100k Ohm

Capacitor de 1000uF eletrolítico 

Capacitor 1mF cerâmico

Diodo 1N4148

<p align="center">
  <img src="https://github.com/user-attachments/assets/f9a38dc8-efd2-4ac4-9691-48e963732ef2" alt="bobina" width="25%">
  <img src="https://github.com/user-attachments/assets/f9b752aa-e10f-4dd8-b49e-266022e4aea2" alt="imã" width="25%">
  <img src="https://github.com/user-attachments/assets/6554351a-f240-4d32-9cc1-77ba78c67284" alt="bobina2" width="50%">
   
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/3beb962f-d72e-4ca5-ba60-3a474c55e8b3" alt="Desligado" width="25%">
  <img src="https://github.com/user-attachments/assets/99a7aedc-f2e6-45cc-895f-b355257c6e4f" alt="Ligado" width="25%">
</p>
