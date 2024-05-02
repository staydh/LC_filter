# LC_filter
LC filter design using planar inductor generated with ASITIC

## Definição da tarefa
Elaborar o projeto, simulação, layout e sign-off (DRC+LVS) de um filtro LC para a tecnologia sky130 utilizando a ferramenta ASITIC para a geração automática do layout do inversor.

Esta tarefa é dividida em duas partes, como descrito abaixo:

### Parte I

- Utilizar os scripts* para atualização do PDK para a versão recomendada;
- Utilizar o script* de instalação e configuração da workarea para o ASITIC;
- Criar um indutor de X** nH utilizando o ASITIC;
- Ler o indutor no _Magic_ para garantir _DRC clean_, e realize a extração do arquivo SPICE equivalente;
- Realize a simulação AC (verificando a frequência de auto-ressonância e o fator de qualidade), tanto com o modelo Pi gerado pelo ASITIC quanto com o modelo extraído pelo _Magic_ (considerando o valor do indutor sintetizado);
- Faça uma comparação entre as duas simulações;
- Organize o repositório.

### Parte II

- Projetar um filtro LC com frequência de ressonância em Y*** GHz (Elaborar um script para calcular o valor do capacitor e as suas dimensões);
- Realizar o layout do capacitor de forma manual e extrair o arquivo SPICE equivalente;
- Realizar o layout do capacitor utilizando o dispositivo da biblioteca sky130_fd_pr e extrair o arquivo SPICE equivalente;
- Comparar a simulação nos 2 casos anteriores;
- Elaborar o layout do filtro LC (junção do capacitor e do indutor);
- Realizar a simulação pós-layout do filtro.
- Atualizar o repositório.

** Valores diferentes por grupo (G1 = 1; G2 = 2.5);  
*** Valores diferentes por grupo (G1 = 5.8; G2 2.4);

### Referências: 
* https://github.com/britovski/sky130_skel
- Artigos do repositório;
- Página do ASITIC;
- Livro do Niknejad.

## Inicio da organização

Work in progress...
