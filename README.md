# Predição de Receita de Filmes
Este projeto é uma análise de dados e modelagem de machine learning para prever a receita de filmes baseado em várias variáveis, comparando os resultados de diferentes tipos de regressão. Utiliza-se uma base de dados contendo informações sobre orçamento, popularidade, duração, avaliação e quantidade de votos de diversos filmes.

# Dependências
Para executar este projeto, você precisará fazer download do dataset, disponível no link abaixo: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv

Além das seguintes bibliotecas instaladas:
numpy
pandas
scikit-learn

Você pode instalá-las usando o gerenciador de pacotes pip:
pip install numpy pandas scikit-learn

# Como funciona
Este script realiza a leitura do arquivo CSV contendo a base de dados, realiza uma análise exploratória dos dados e, em seguida, executa a modelagem de machine learning para prever a receita de filmes.

O script salva o modelo treinado em um arquivo chamado model.pkl. Esse arquivo pode ser carregado em outros programas para fazer previsões sobre a receita de novos filmes.

# Resultados
O modelo de machine learning utilizado para prever a receita de filmes alcançou uma pontuação R² de 0,796 com a regressão polinomial. Isso significa que ele é capaz de explicar 79,6% da variação nos dados de receita.

# Autor

Este projeto foi desenvolvido por [Juliana Alves]. Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.




