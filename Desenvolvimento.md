# Desenvolvimento

O sensor de efeito Hall mede a posição do objeto levitado e envia um sinal de tensão proporcional
à distância ao comparador. Esse comparador é implementado com um amplificador operacional,
que compara o sinal recebido com uma tensão de referência ajustável. A tensão de referência 
define o ponto de equilíbrio do objeto.

O comparador processa o sinal de entrada e gera um sinal de controle de saída. Esse sinal é 
enviado para o gate de um MOSFET, que regula a corrente que passa pela bobina do eletroímã.

O MOSFET funciona como um chaveador, controlando o liga e desliga do eletroímã de forma 
proporcional ao sinal do comparador. Dessa forma, o sistema ajusta dinamicamente o campo 
magnético produzido pela bobina.

Ao controlar o campo magnético gerado pelo eletroímã, o sistema consegue estabilizar o objeto
levitado, ajustando sua distância em relação ao eletroímã. O ponto de equilíbrio pode ser 
alterado por meio do ajuste da tensão de referência no comparador.

![Captura de tela 2024-11-18 125344](https://github.com/user-attachments/assets/fdde3a2e-a0cc-4661-b237-55a43d138bed), ![Levitador_magnético](https://github.com/user-attachments/assets/af01046c-6b2f-46d0-9ca2-be716a9102fe)


Para o suporte do projeto, utilizamos um modelo disponível no Thingiverse como base.

![694957be85e14cae4f33ac5997d11b8a_display_large](https://github.com/user-attachments/assets/1cc49ee8-34da-4b27-a638-5d3e65a97f1e)


## Referências

Vídeo no YouTube: "Como construir um levitador magnético", disponível em: https://www.youtube.com/watch?v=eOT_G-1ogn4. Acesso em: 18 nov. 2024.

Playlist no YouTube: "Controle PID com Arduino - Aula 15", disponível em: https://www.youtube.com/watch?v=z6f-lXpHKz4&list=PLSQMBAGorPmUkrGbE4Pem4aGnRrQWcQp7&index=15. Acesso em: 18 nov. 2024.

Artigo: CÔRTES, Hyghor Miranda; PIVOTO, Alex Sander de Magalhães. Modelagem e Simulação do Controle de posição de uma Esfera por um Sistema de levitação magnética em Plataforma Virtual. Disponível em: [https://www.researchgate.net/publication/320540281_Modelagem_e_Simulacao_do_Controle_de_posicao_de_uma_Esfera_por_um_Sistema_de_levitacao_magnetica_em_Plataforma_Virtual].

Artigo: GUEDES, Rafael Augusto de Oliveira. Projeto para Módulo Didático de um Levitador Magnético e Proposta para Controle Analógico. Disponível em: [https://repositorio.ufrn.br/handle/123456789/56607].

Artigo: ENDALECIO, Alan Dantas de Medeiros. Estudo e Implementação de um Sistema de Levitação Eletromagnética Utilizando Sensores de Efeito Hall. Disponível em: [https://pantheon.ufrj.br/handle/11422/11506].

Modelo 3D: "Levitador magnético - Thingiverse", disponível em: https://www.thingiverse.com/thing:1392023. Acesso em: 18 nov. 2024.
