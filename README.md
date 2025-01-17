# UABJ_BUS_LOC

Projeto para gestão e localização de ônibus e rotas no campus da UABJ. Este sistema visa facilitar a vida dos estudantes e funcionários, permitindo consultas rápidas sobre horários, itinerários, envia notificações automáticas sobre a localização dos transportes via Telegram usando IA.

---

## 🛠️ Funcionalidades

- Consulta de horários de ônibus no campus.
- Visualização de rotas disponíveis.
- Localização em tempo real dos ônibus.
- Interface amigável e responsiva.

---

## 🚀 Tecnologias Utilizadas

- **Backend**: Python (Flask)
- **Frontend**: HTML, CSS (Tailwind), JavaScript
- **Banco de Dados**: SQLite
- **Outras**:
  - Bibliotecas específicas para geolocalização e mapas.

---

## 🛆 Como Instalar e Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/eukarol/UABJ_BUS_LOC.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd UABJ_BUS_LOC
   ```
3. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
5. Inicie o servidor:
   ```bash
   python app.py
   ```
6. Acesse o sistema no navegador:
   ```
   http://127.0.0.1:5000
   ```

---

## 📚 Estrutura do Projeto

```
UABJ_BUS_LOC/
├── app.py                # Arquivo principal do backend
├── requirements.txt      # Dependências do projeto
├── LICENSE               # Licença do projeto
├── README.md             # Documentação
├── static/               # Arquivos estáticos (CSS, JS, imagens)
│   ├── style.css
│   └── script.js
├── templates/            # Templates HTML
│   └── index.html
```

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar **pull requests** com melhorias ou sugestões.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

