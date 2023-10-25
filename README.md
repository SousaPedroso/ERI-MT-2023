**O link para o artigo será divulgado em breve.**

Existem dois códigos em jupyter notebook, o "Cross-dataset Fair Evaluation to evaluate COVID-19 chest X-rays models.ipynb" possui todas as instruções e processos definidos para que seja possível obter os resultados. Aqui também está como são obtidos os conjuntos de dados utilizados. O notebook separa em seções os processos definidos. Ao executar, fique atento dentro da seção "COHEN dataset" às duas subseções "Baseline" e "Separação de visualizações (PA, AP, AP Supine e L)", que correspondem a 1º e 2º iterações definidas no artigo. Nos notebooks, caso haja espaço em disco para todas as imagens ou já tenha todo o conjunto baixado, fique a vontae para ignorar as etapas de coleta dos dados. No arquivo "Visualize_Results" são demonstradas as formas de avaliação dos resultados, por reconhecimento de base de dados e por classe. Cada notebook está separado por escopo, fique atento a executar cada conjunto de instruções por baseline, cross-validation, metadados ou metadados + cross-validation.

Os trabalhos foram realizados dentro do Google Colaboratory, atente-se a remover as importações e referenciações na primeira celula de código de cada notebook. As dependências necessárias para a execução dos códigos estão no arquivo "requirements.txt", puxadas diretamente do ambiente do colab. Para instalar as dependências, execute o comando abaixo no terminal:

```bash
pip install -r requirements.txt
```

Caso haja ainda assim dúvidas ou encontre bugs, não hesite em abrir uma [issue](https://github.com/SousaPedroso/ERI-MT-2023/issues)!