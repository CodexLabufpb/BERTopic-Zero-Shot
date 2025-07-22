# 🧠 Modelagem de Tópicos Zero-Shot com BERTopic

Este repositório contém um notebook Jupyter (`Modelagem_Zero_Shot_BERTopic.ipynb`) projetado para realizar análise de tópicos de forma eficiente e intuitiva, utilizando o poderoso framework BERTopic. A abordagem 'Zero-Shot' permite a identificação de tópicos sem a necessidade de pré-definição de categorias, tornando-o extremamente flexível para diversas aplicações.

## 🌟 Visão Geral

O BERTopic é uma ferramenta de modelagem de tópicos que aproveita embeddings de linguagem (como os gerados por modelos BERT) e técnicas de agrupamento para extrair tópicos de grandes volumes de texto. Este notebook simplifica o processo, guiando o usuário desde a instalação das dependências até a visualização e exportação dos resultados, mesmo para aqueles sem profundo conhecimento em programação ou Machine Learning.

## ✨ Funcionalidades Principais

- **Instalação Automatizada**: Configuração rápida de todas as bibliotecas necessárias (BERTopic, spaCy, pandas, etc.).
- **Configuração Simplificada**: Parâmetros essenciais como caminho do CSV, modelo spaCy, stopwords personalizadas e configurações do BERTopic são facilmente ajustáveis.
- **Pré-processamento de Texto**: Limpeza e lematização de textos para otimizar a qualidade da modelagem de tópicos.
- **Visualizações Interativas**: Geração de gráficos de barras, mapas de distância e matrizes de similaridade para uma compreensão aprofundada dos tópicos.
- **Nuvem de Palavras**: Ferramenta visual para identificar e refinar stopwords, melhorando a relevância dos tópicos.
- **Personalização de Tópicos**: Capacidade de renomear os tópicos identificados para rótulos mais descritivos e significativos.
- **Exportação de Resultados**: Salve os dados classificados em CSV para análise posterior em planilhas e exporte visualizações interativas em HTML.

## 🚀 Como Usar

Para utilizar este notebook, siga os passos abaixo:

1.  **Clone o Repositório**: Faça o download ou clone este repositório para sua máquina local.

2.  **Abra no Google Colab ou Jupyter**: Recomenda-se usar o Google Colab para aproveitar o ambiente pré-configurado e o acesso a GPUs, mas também pode ser executado localmente com Jupyter Notebook.

    -   **Google Colab**: Faça upload do arquivo `Modelagem_Zero_Shot_BERTopic.ipynb` para o Google Colab.
    -   **Jupyter Notebook Local**: Certifique-se de ter Python e Jupyter instalados. Em seguida, execute `jupyter notebook` no diretório do projeto e abra o arquivo `.ipynb`.

3.  **Execute as Células em Ordem**: O notebook é estruturado em seções numeradas. Execute as células sequencialmente, de cima para baixo, clicando no botão ▶ ao lado de cada célula.

    -   **1️⃣ INSTALAR E IMPORTAR DEPENDÊNCIAS**: Execute esta célula primeiro para instalar todas as bibliotecas.
    -   **2️⃣ CONFIGURAÇÕES**: Ajuste os parâmetros conforme as instruções no notebook (caminho do CSV, nome da coluna de texto, stopwords, etc.).
    -   **3️⃣ MODELAGEM DE TÓPICOS**: Esta é a etapa principal onde o modelo BERTopic processa seus dados.
    -   **4️⃣ VISUALIZAÇÕES**: Explore os gráficos interativos para entender os tópicos.
    -   **5️⃣ EXPORTAÇÃO**: Salve seus resultados em CSV ou HTML.

4.  **Ajuste e Refine**: O notebook inclui seções para verificar os resultados e ajustar parâmetros (como `CUSTOM_STOP_WORDS` e `MIN_TOPIC_SIZE`) para otimizar a qualidade dos tópicos. Não hesite em iterar sobre as configurações para obter os melhores resultados para seus dados.

## 🎯 Quando Usar

Este notebook é ideal para:

-   **Análise de Feedback de Clientes**: Entender os principais temas em avaliações de produtos, comentários de serviços ou pesquisas de satisfação.
-   **Pesquisa de Mercado**: Identificar tendências e opiniões em dados de redes sociais, fóruns ou notícias.
-   **Análise de Documentos**: Classificar e organizar grandes coleções de documentos (e-mails, artigos, relatórios) por tema.
-   **Suporte ao Cliente**: Agrupar e priorizar tickets de suporte com base nos problemas mais recorrentes.
-   **Estudos Acadêmicos**: Explorar temas emergentes em artigos científicos ou teses.
-   **Jornalismo de Dados**: Descobrir narrativas e ângulos em grandes volumes de texto jornalístico.

É particularmente útil quando você não tem categorias pré-definidas para seus dados ou quando deseja uma exploração de tópicos mais flexível e baseada em dados.

## 📄 Licença

Este projeto está licenciado sob a licença GNU General Public License. Veja o arquivo `LICENSE` para mais detalhes.
