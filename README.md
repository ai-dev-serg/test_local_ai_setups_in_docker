# test_local_ai_setups_in_docker
This repo needs to save all tests with local ai setups in docker tested on RTX 3090 24 Gb

- Run models on ollama and vLLM
- Web ui interface is based on open-webui
- Other tool: n8n




To run n8n docker with gpu activation "docker compose --profile gpu-nvidia up" and use ollama in this case "docker compose exec ollama-gpu ollama list" where ollama-gpu selected profile to run docker