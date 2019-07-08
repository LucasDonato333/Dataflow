# Dataflow

Execute para clonar o projeto.
```linux
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
```
Entre na pasta
```linux
cd training-data-analyst/courses/data_analysis/lab2/python
```
Execute o pacote de instalação
```linux
sudo ./install_packages.sh
```
Instale o módulo apache_beam
```linux
python -m pip install apache_beam
```
Execute o programa indicado
```linux
python grep.py
```
Execute
```linux
gsutil cp ../javahelp/src/main/java/com/google/cloud/training/dataanalyst/javahelp/*.java gs://multic-carga-manual/javahelp
```
Entre na pasta.
```linux
cd ~/training-data-analyst/courses/data_analysis/lab2/python
```
Edite o arquivo
```linux
nano grepc.py
```
```
CTRL-x - Sai do editor. Se você estiver no meio da edição de um arquivo, o processo de saída irá perguntar se você quer salvar seu trabalho.
CTRL-R - Ler um arquivo em seu arquivo de trabalho atual. Isso permite que você adicione o texto de outro arquivo enquanto trabalha dentro de um novo arquivo.
CTRL-c - Mostra a posição atual do cursor.
CTRL-k - 'recorta' o texto.
CTRL-U - 'cola' o texto.
CTRL S - Salva o arquivo e continua trabalhando.
CTRL-T - verifica a ortografia do seu texto.
CTRL-w - faz uma busca no texto.
CTRL-a- leva o cursor para o início da linha.
CTRL-e - leva o cursor para o fim da linha.
CTRL-g - mostra a ajuda do Nano.
```
Mude o "bucket" e "project" para:
```
bucket = 'multic-carga-manual'
project = 'sas-corp-multicanalidade'
```
Execute o arquivo python
```linux
python grepc.py
```

[Referencia](https://codelabs.developers.google.com/codelabs/cpb101-simple-dataflow-py/index.html?index=..%2F..next17#0 "Dataflow")
