# Trabalhando com Esteiras de CI/CD na Prática

Este curso prático ensina a **projetar**, **implementar** e **manter** pipelines de **CI/CD** (Integração Contínua e Entrega Contínua) para acelerar e elevar a qualidade do ciclo de vida de software.  
Você vai aprender, na prática, a configurar desde etapas básicas de build/test até deploy automatizado em ambientes reais, seguindo as melhores práticas de engenharia de confiabilidade.

---

## 🎯 Objetivos de Aprendizagem

- **Automatizar** builds e testes de unidades e integração  
- **Versionar** artefatos e coordenar múltiplos ambientes  
- **Configurar** triggers de pipeline (push, pull requests, tags)  
- **Garantir** segurança e qualidade em cada etapa  
- **Fazer deploy** automático em servidores ou nuvem  
- **Monitorar** estado e performance das pipelines  

---

## 🗂 Conteúdo Programático

1. **Introdução ao CI/CD**  
   - Conceitos e benefícios  
   - Fluxos de trabalho comuns  

2. **Ferramentas e Ecossistema**  
   - GitHub Actions  
   - Jenkins, GitLab CI, Azure DevOps  
   - Docker e repositórios de artefatos  

3. **Construção de Pipelines**  
   - Sintaxe YAML e infraestrutura como código  
   - Configuração de runners e agentes  

4. **Fase de Build & Test**  
   - Compilação automática  
   - Execução de testes unitários e de integração  
   - Métricas de cobertura e qualidade  

5. **Entrega e Deploy Contínuo**  
   - Publicação de pacotes  
   - Estratégias de deploy (blue/green, canary)  
   - Rollbacks automatizados  

6. **Segurança e Governança**  
   - Scans de dependências  
   - Gerenciamento de segredos  

7. **Monitoramento e Observabilidade**  
   - Logs e dashboards  
   - Alertas e auto-recuperação  

8. **Boas Práticas e Otimizações**  
   - Reuso de jobs e templates  
   - Paralelismo e caching  

---

## 🛠️ Ferramentas Usadas

- **GitHub Actions** (checkout, setup-dotnet, build, test, upload-artifact)  
- **Docker** (imagens de build e runtime)  
- **Azure DevOps** (opcional para comparativo)  
- **Linters** e **scanners** de segurança  

---

## ✅ Conquistas

- Pipeline CI/CD completo em ambiente Windows-Hosted  
- Automação de build → test → deploy  
- Publicação de artefatos versionados  
- Relatórios de cobertura e qualidade integrados  
- Deploy automatizado com rollback seguro  

---

## 📂 Repositório de Exemplo

```bash
git clone https://github.com/joana-nishimura-narazaki/ci-cd-dio.git
cd ci-cd-dio
