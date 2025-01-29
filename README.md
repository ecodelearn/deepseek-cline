# deepseek-cline

## DeepSeek-R1:8b Model Configuration
---
crie um arquivo deepseek-r18b com este conteudo:
 ```bash
FROM deepseek-r1:8b
PARAMETER num_ctx 32768
```

## Model Configuration
```bash
ollama create -f deepseek-r18b deepseek-r1-new:8b
```
