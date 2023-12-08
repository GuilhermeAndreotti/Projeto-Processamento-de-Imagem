# Processamento de Imagens - LBP (Local Binary Patterns)

### Equipe:

- Guilherme Chizzolini Andreotti
- William Tanaka
- Gabriel Saque Marquez

### Descritor implementado:

Foi utilizado para este projeto o descritor Local Binary Patterns (LBP). Esse descritor opera através de uma sequência em binário, convertendo cada pixel de uma imagem nessa sequência e então comparando seus pixeis com os seus vizinhos. Além disso, funciona convertendo primeiro para escalas de cinza.

### Repositório do projeto

Para acessar o projeto, [Clique aqui](https://github.com/GuilhermeAndreotti/Projeto-Processamento-de-Imagem), após isso copie a url do projeto e utilize do comando "git clone <url do projeto> para ter uma cópia ou simplesmente faça download do projeto.

### Classificador e acurácia:

Foram utilizados os mesmos classificadores demonstrados durante as aulas, são eles: 
- Multi-Layer Perceptron (MLP);
- Random Forest (RF);
- Support Vector Machine (SVM).

Foram obtidos os seguintes resultados durante a execução:

- MLP Acurácia: 85.71%;
- SVM Acurácia: 75%;
- RF Acurácia: 92.86%.


### Vídeo demonstrativo:

Abaixo, segue um vídeo demonstrando o projeto:

### Tutorial de intalação:

Para instalar o projeto, siga os seguintes passos:

#### 1 - Instale o miniconda

[Acesse esse link](https://docs.conda.io/projects/miniconda/en/latest/), clique para instalar o miniconda, de acordo com seu sistema operacional.

#### 2 - Acesse o terminal do miniconda

Após o download, pesquisa por Anaconda Powershell Prompt e abra esse terminal. Depois disso, crie um ambiente separado, por exemplo:

`conda create <nome-desejado>`

Então, acesse ele:

`conda activate <nome-desejado>`

#### 3 - Instale as dependências necessárias para o projeto.

Dentro do terminal, instale as seguintes dependências:

- `pip install numpy`
- `pip install matplotlib`
- `pip install opencv`
- `pip install scikit-image`
- `pip install scikit-learn`
- `pip install split-folders`
- `pip install progress`

#### 4 - Abra o projeto no VS CODE

Após abrir o VS CODE, selecione o `<nome-desejado>` como compilador python.

#### 5 - Selecione uma base de imagens e prepare o dataset

Selecione uma base de dados para o dataset, no projeto, foi usado imagens de covid e imagens sem covid. Após isso, rode o arquivo  `data_spliting`.

#### 6 - Rode o descritor LBP.

Rode o arquivo LBP_Histogram_Extraction para extrair com base no padrão.

#### 7 - Escolha um classificador.

Depois disso, escolha um dos classificadores e execute-o. Isso irá gerar uma imagem através do matplotlib que irá apresentar a acurácia.
