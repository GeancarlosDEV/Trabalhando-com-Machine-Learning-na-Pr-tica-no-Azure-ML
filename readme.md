# Explorei o Machine Learning Automatizado no Azure Machine Learning

Neste exercício, utilizei o recurso de aprendizado de máquina automatizado no Azure Machine Learning para treinar e avaliar um modelo de aprendizado de máquina. Em seguida, implantei e testei o modelo treinado.

Esse exercício levou aproximadamente 30 minutos para ser concluído.

## Criei um espaço de trabalho no Azure Machine Learning

Para utilizar o Azure Machine Learning, tive que aprovisionar um espaço de trabalho na minha subscrição do Azure. Depois, usei o estúdio Azure Machine Learning para trabalhar com os recursos do meu workspace.

1. Acessei [https://portal.azure.com](https://portal.azure.com) com minhas credenciais da Microsoft.

2. Selecionei "+ Criar um recurso", pesquisei "Machine Learning" e criei um novo recurso do Azure Machine Learning com as configurações necessárias.

3. Após a criação, fui para o recurso implantado e selecionei "Launch Studio" (ou abri uma nova guia do navegador e acessei [https://ml.azure.com](https://ml.azure.com)).

4. No estúdio Azure Machine Learning, verifiquei se via meu espaço de trabalho recém-criado. Caso contrário, selecionei "Todos os espaços de trabalho" no menu à esquerda e escolhi o espaço de trabalho que acabei de criar.

## Usei aprendizado de máquina automatizado para treinar um modelo

O aprendizado de máquina automatizado permitiu que eu experimentasse vários algoritmos e parâmetros para treinar modelos e identificasse o melhor para meus dados.

1. No Azure Machine Learning Studio, acessei a página Automated ML (em Authoring).

2. Criei um novo trabalho de ML automatizado com as configurações especificadas.

3. Aguardei o término do trabalho automatizado. Demorou algum tempo.

## Avaliei o melhor modelo

Quando o trabalho automatizado de aprendizado de máquina foi concluído, pude revisar o melhor modelo treinado.

1. Na guia Visão geral do trabalho automatizado de aprendizado de máquina, observei o melhor resumo do modelo.

2. Selecionei o nome do algoritmo do melhor modelo para visualizar seus detalhes.

3. Na guia Métricas, revisei os gráficos que mostravam o desempenho do modelo.

## Implantei e testei o modelo

1. Na guia Modelo do melhor modelo treinado, selecionei "Implantar" e usei a opção de serviço Web para implantar o modelo com as configurações especificadas.

2. Aguardei o início da implantação e, em seguida, esperei até que o status da implantação mudasse para "Succeeded".

## Testei o serviço implantado

Agora pude testar o serviço implantado.

1. No estúdio Azure Machine Learning, na guia Endpoints, abri o ponto final em tempo real de previsão de aluguel.

2. Na página do endpoint em tempo real de previsão de aluguel, visualizei a guia "Teste".

3. No painel "Dados de entrada para testar o endpoint", substituí o modelo JSON pelos dados de entrada fornecidos.

4. Cliquei no botão "Testar" e revisei os resultados do teste.

## Limpei

Se não pretender experimentar mais, segui as instruções fornecidas para excluir o ponto de extremidade e, se necessário, o espaço de trabalho do Azure Machine Learning para evitar cobranças desnecessárias.

Esse guia resume os passos que segui para explorar o Machine Learning Automatizado no Azure Machine Learning.