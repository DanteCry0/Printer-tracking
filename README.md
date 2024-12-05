# Printer-tracking  
## Monitoramento de Impressões  

Este projeto é um sistema simples para monitorar e registrar informações sobre as impressões realizadas em impressoras conectadas ao sistema. Ele registra detalhes como o nome do arquivo impresso, o número de páginas, os horários de início e término da impressão e salva esses dados em um banco de dados.

---

## 🌐 **Idioma**  
Escolha o idioma do projeto:  
- [🇧🇷 Português - Brasil](#🇧🇷-português---brasil)  
- [🇬🇧 English - United Kingdom](#🇬🇧-english---united-kingdom)  

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