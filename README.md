# Reconhecimento_Facial_Controle_Acesso
Sistema de Reconhecimento Facial para Controle de Acesso

Neste desafio, você aplicará conceitos de Visão Computacional para criar uma aplicação prática de Reconhecimento Facial voltada ao controle de acesso, utilizando a biblioteca DeepFace em conjunto com o OpenCV e o Matplotlib.

Para tanto, você deverá:

Realizar as importações e configurações necessárias das bibliotecas.
Carregar uma imagem e padronizar o espaço de cor (BGR → RGB).
Aplicar o modelo pré-treinado da DeepFace para comparar imagem de teste com um banco de imagens autorizadas.
Exibir o resultado indicando se o rosto é AUTORIZADO ou NÃO AUTORIZADO.
Destacar o resultado visualmente na imagem, desenhando uma moldura colorida com base na classificação.

Nesta atividade, você utilizará um ambiente de programação Python com notebooks (como o Google Colab). O desafio consiste em completar trechos de códigos, executar e, principalmente, compreender o passo a passo detalhado em cada célula. Siga as orientações, execute os códigos, analise os resultados e qualquer dúvida procure seu professor.

O seu notebook e a sua análise final devem, no mínimo, conter:

Importar as bibliotecas DeepFace, OpenCV e Matplotlib.
Carregar uma imagem de teste e garantir sua exibição correta (conversão BGR→RGB).
Comparar a imagem de teste com o diretório “autorizados/” utilizando o método DeepFace.find().
Classificar o resultado como “AUTORIZADO” ou “NÃO AUTORIZADO”.
Exibir a imagem final com uma moldura verde ou vermelha, conforme o resultado obtido.

ORIENTAÇÕES TÉCNICAS
Na construção do seu notebook, se aplicável:

| Etapa | Ações mínimas requeridas | Funções/Ferramentaschave |
| --- | --- | --- |
| Instalação e importação de bibliotecas | Instalar e importar DeepFace, OpenCV e Matplotlib. | !pip install, import |
| Leitura e exibição da imagem | Ler imagem de teste e converter de BGR para RGB antes de exibir. | cv2.imread, cv2.cvtColor, plt.imshow |
| Busca e comparação facial | Executar a função DeepFace.find() comparando a imagem de teste com o banco de imagens autorizadas. | DeepFace.find() |
| Classificação e decisão | Definir o texto e a cor de acordo com o resultado retornado (AUTORIZADO / NÃO AUTORIZADO). | Estrutura condicional if |
| Feedback visual | Desenhar uma moldura colorida na imagem conforme o resultado e exibir com título. | cv2.rectangle, plt.imshow |

DICAS
Para facilitar sua pesquisa e aprendizado durante a prática, fique de olho em algumas
dicas:

1. Documente o processo: insira comentários explicando o propósito de cada célula de código.
2. Verifique os caminhos: certifique-se de que a imagem de teste (teste.jpeg) e o diretório autorizados/ estão corretamente configurados.
3. Compreenda a função: DeepFace.find() é responsável por comparar o rosto com o banco de imagens e retornar a correspondência mais próxima.
4. Visualização: use matplotlib (plt.imshow()) para inspecionar visualmente a imagem antes e depois da classificação.
5. Valide o resultado: observe o feedback textual e visual (“AUTORIZADO” ou “NÃO AUTORIZADO”).
