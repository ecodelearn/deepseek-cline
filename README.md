# deepseek-cline

## DeepSeek-R1:8b Model Configuration
---
Crie um arquivo deepseek-r18b com este conteudo:
 ```bash
FROM deepseek-r1:8b
PARAMETER num_ctx 32768
```

## Model Configuration
Abra a janela do terminal no vscode onde está o arquivo já com o modelo instalado no ollama e execute o comando abaixo.
```bash
ollama create -f deepseek-r18b deepseek-r1-new:8b
```
Agora vá no Cline ou Roo-Code e selecione o provedor Ollama e o modelo deepseek-r1-new:8b.
