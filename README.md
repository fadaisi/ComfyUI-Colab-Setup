# 🚀 ComfyUI Cloud Infrastructure: Afrofuturism & Innovation

Este repositório documenta a implementação de uma infraestrutura escalável para IA Generativa, utilizando **ComfyUI** rodando em instâncias de nuvem. O foco deste projeto é unir a eficiência técnica da ciência de dados com a exploração estética do Afrofuturismo e Surrealismo.

## 📋 Sobre o Projeto
Para superar limitações de hardware local (reduzindo o tempo de renderização de 8 minutos para 40 segundos), desenvolvi um ambiente no **Google Colab** que gerencia workflows complexos de Stable Diffusion XL.

### O que este setup resolve:
* **Escalabilidade:** Permite rodar modelos pesados (SDXL) em GPUs de alto desempenho (Tesla T4).
* **Gestão de Dados:** Integração via links simbólicos com o Google Drive, evitando downloads repetitivos de modelos (Checkpoints/LoRAs).
* **Acesso Seguro:** Implementação de túneis via **Cloudflare** para exposição da interface local para a web sem necessidade de portas abertas.

---

## 🛠️ Tecnologias e Competências
* **Python:** Scripting para automação do servidor e gestão de processos.
* **Linux/Bash:** Manipulação de diretórios, gestão de permissões e processos (`pkill`, `ln -s`, `mkdir`).
* **Cloud Computing:** Orquestração de ambiente no Google Colab.
* **Generative AI:** Arquitetura de nós no ComfyUI e otimização de modelos Juggernaut XL.

---

## 🖼️ Resultados (Creative Research)
Abaixo, um exemplo de renderização gerada com este setup em apenas **40 segundos**:

<p align="center">
  <img src="samples/primeira_geracao.jpg" width="400" alt="Resultado Afrofuturista">
</p>

---

## 🚀 Como utilizar
1. Suba o arquivo `comfyui_setup.ipynb` para o seu Google Colab.
2. Organize suas pastas no Drive conforme a seção de `# Setup e Modelos`.
3. Execute as células em ordem para liberar o link do túnel Cloudflare.

---

**Janice Mascarenhas (Fadaisi)** *Junior Developer | Data Analyst | Innovation Specialist* [Meu LinkedIn](SEU_LINK_DO_LINKEDIN_AQUI) | [Meu Portfólio](SEU_PORTFOLIO_OU_SITE_AQUI)
