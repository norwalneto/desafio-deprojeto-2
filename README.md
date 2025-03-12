# desafio-deprojeto-2

# Projeto Desafio DIO - OCR com Azure OpenAI e Content Filters

## Introdução

Neste projeto, desenvolvi uma aplicação de reconhecimento de texto (OCR) utilizando os conceitos abordados durante o conteúdo da DIO. O projeto demonstra como integrar ferramentas de **Azure OpenAI**, **Microsoft Copilot** e **Content Filters** para extrair texto de imagens e tratar os resultados de forma inteligente.

## Estrutura do Projeto

- **inputs/**: Pasta contendo as imagens utilizadas para o reconhecimento de texto.
- **output/**: Pasta onde foram salvos os resultados do OCR, com os textos extraídos de cada imagem.
- **README.md**: Este arquivo, que descreve o processo, apresenta alguns prints e compartilha insights e possibilidades de futuras melhorias.

## Passo a Passo do Processo

1. **Preparação do Ambiente:**
   - Criação do repositório no GitHub com o nome `meu-projeto-ocr-dio`.
   - Organização das pastas `inputs` e `output` para armazenar as imagens e os resultados.

2. **Captura das Imagens:**
   - Utilizei imagens contendo texto para testar a aplicação.
   - As imagens foram salvas na pasta `inputs`.

3. **Processamento e Reconhecimento de Texto (OCR):**
   - Integrei o serviço de OCR utilizando a API do Azure OpenAI (ou outro serviço de OCR disponível).
   - O código realizou a extração de texto das imagens e salvou os resultados na pasta `output`.
   - Durante esse processo, utilizei filtros de conteúdo para melhorar a qualidade dos resultados.

4. **Análise e Tratamento dos Dados:**
   - Realizei ajustes finos para garantir que o reconhecimento estivesse preciso.
   - Alguns prints do processo foram capturados para ilustrar a execução e os resultados obtidos.

## Prints do Processo

### Exemplo de execução do OCR:
![Print do OCR](https://github.com/norwalneto/desafio-deprojeto-2/blob/main/inputs/images.png)

### Resultado do reconhecimento de texto:
📄 [`output/imagem.txt`](https://github.com/norwalneto/desafio-deprojeto-2/blob/main/output/imagem.txt)


## Insights e Possibilidades

- **Integração com Azure OpenAI:**  
  Aprendi como integrar serviços de inteligência artificial para enriquecer a extração de dados e melhorar a precisão do reconhecimento.
  
- **Utilização de Content Filters:**  
  Os filtros de conteúdo possibilitam a melhoria dos resultados, removendo ruídos e ajustando o output do OCR.
  
- **Microsoft Copilot:**  
  Explorando a generative AI com o Microsoft Copilot, pude automatizar parte do processo de revisão e validação dos resultados.
  
- **Futuras Expansões:**
  - Desenvolver uma interface web para exibir as imagens e os textos reconhecidos.
  - Implementar um pipeline de processamento mais robusto com logs e tratamento de erros.
  - Ampliar o uso de AI para incluir tradução ou análise semântica do texto extraído.

## Conclusão

Este projeto não apenas reforça a importância da organização e da documentação dos processos, mas também demonstra como utilizar tecnologias modernas para resolver problemas práticos. A integração com serviços da Azure e o uso de ferramentas de AI abrem diversas possibilidades para aprimorar a experiência de reconhecimento de texto e enriquecer o portfólio de projetos.

## Links Importantes

- [Explore generative AI with Microsoft Copilot](https://www.microsoft.com/pt-br/ai/microsoft-copilot)
- [Explore Azure OpenAI](https://azure.microsoft.com/pt-br/services/openai/)
- [Explore content filters in Azure OpenAI](https://learn.microsoft.com/pt-br/azure/cognitive-services/openai/concepts/content-filters)

---

Esse exemplo serve como ponto de partida. Sinta-se à vontade para personalizar o conteúdo, incluir mais prints e detalhar os passos conforme o seu processo e aprendizados. Quando estiver satisfeito com o resultado, basta compartilhar o link do repositório na plataforma DIO através do botão "entregar projeto".
