# Configuração do Modelo DeepSeek-R1:8b / DeepSeek-R1:8b Model Configuration

This document provides instructions for configuring the DeepSeek-R1:8b model.

## 1. Create the `deepseek-r18b` file

**Português:**

Crie um arquivo chamado `deepseek-r18b` com o seguinte conteúdo:

```bash
FROM deepseek-r1:8b
PARAMETER num_ctx 32768
```

**English:**

Create a file named `deepseek-r18b` with the following content:

```bash
FROM deepseek-r1:8b
PARAMETER num_ctx 32768
```

## 2. Model Configuration

**Português:**

Execute o seguinte comando para configurar o modelo:

```bash
ollama create -f deepseek-r18b deepseek-r1-new:8b
```

**English:**

Execute the following command to configure the model:

```bash
ollama create -f deepseek-r18b deepseek-r1-new:8b
```
