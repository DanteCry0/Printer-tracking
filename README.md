# Printer-tracking
# Monitoramento de Impressões

Este projeto é um sistema simples para monitorar e registrar informações sobre as impressões realizadas em impressoras conectadas ao sistema. Ele registra detalhes como o nome do arquivo impresso, o número de páginas, os horários de início e término da impressão e salva esses dados em um banco de dados.

---

## 🌐 **Idioma**
Escolha o idioma do projeto:
- [🇧🇷 Português - Brasil](#português---brasil)
- [🇬🇧 English - United Kingdom](#english---united-kingdom)

---

# 🇧🇷 **Português - Brasil**

## **Funcionalidades**

- Monitora automaticamente as impressoras configuradas no sistema.
- Registra:
  - Nome do arquivo impresso.
  - Quantidade de páginas.
  - Horário de início e fim da impressão.
- Salva os dados em um banco de dados SQLite.
- Interface web simples para visualização dos registros.
- Exportação de registros (planejado para versões futuras).

---

## **Requisitos**

- Python 3.8 ou superior.
- Sistema operacional compatível com a biblioteca **win32print** (somente Windows, por enquanto).

### **Bibliotecas Necessárias**
As dependências do projeto estão listadas no arquivo `requirements.txt`. Para instalá-las, use o comando:

```bash
pip install -r requirements.txt

Estrutura do Projeto

monitoramento-de-impressoes/
│
├── app.py              # Código principal do monitoramento.
├── models.py           # Configuração do banco de dados com SQLAlchemy.
├── requirements.txt    # Lista de dependências do projeto.
├── print_jobs.db       # Banco de dados SQLite (gerado automaticamente).
└── README.md           # Documentação do projeto.


---

Configuração e Execução

1. Clonar o repositório:

git clone https://github.com/seu-usuario/monitoramento-de-impressoes.git
cd monitoramento-de-impressoes


2. Criar um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows


3. Instalar as dependências:

pip install -r requirements.txt


4. Executar o monitoramento:

python app.py


5. Acessar a interface web:

Abra o navegador e acesse: http://127.0.0.1:5000/print_jobs





---

Melhorias Futuras

Compatibilidade com outros sistemas operacionais (Linux/macOS).

Suporte a múltiplas impressoras.

Exportação de registros para formatos CSV ou Excel.

Interface gráfica aprimorada.



---

Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.


---

Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações.


---

🇬🇧 English - United Kingdom

Features

Automatically monitors printers configured in the system.

Logs:

Printed file name.

Number of pages.

Start and end times of the print job.


Saves data to a SQLite database.

Simple web interface for record visualization.

Exporting records (planned for future releases).



---

Requirements

Python 3.8 or higher.

Operating system compatible with the win32print library (Windows only for now).


Required Libraries

The project's dependencies are listed in the requirements.txt file. To install them, use the command:

pip install -r requirements.txt

