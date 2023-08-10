Planejamento da bancada elétrica.
- Ideias e funcionalidades básicas
o Posicionamento de componentes IFC com informações elétricas e construtivas
o Gerar uma biblioteca vasta de componentes elétricos utilizados no Brasil
o Gerar uma tabela de quantitativos
o Gerar legenda automática
o Dimensionamento de cabos, eletrodutos, eletrocalha, motores etc. Segundo normas.
o Geração de relatório base.
o Gerar planta 2D com simbologia ou 3D.
o Informações de cabos dentro de eletrodutos.
- As normas, vamos modelar a bancada desacoplada de normas, deixando o usuário selecionar a norma vigente em seu país, vamos elaborar uma pasta com normas separadas.
- Exemplo da organização das pastas
  
![image](https://github.com/joaocoutojc/EletroAlfa/assets/89688702/1cf36039-1b1f-4cd3-a60d-0c0f2ed77f9e)

Pasta BT – Pasta com funcionalidade para projetar em baixa tensão
- Pasta Core – Elementos fundamentais para o funcionamento da bancada
- EletroData – Pasta com informações de componentes, como Cabos, Eletrodutos, Barramentos etc.
- functions – Cálculos bases para dimensionamentos, de Cabos, motores, eletrodutos etc.
- Normas – Pasta para as classes de Normas vigentes selecionadas pelo usuário, onde ele vai
auxiliar nos dimensionamentos da pasta functions
- QuadroComando – Pasta para auxiliar a projetar quadros de comando 2D e 3D
- Resources – componentes base para bancada como ícones, traduções, logos.
- Shape – Primeiro momento, componentes elétricos base para a bancada funcionar, mas
futuramente, componentes vão ser inserido externo do sistema.
