# Construção 

A montagem do levitador magnético utiliza uma bobina de cobre com aproximadamente 300 espiras de fio AWG 22, enroladas em um núcleo de aço 1020 com dimensões de 5 cm de comprimento e 2 cm de diâmetro. 
Esse conjunto é capaz de gerar um campo magnético suficiente para levitar um ímã de neodímio. 
A alimentação da bobina é controlada por um MOSFET, que atua como uma chave para regular o campo magnético conforme a necessidade do sistema, com o auxílio de um comparador baseado em um amplificador operacional (ampop).
O circuito é alimentado por uma fonte de bancada de 12 V, capaz de fornecer até 2 A de corrente máxima, garantindo uma operação estável e segura.
O controle do campo magnético é realizado por um circuito eletrônico que monitora a posição do objeto a ser levitado, utilizando um sensor de efeito Hall modelo 49E.
Este sensor permite ativar e desativar o sistema de controle de forma precisa, assegurando o funcionamento adequado do levitador.



<p align="center">
  <img src="https://github.com/user-attachments/assets/3beb962f-d72e-4ca5-ba60-3a474c55e8b3" alt="Desligado" width="35%">
  <img src="https://github.com/user-attachments/assets/99a7aedc-f2e6-45cc-895f-b355257c6e4f" alt="Ligado" width="35%">
</p>
