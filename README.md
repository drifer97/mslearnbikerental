# mslearnbikerental
Historic bike rental data Azure


Primeiro, entro no Azure Machine Learning Studio e faço login. Uma vez dentro, preciso de um espaço de trabalho, ou workspace, então crio um novo para organizar tudo. Dou um nome a ele, escolho a assinatura e a região, e pronto, estou no meu próprio “laboratório” de machine learning.

Agora vou criar um experimento. Como estamos prevendo o aluguel de bicicletas, dou um nome intuitivo, tipo “Previsão de Aluguel de Bicicletas”. Em seguida, vou para a seção de Datasets e carrego o conjunto de dados que vou usar no projeto. O arquivo CSV tem informações importantes, como a data, o clima, a temperatura, e a quantidade de bicicletas alugadas em diferentes horários do dia.

Com os dados carregados, é hora de preparar tudo. Primeiro, verifico se há algum dado faltando (valores nulos) e, se houver, removo ou preencho esses valores. Faço umas normalizações básicas para que tudo esteja na mesma escala e divido os dados em dois grupos: treino e teste. Assim, posso ver depois se o modelo consegue fazer previsões precisas para dados novos.

Em seguida, parto para o treinamento do modelo. Aqui no Azure, escolho um algoritmo que funcione bem para previsão de números, como regressão linear. Configuro os parâmetros básicos e começo o treinamento. O Azure acompanha o progresso e, no final, me mostra métricas de performance para entender o quanto o modelo aprendeu a prever o aluguel de bicicletas.

Depois disso, vou para a parte de avaliação, onde uso os dados de teste para ver como o modelo está performando. Olho métricas como a precisão e o erro médio — tudo isso me dá uma ideia se o modelo está acertando ou se ainda precisa de ajustes.

Se tudo estiver em ordem, é hora do deploy, ou seja, publico o modelo para que ele esteja disponível como um serviço da web. Configuro as opções de implantação e pronto! Agora outras aplicações podem usar esse modelo para fazer previsões de aluguel de bicicletas.

Por fim, dou uma revisada nos resultados e penso em ajustes para melhorar ainda mais a precisão. É um processo bem interessante, pois passo por cada etapa do machine learning, desde organizar os dados até ter o modelo disponível para uso em aplicações reais.
