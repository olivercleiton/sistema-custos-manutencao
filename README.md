# Sistema de Controle de Custos de Manutenção

Sistema web para gerenciar custos, ordens de serviço e histórico de manutenção de motos.

## 🚀 Tecnologias

- Python + Flask
- MySQL
- HTML/CSS/JS
- Docker (em breve)

## 📦 Como executar (local)

```bash
# Clone
git clone https://github.com/olivercleiton/sistema-custos-manutencao.git
cd sistema-custos-manutencao

# Crie ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instale dependências
pip install -r requirements.txt

# Configure variáveis de ambiente (crie um .env)
# DB_HOST, DB_USER, DB_PASSWORD, DB_NAME

# Execute
python app.py
