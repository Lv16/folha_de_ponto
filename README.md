# 🕒 Sistema de Folha de Ponto

Projeto desenvolvido para controle e registro de ponto eletrônico de colaboradores. A aplicação permite que os usuários registrem horários e acompanhem sua jornada de trabalho de forma prática e organizada.

## 🚀 Tecnologias Utilizadas

- **HTML5** – Estrutura semântica das páginas
- **CSS3** – Estilização com foco em usabilidade e layout moderno
- **JavaScript** – Lógica de interface e validações no front-end
- **Django** – Backend em Python para gestão dos dados (em colaboração)

## 👨‍💻 Autores

- **Front-End:** Desenvolvido por Lohran Victor em conjunto com Gabriel de Andrade
- **Back-End:** Projeto em conjunto com Gabriel de Andrade

## 🎯 Funcionalidades

- Registro de horários de entrada, saída e intervalos
- Validação de campos obrigatórios
- Preenchimento dos campos automáticos
- Interface moderna (desktop-first)
- Integração com banco de dados via Django
- Geração de relatórios/exportação de dados (se aplicável)

## 🛠️ Como executar localmente

```bash
# Clone o repositório
git clone https://github.com/Lv16/folha_de_ponto.git
cd folha-de-ponto

# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate  # no Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Rode o servidor Django
python manage.py runserver

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
