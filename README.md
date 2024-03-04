# Explorando o Machine Learning Automatizado no Azure Machine Learning

### Neste guia, vou compartilhar minha experiência ao explorar o Machine Learning Automatizado no Azure Machine Learning.

<br>

## Passo 1: Criar um espaço de trabalho do Azure Machine Learning

- Acessei o [portal do Azure](https://portal.azure.com/) e fiz login com minhas credenciais.
- Criei um novo recurso do Azure Machine Learning com as configurações necessárias, como assinatura, grupo de recursos e região.
- Aguardei a criação do espaço de trabalho e acessei o Azure Machine Learning Studio.

## Passo 2: Utilizar o aprendizado de máquina automatizado

- Acessei a página Automated ML em Authoring no Azure Machine Learning Studio.
- Criei um novo trabalho de ML automatizado com as configurações específicas, como nome do trabalho, tipo de tarefa e métricas.
- Enviei o trabalho de treinamento e aguardei a conclusão do processo.

## Passo 3: Avaliar o melhor modelo

- Após a conclusão do trabalho automatizado, revisei o melhor modelo treinado na guia Visão geral do trabalho automatizado de aprendizado de máquina.
- Analisei os gráficos residuais e predito_true para avaliar o desempenho do modelo.

## Passo 4: Implantar e testar o modelo

- Na guia Modelo do melhor modelo treinado, selecionei Implantar e escolhi a opção de serviço Web para implantar o modelo.
- Aguardei a implantação e verifiquei se o status mudou para "Succeeded".
- Testei o serviço implantado na guia Endpoints do Azure Machine Learning, substituindo os dados de entrada pelo JSON fornecido e revisei os resultados do teste.

<br>

Este foi o resumo da minha jornada ao explorar o Machine Learning Automatizado no Azure Machine Learning. Siga esses passos e aproveite a experiência de treinar, avaliar, implantar e testar um modelo de aprendizado de máquina de forma automatizada.

**Tempo estimado**: Aproximadamente 30 minutos para conclusão.
