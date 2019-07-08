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
nano grepc.py

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
