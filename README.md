# Aula 6 — Simulação de API + Organização de Backend

Projeto desenvolvido na Aula 6 para simular o funcionamento interno de uma API REST e praticar organização de código em camadas.

## Estrutura

```
CODINGII/
│
├── models/
│   └── produtos.py   # Representa os dados do sistema
├── services/
│   └── estoque.py    # Lógica + simulação de rotas e roteamento
└── main.py           # Executa e testa o sistema
```

## Conceitos praticados

- Separação de responsabilidades em camadas (models / services / main)
- Método `to_dict()` para simular formato JSON de uma API
- List comprehension para transformar objetos em dicionários
- Simulação de endpoints REST (GET, POST, PUT, DELETE)
- Simulação de roteamento com a função `executar_rota()`

## Como executar

```bash
python main.py
```

## Desafios propostos

- **Desafio 1** → Impedir quantidade negativa ou igual a zero
- **Desafio 2** → Verificar produto duplicado antes de cadastrar
- **Desafio 3** → Melhorar retorno das funções com respostas estruturadas

```python
{"mensagem": "Produto adicionado", "status": "sucesso"}
```
