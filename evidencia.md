# Investigação de DNS

## Execução do nslookup
```text
(Cole aqui o texto completo que saiu no seu terminal ao rodar 'nslookup uni9.br')
```

## Execução do ping
```text
(Cole aqui o texto completo que saiu no seu terminal ao rodar 'ping uni9.br')
```

**Conclusão:** O IP retornado pelo nslookup é o mesmo IP respondido pelo comando ping.

## Passo 2: Análise de Requisições (DevTools)

### Requisições Encontradas:
- `organization-new-tasks-indicator` | Método: GET | Status: 304
- `chunk-19722` | Método: GET | Status: 200
- `chunk-14789` | Método: GET | Status: 200
- `57741.css` | Método: GET | Status: 200

### Cabeçalhos de Requisição:
- **Host:** github.com
- **User-Agent:** Mozilla/5.0 (Windows NT 10.0; Win64; x64)
- **Content-Type:** text/css

### Teste de Erro 404:
- `github.com/pagina-que-nao-existe` | Status: 404
