VANT com painéis solares
========================

.. figure:: /img/Aerial/vantsolar/vantsolar.png
   :align: center
   :width: 450px

   Aeronave Ranger EX Volatex RC com asa modificada

.. http://www2.ene.unb.br/henrique/oportunidades.html

.. TRADUZIR

Este trabalho trata do desenvolvimento de um VANT (veículo aéreo não tripulado) de asa fixa com um sistema de obtenção e gerenciamento de energia por meio de células solares dispostas em sua asa. Os sistemas que compôem o VANT com painéis solares são: Sistema de navegação e controle, sistema de gerenciamento de energia e FPV. 

.. The objective of this work is the development of an unmanned aerial vehicle (UAV) with a system for obtaining and managing energy by solar cells arranged in its wing.

O sistema de gerenciamento de energia permite ao VANT maior autonomia, potencializando sua capacidade em missões de reconhecimento e vigilância. É uilizado neste projeto o algoritmo de rastemaento de ponto de máxima potência que possibilita o ajuste continuo da impedância percebida para que o sistema fotovoltaico opere na região do ponto de máxima potência do painel fotovoltaico.

.. The energy management system allows UAV greater autonomy, enhancing its capacity in reconnaissance and surveillance missions.

O sistema de Navegação e Controle possui sensores responsáveis pela determinação da posição, velocidade, altitude, bem como um gerenciamento por software em uma estação em solo para controle e monitoramento da aeronave. Os sensores que compôem o sistema de navegação são: giroscópio, barômetro, magnetômetro, acelerômetro e o GPS.

.. Its management system consists of three subsystems: Navigation system, control system and energy management system. For energy management, two methods are available in this documentation: that of pulse width modulation (PWM) and that of maximum power point tracking.

O VANT com painéis solares é uma modificação do modelo Ranger EX Volatex RC, substituindo-se sua asa original por uma asa com perfil Clark-Y 11,5% smoothed com 36 células fotovoltaicas alocadas na sua superfície.

.. The UAV with solar panels is a modification of the Ranger EX Volatex RC model in which its original wing was replaced by a wing with a Clark-Y 11.5% smoothed profile with 36 photovoltaic cells allocated on its surface.
	
.. toctree::
   :maxdepth: 2
   :caption: Piloto Automático

   vantsolar/1-macrosistema/1.0-macrosistema
   
	
.. toctree::
   :maxdepth: 2
   :caption: Hardware Embarcado

   vantsolar/2-hardware_embarcado/2.0-hardware_embarcado

.. toctree::
   :maxdepth: 2
   :caption: Sistema obtenção e Gerenciamento de Energia

   vantsolar/3-energia/3.0-energia

.. toctree::
   :maxdepth: 2
   :caption: Projeto Aerodinâmico

   vantsolar/4-aero/4.0-aero

.. toctree::
   :maxdepth: 2
   :caption: Sistema de Navegação e Controle

   vantsolar/5-navegacao_controle/5.0-config_pilot

.. toctree::
   :maxdepth: 2
   :caption: Sistema de comunicação

   vantsolar/6-sistema_comunicacao/6.0-sistema_comunicacao
   
.. toctree::
   :maxdepth: 2
   :caption: Sistema de FPV

   vantsolar/7-sistema_fpv/7.0-sistema_fpv

Referências
-----------

* PEREIRA, G. H. S. Análise de parâmetros aerodinâmicos e configuração de sistemas de comunicação e captação de imagem para um VANT com painéis solares nas asas. Faculdade de Tecnologia, Universidade de Brasília, 2019.

* GOMES, D. H. Configuração e estudo do sistema de gerenciamento de energia, navegação e controle como parâmetros ótimos na montagem e desempenho de um VANT com painéis solares. Faculdade de Tecnologia, Universidade de Brasília, 2019.

* `PX4 Autopilot User Guide`_ - docs.px4.io

* `QGroundControl User Guide`_ - qgroundcontrol.com

* `Ardupilot Docs`_ - ardupilot.org

* `RT-MaG Project`_ - gipsa-lab.fr

* `Yocto Project`_ - yoctoproject.org

* `Getting Started - Gumstix COM`_ - gumstix.com

* `Gumstix, Inc - GitHub`_ - github.com
   

.. _Gumstix, Inc - GitHub: https://github.com/gumstix
.. _Getting Started - Gumstix COM: https://www.gumstix.com/support/getting-started
.. _RT-MaG Project: http://www.gipsa-lab.fr/projet/RT-MaG/
.. _Yocto Project: https://www.yoctoproject.org/
.. _PX4 Autopilot User Guide: https://docs.px4.io/master/en/index.html
.. _QGroundControl User Guide: https://docs.qgroundcontrol.com/en/
.. _Ardupilot Docs: https://ardupilot.org/copter/index.html
