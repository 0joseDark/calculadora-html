# calculadora-html
### Passo 1: Instalar Flask
Primeiro, precisamos instalar o Flask. Se você ainda não o tem instalado, pode fazer isso usando o pip:

```sh
pip install flask
```

### Passo 2: Estrutura do Projeto

```
calculator/
│
├── static/
│   ├── styles.css
│   └── script.js
│
├── templates/
│   └── index.html
│
├── app.py
```

### Passo 3: Criar o Servidor Flask (`app.py`)

Na raiz do projeto

### Passo 4: Criar o Template HTML (`index.html`)

Na pasta `templates`

### Passo 5: Criar o CSS (`styles.css`)

Na pasta `static`

### Passo 6: Criar o JavaScript (`script.js`)

Na pasta `static`

### Explicação

1. **Servidor Flask (`app.py`):**
   - Importamos o Flask e criamos uma instância do aplicativo.
   - Definimos uma rota (`/`) que renderiza o template `index.html`.
   - O servidor é iniciado em modo de depuração (`debug=True`).

2. **Template HTML (`index.html`):**
   - Usamos o Jinja2 (motor de templates do Flask) para incluir os arquivos CSS e JavaScript.
   - Definimos a estrutura da calculadora com um campo de entrada (`input`) e botões.

3. **CSS (`styles.css`):**
   - Estilizamos a calculadora para que tenha uma aparência agradável.
   - Usamos grid layout para organizar os botões.

4. **JavaScript (`script.js`):**
   - Definimos funções para limpar o display, deletar o último caractere, adicionar caracteres ao display e calcular o resultado da expressão.

### Executar o Projeto

Para executar o projeto, navegue até o diretório do projeto no terminal e execute o seguinte comando:

```sh
python app.py
```

Abra o navegador e acesse `http://127.0.0.1:5000/` para ver a calculadora em funcionamento.
