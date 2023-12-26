# Documentação

Este repositório contém o código referente ao trabalho entitulado "Metodologia para seleção de algoritmo de aprendizagem de máquina para estudos de controle centrado no usuário".

Descrição dos arquivos:

<ul>
<li><b>Etapa1:</b> Esta pasta contém os notebooks com o código dos experimentos realizados durante a etapa 1 do trabalho.  </li>
    <ul>
        <li><b>DT.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>Decision Tree</i> (Árvore de Decisão); </li>
        <li><b>kNN.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>k-Nearest Neighbor</i>; </li>
        <li><b>MLP.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>Multilayer Perceptron</i> (Rede Neural); </li>
        <li><b>RF.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>Random Forest</i>; </li>
        <li><b>SVM.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>Support Vector Machine</i>. </li>
    </ul>
    
<li><b>KNN_cenario_real.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>k-Nearest Neighbor</i>sendo aplicado em um cenário real; </li>
<li><b>KNN_otimizacao.ipynb:</b> notebook contendo o código do experimento realizado utilizando o algoritmo <i>k-Nearest Neighbor</i>, variando os tipos de iluminância utilizados durante o treino e teste; </li>
<li><b>mai_2022_fev_2023.csv</b>: conjunto de dados pré-processado.
    <ul>
        <li><b>Descrição das características:</b>
        <ul>
            <li><b>data_ano:</b>	Ano em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>data_mes:</b>	Mês em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>data_dia:</b>	Dia em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>data_hora:</b>	Hora em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>data_minuto:</b>	Minuto em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>data_dia_da_semana:</b>	Dia da semana em que a amostra foi coletada; Tipo de dado:	Inteiro;</li>
            <li><b>iluminancia_caixa:</b>	Iluminância no sensor localizado na estação de medição; Tipo de dado:	Inteiro;</li>
            <li><b>iluminancia_teto:</b>	Iluminância no sensor localizado no teto do ambiente; Tipo de dado:	Inteiro;</li>
            <li><b>temperatura:</b>	Temperatura ambiente; Tipo de dado: 	Ponto Flutuante;</li>
            <li><b>porta:</b>	Estado da porta do ambiente; Tipo de dado:	Booleano;</li>
            <li><b>janela1:</b>	Estado da janela 1 do ambiente; Tipo de dado:	Booleano;</li>
            <li><b>janela2:</b>	Estado da janela 2 do ambiente; Tipo de dado:	Booleano;</li>
            <li><b>usuario_X:</b>	Indicação de presença do usuário no ambiente; Tipo de dado:	Booleano;</li>
            <li><b>output:</b>	Estado dos dois conjuntos de lâmpadas; Tipo de dado:	Inteiro.</li>
        </ul>  
    <ul>   
</ul>