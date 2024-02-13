# Data Project Starter Kit

### Instalação e Configuração

1. Clone o repositório:

```bash
git clone https://github.com/lvgalvao/dataprojectstarterkit.git
cd dataprojectstarterkit
```

2. Configure a versão correta do Python com `pyenv`:

```bash
pyenv install 3.11.5
pyenv local 3.11.5
```

3. Configurar poetry para Python version 3.11.5 e ative o ambiente virtual:

```bash
poetry env use 3.11.5
poetry shell
```

4. Instale as dependencias do projeto:

```bash
poetry install
```

5. Execute os testes para garantir que tudo está funcionando como esperado:

```bash
task test
```

6. Execute o comando para ver a documentação do projeto:

```bash
task doc
```

7. Execute o comando de execucão da pipeline para realizar a ETL:

```bash
task run
```

8. Verifique na pasta data/output se o arquivo foi gerado corretamente.

### Arquitetura
![Arquitetura](/docs/static/fluxo.png)

- Confira a documentação aqui: 

### Tecnologias e Bibliotecas
- Python
- Pyenv
- Poetry
- Pandas
- Faker
- Mkdocs


---
---
---

# Data Project Starter Kit

### Installation and Configuration

1. Clone the repository:
```bash
git clone https://github.com/lvgalvao/dataprojectstarterkit.git
cd dataprojectstarterkit
```

2. Configure the correct Python version with `pyenv`:
```bash
pyenv install 3.11.5
pyenv local 3.11.5
```

3. Set up poetry for Python version 3.11.5 and activate the virtual environment:
```bash
poetry env use 3.11.5
poetry shell
```

4. Install project dependencies:
```bash
poetry install
```

5. Run tests to ensure everything is functioning as expected:
```bash
task test
```

6. Run the command to view the project documentation:
```bash
task doc
```

7. Run the pipeline execution command to perform ETL:
```bash
task run
```

8. Check in the data/output folder if the file was generated correctly.

### Architecture

![Architecture](/docs/static/fluxo.png)

- Check the documentation here: 

### Technologies and Libraries

- Python
- Pyenv
- Poetry
- Pandas
- Faker
- Mkdocs