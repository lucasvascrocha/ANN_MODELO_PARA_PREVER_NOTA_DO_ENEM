# ANN_MODELO_PARA_PREVER_NOTA_DO_ENEM
Aplicaço de modelo de Artificial neura nets para previsao de dados
# CONTEXTO 
## Modelo de machine learning ANN que consegue prever a nota do enem de um aluno de acordo com suas notas em outras matérias
**Abstract:**
O ENEM é a maior prova unificada do país que através de sua avaliação permite a entrada de alunos em universidades públicas. Foram avaliadas as notas dos alunos em diversas matérias e suas características pessoais. Através do desempenho do aluno nas provas de ciências naturais, ciências humanas, línguas e redação o modelo é capaz de prever a sua nota de matemática.
As características pessoais dos candidatos não se caracterizaram como bons indicadores para prever as notas de matemática, com isso, foram utilizados para a previsao somente as notas das provas citadas anteriormente.
Utilizando dados de teste para esta situação o modelo teve uma alta acertividade com uma margem de erro de 42 pontos em mil para mais ou para menos, ou seja 95,8% de precisao, sendo considerado um ótimo parâmetro para a previsão.


# Sobre o desenvolvimento

Foram utilizados arquivos disponibilizados pela Codenation. O código foi desenvolvido em python e apresentado em jupyter notebook.

# Perguntas a serem respondidas

1. Quais características dos alunos são bons indicadores de previso para sua nota de matemática?

-Notas do aluno nas provas de ciências naturais, ciências humanas, línguas e redação

2. É possível prever a nota de matemática de um aluno com base em suas características ou notas?

-Sim, apenas com as notas em outras matérias, as características pessoais não foram consideradas boas preditoras


# Requisitos

- Python 3.5
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- Scipy
- tensorflow
