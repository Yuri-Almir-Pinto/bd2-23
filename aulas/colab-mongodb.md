# Configuração Mongodb + Colab

```python
from google.colab import drive

drive.mount('/content/gdrive')

```

```python

# criar a pasta "data" no Drive para armazenar o arquivo csv.
!mkdir /content/gdrive/MyDrive/data

# verificar se o arquivo foi baixado:
!ls /content/gdrive/MyDrive/data

```

```python
# instalação do mongodb
!apt install mongodb >log

# iniciar o serviço
!service mongodb start

```

