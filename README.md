# Análise de Dados da Guerra na Ucrânia

## Como Executar no Google Colab

### 📁 **Preparar os Arquivos** 

1. Crie uma pasta no seu Google Drive:
   ```
   MyDrive/[CAMINHO]/Datasets/
   ```

2. Baixe os 2 arquivos CSV do dataset e coloque no caminho acima no seu Google Drive:
   - `russia_losses_equipment.csv`
   - `russia_losses_personnel.csv` 

3. Modifique a linha a seguir:
   ```python
   # Montagem do Google Drive
   from google.colab import drive
   drive.mount('/content/drive')
   caminho = '/content/drive/MyDrive/[CAMINHO]/Datasets/'
   ```

**Dataset:** https://www.kaggle.com/datasets/piterfm/2022-ukraine-russian-war