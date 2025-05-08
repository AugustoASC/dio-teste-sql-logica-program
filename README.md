# 🚀 DIO-Desafio-SQL

**Associando Conceitos de Comandos SQL com Lógica de Programação**

## 📘 Descrição

Este projeto foi desenvolvido como parte de um desafio da [Digital Innovation One (DIO)](https://www.dio.me/), com o objetivo de simular um sistema de suporte técnico que reconhece comandos SQL básicos e associa cada um deles à sua funcionalidade principal. Ele demonstra como conceitos simples de lógica de programação podem ser usados para treinar sistemas de suporte.

---

## 🧐 Conceito

O programa utiliza uma função que **recebe um comando SQL** (como `SELECT`, `INSERT`, `UPDATE` ou `DELETE`) e retorna uma **descrição clara e objetiva** sobre sua finalidade.

---

## 💻 Exemplo de Código

```python
# Recebe a entrada do usuário
entrada = input()

# Função que descreve o comando SQL
def descrever_comando_sql(comando):
    if comando == "SELECT":
        return "Usado para consultar dados em uma tabela"
    elif comando == "INSERT":
        return "Usado para inserir novos dados em uma tabela"
    elif comando == "UPDATE":
        return "Usado para atualizar registros existentes em uma tabela"
    elif comando == "DELETE":
        return "Usado para deletar registros de uma tabela"
    else:
        return "Comando SQL desconhecido"

# Imprime a descrição correspondente
print(descrever_comando_sql(entrada))
```

---

## 📥 Entrada Esperada

O usuário deve fornecer um dos seguintes comandos SQL via terminal/interação:

```
SELECT
INSERT
UPDATE
DELETE
```

---

## 📤 Saída Esperada

A descrição do comando SQL fornecido:

* `"SELECT"` → `Usado para consultar dados em uma tabela`
* `"INSERT"` → `Usado para inserir novos dados em uma tabela`
* `"UPDATE"` → `Usado para atualizar registros existentes em uma tabela`
* `"DELETE"` → `Usado para deletar registros de uma tabela`
* Qualquer outro → `Comando SQL desconhecido`

---

## 🧪 Teste Interativo

Execute o script em um terminal Python com:

```bash
python desafio_sql.py
```

Digite um comando como `SELECT` e observe a resposta descritiva no terminal!

---

## ✨ Melhorias Futuras

* 🔠 Suporte a letras minúsculas e espaços extras (`.strip().upper()`)
* 📚 Suporte a mais comandos SQL (ex: `CREATE`, `DROP`, `ALTER`, etc.)
* 🌐 Interface web simples com Flask ou Streamlit

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues ou pull requests com melhorias e sugestões. Este projeto é educativo e toda colaboração é bem-vinda!
