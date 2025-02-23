# Classificação de Clientes - Machine Learning

Este repositório contém um projeto de aprendizado de máquina para classificação de clientes baseado em dados de cartões de crédito. O sistema permite escolher entre três técnicas de classificação:

- **Rede Neural**
- **Perceptron**
- **Árvore de Decisão**

## Estrutura do Projeto

- `menu.py` - Interface de seleção de técnicas de aprendizado.
- `func.py` - Implementação dos modelos de classificação.
- `dados.py` - Carregamento e divisão dos dados.
- `default of credit card clients.xls` - Conjunto de dados (não incluído no repositório por questões de direitos autorais).

## Requisitos

Antes de rodar o projeto, instale as dependências necessárias:

```bash
pip install -r requirements.txt
```

**Bibliotecas utilizadas:**
- `pandas`
- `scikit-learn`

## Como Executar

1. Certifique-se de que o arquivo `default of credit card clients.xls` está na pasta do projeto.
2. Execute o script principal:

```bash
python menu.py
```
3. Escolha a técnica desejada no menu interativo.

## Funcionalidades

- **Rede Neural:** Implementada com `MLPClassifier`.
- **Perceptron:** Usa `Perceptron` com normalização dos dados.
- **Árvore de Decisão:** Baseada em `DecisionTreeClassifier`.
- Exibição de métricas como acurácia e relatório de classificação.

## Exemplo de Saída

```
Escolha uma técnica de aprendizado:
1. Rede Neural
2. Perceptron
3. Árvore de Decisão
4. Sair
Digite sua escolha: 1

Acurácia do modelo de rede neural: 0.82
Relatório de classificação:
               precision    recall  f1-score   support

           0       0.85      0.80      0.82      5000
           1       0.78      0.83      0.80      3000

    accuracy                           0.82      8000
   macro avg       0.81      0.82      0.81      8000
weighted avg       0.82      0.82      0.82      8000
```

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## Licença

Este projeto está licenciado sob a MIT License.

