# Sistema de análise de qualidade de produtos
<p align="justify">
Atualmente, o mundo vive a 4ª Revolução Industrial, caracterizada pelo uso intensivo de dados para viabilizar a comunicação entre as máquinas que compõem os processos industriais. Nesse contexto, a inspeção de qualidade se destaca como um processo crítico para garantir a conformidade dos produtos finais com os padrões estabelecidos. Em vista disso, surge a proposta de utilizar a IoT (Internet of Things, ou Internet das Coisas) no setor de inspeção de qualidade de produtos, representando mais um avanço significativo dentro desse novo paradigma. A aplicação dessa tecnologia tem como objetivo otimizar as linhas de produção, permitindo de forma antecipada a identificação de um erro. 
</p>

**Metodologia**

- Definição de escopo
<p align="justify">
Nesta etapa foram definidos os defeitos a serem identificados bem como o objeto de estudo que será adotado como sendo uma luva.
</p>
- Coleta de dados
<p align="justify">
Serão feitas coletas de imagens, em ambiente controlado, rotulando as mesmas em duas categorias, "peça com defeito" e "peça sem defeito".
</p>
- Pré-processamento dos Dados
<p align="justify">
Essa etapa consite em contribuir para melhorar a capacidade de generalização da rede neural. Ou seja, todas as imagens coletadas serão padronizadas.
</p>
- Desenvolvimento do Modelo de IA
<p align="justify">
A arquitetura adotada será baseada em Redes Neurais Convolucionais (CNNs) para isso utilizaremos o ambiente Visual Studio Code com a linguagem Python, empregando bibliotecas PyTorch.
</p>
- Treinamento do modelo
<p align="justify">
Foi adotada a disposição 70% treinamento, 15% validação e 15% teste. Além disso, foram ajustados parâmetros como número de camdas e taxa de apresendizado.
</p>
- Avaliação de Desempenho
<p align="justify">
Etapa que monitor o progresso e identifica acertos e falahas, tornando possível distirguir falso positivo (aprovação indevida de peças com defeito) e falso negativo (reprovação indevida de peças corretas).
</p>
- Implementação do Protótipo
<p align="justify">
Após a validação, será desenvolvido um protótipo funcional capaz de receber imagens em tempo real e emitir a decisão de “aprovado” ou “reprovado”.
</p>
