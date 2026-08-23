# Auditoria de Segurança da Informação e Gestão de Riscos de TI – Setor de RH

> Avaliação prática de maturidade de segurança, mapeamento de ativos críticos e estruturação de planos de mitigação alinhados à ISO 27002 e LGPD em contexto empresarial real.

**Status:** Concluído  
**Natureza:** Acadêmico Aplicado em Contexto Empresarial Real (com dados sanitizados para portfólio)

---

## 🔒 Nota de Confidencialidade

*Tratando-se de uma auditoria baseada em um contexto corporativo real, todos os dados sensíveis, nomes da organização, endereços IP, topologias de rede específicas, CVEs exatos e vulnerabilidades identificadas foram rigorosamente anonimizados, sanitizados ou substituídos por dados fictícios neste repositório. O objetivo é demonstrar a metodologia e a capacidade analítica sem comprometer a segurança ou a confidencialidade da organização real.*

---

## Visão Geral

Este projeto consistiu na execução de uma auditoria técnica e processual de Segurança da Informação focada no departamento de Recursos Humanos de uma organização industrial de grande porte. O trabalho avaliou a maturidade dos controles de segurança, mapeou ativos críticos e identificou riscos residuais, culminando na entrega de um plano de mitigação estruturado e um programa de conscientização, alinhados às melhores práticas da ISO/IEC 27002 e da LGPD.

## Contexto e Problema

A organização necessitava de maior visibilidade sobre sua superfície de ataque e a efetividade real dos controles de segurança aplicados ao tratamento de dados pessoais sensíveis de milhares de colaboradores. Havia uma lacuna entre a conformidade documental e a postura técnica real (ex: ausência de controles de endpoint e exposição de serviços administrativos), exigindo uma avaliação que unisse a auditoria de processos a testes técnicos controlados para identificar vulnerabilidades de forma precisa.

## Objetivos

- Mapear, classificar e valorar ativos críticos de informação do setor de RH (Dados Pessoais, Folha de Pagamento, Contratos).
- Avaliar a maturidade dos controles de segurança da informação com base na ISO 27002.
- Identificar vulnerabilidades técnicas e riscos residuais por meio de reconhecimento de rede e análise controlada.
- Propor um plano estratégico de mitigação e um programa de conscientização de colaboradores.

## Escopo

**Inclusões:** Infraestrutura de TI corporativa, processos críticos de RH (folha de pagamento, recrutamento, gestão de contratos), reconhecimento de rede (footprinting) e auditoria de conformidade.  
**Exclusões:** Sistemas legados de manufatura isolados da rede corporativa (OT) e testes destrutivos (ex: DoS).  
**Limites:** Projeto executado com prazo acadêmico definido, sob premissa de análise em ambiente controlado e com dados sanitizados para fins de portfólio.

## Papel e Responsabilidades

Liderança técnica e metodológica do trabalho, abrangendo o levantamento e valoração de ativos, execução da avaliação de riscos (qualitativa e quantitativa), condução da análise de vulnerabilidades com ferramentas de varredura e elaboração dos relatórios técnico e executivo para a gestão.

## Metodologia e Abordagem

O projeto foi conduzido em fases estruturadas:
1. **Levantamento e Valoração de Ativos:** Mapeamento de ativos de informação e classificação baseada nos critérios de Disponibilidade, Integridade e Confidencialidade (D-I-C).
2. **Avaliação de Riscos:** Aplicação de metodologia qualitativa e quantitativa para construção do Mapa de Calor (Heat Map) de riscos.
3. **Auditoria de Conformidade:** Verificação da aderência dos controles implementados em relação aos requisitos da ISO/IEC 27002 e LGPD.
4. **Validação Técnica:** Execução de reconhecimento de rede (footprinting), varredura de portas (NMAP) e análise de configurações de hardening.
5. **Simulação de Incidentes:** Modelagem de cenários de ataque (ex: Ransomware via typosquatting e exploração de SSRF) para testar a resposta e as lacunas de controle.
6. **Tratamento do Risco:** Elaboração do plano de melhoria contínua e definição de ações corretivas.

## Frameworks e Boas Práticas

- **ISO/IEC 27002:** Utilizado como lista de verificação base para a auditoria de conformidade dos controles de segurança da informação (foco em controles de acesso, gestão de vulnerabilidades e conscientização).
- **LGPD (Lei Geral de Proteção de Dados):** Aplicado como requisito normativo para a classificação e proteção de dados pessoais sensíveis de colaboradores.
- **Princípio do Menor Privilégio:** Diretriz central aplicada na análise de acessos e nas recomendações de hardening de servidores e serviços de rede.

## Tecnologias e Ferramentas

- **Análise e Reconhecimento:** NMAP, Shodan, MxToolbox, Pentest-Tools (utilizadas em ambiente controlado/acadêmico para fins de diagnóstico).
- **Documentação e Modelagem:** Ferramentas de diagramação de topologia, planilhas de matriz de risco e valoração de ativos.

## Solução e Arquitetura

A solução entregue foi um modelo de avaliação de risco híbrido. Ele combinou a auditoria documental (baseada na ISO 27002) com a validação técnica (varredura de rede e análise de vulnerabilidades). Os resultados foram consolidados em um Mapa de Calor (Heat Map) visual, que traduziu vulnerabilidades técnicas complexas (como exposição de portas administrativas e falhas de configuração em servidores web) em níveis de risco (Baixo, Médio, Alto, Crítico) compreensíveis para a tomada de decisão da alta gestão.

## Evidências e Entregáveis

- **Inventário e Valoração de Ativos:** Documento de classificação de ativos críticos do RH com pontuação D-I-C (ex: Dados Pessoais classificados com valor máximo de impacto).
- **Mapa de Calor (Heat Map):** Matriz de riscos qualitativa e quantitativa, posicionando ativos como "Dados Pessoais" no quadrante de Risco Alto.
- **Relatório Técnico de Auditoria (Sanitizado):** Detalhamento das vulnerabilidades identificadas (ex: ausência de EDR, exposição de serviços SSH/HTTP), evidências das varreduras e análise de hardening.
- **Plano de Melhoria e Mitigação:** Plano de ação estruturado com recomendações para atualização de servidores, implementação de controles de endpoint e programa de conscientização contra phishing.

*[Espaço reservado para inserção de imagens do Heat Map sanitizado, trechos do relatório técnico anonimizado ou diagrama de topologia de laboratório]*

## Resultados e Validação

- Mapeamento completo da superfície de ataque e dos ativos críticos de RH dentro do escopo definido.
- Identificação de lacunas críticas de governança (ex: inexistência de política de segurança cibernética formalizada e falta de proteção de endpoints).
- Proposição de um plano de tratamento estruturado para mitigação das vulnerabilidades críticas mapeadas durante o estudo, incluindo a correção de falhas de configuração em servidores web e a restrição de acessos administrativos.

## Aprendizados e Limitações

- **Aprendizado:** A combinação de auditoria de conformidade (ISO 27002) com testes técnicos controlados fornece uma visão muito mais realista e acionável do risco residual do que a auditoria puramente documental. A simulação de incidentes (como typosquatting) demonstrou a eficácia prática de validar controles de conscientização.
- **Limitação:** A auditoria pontual representa um "retrato" do momento. Ficou evidente que a mitigação real e a manutenção da postura de segurança exigem monitoramento contínuo e automatizado, não apenas ações corretivas pontuais.

## Próximos Passos e Evoluções Futuras

- Integração dos achados e indicadores de risco a dashboards de GRC para monitoramento contínuo da postura de segurança.
- Expansão do escopo de testes para incluir avaliações de engenharia social e auditoria de segurança de terceiros (TPRM).
- Acompanhamento da evolução da maturidade dos controles em ciclos de auditoria semestrais.

---

## 📂 Documentação, Evidências e Recursos

- [Link para a Apresentação Executiva do Projeto (Sanitizada)]
- [Link para o Relatório Técnico de Auditoria (Anonimizado)]
- [Link para o Modelo de Mapa de Calor (Heat Map) e Valoração de Ativos]
- [Link para o Vídeo de Apresentação do Projeto]

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguelhcruz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mig.kruz@gmail.com)

---

## 🧭 Navegação do Portfólio

[⬅️ Voltar ao Perfil Principal](https://github.com/mighcruz) 

[📂 Voltar ao Hub Central de Projetos](https://github.com/mighcruz/portfolio-ti)
