# API de Chamados de Suporte

**Estudante:** MARIA FERNANDA SOUSA SILVA
**Mtrícula:** 2025019580

## Objetivo
Estrutura inicial de uma API de chamados de suporte feita com Python e Flask,
usando uv para gerenciar o ambiente e as dependências. Nesta etapa existe
apenas a rota inicial, que confirma que a API está funcionando.

## Instalação das dependências
```bash
uv sync --locked
```

## Como executar
```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Como acessar a rota inicial
Com a aplicação em execução, acesse `http://localhost:5000/` no navegador
ou use:

```bash
curl -i http://localhost:5000/
```

**Resposta esperada:** status `200` e corpo JSON:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```