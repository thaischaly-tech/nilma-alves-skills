# Skills — Nilma Alves Advocacia

Skills do escritório **Nilma Alves Advocacia** para uso no Claude (Cowork mode).

Desenvolvidas durante processo de mentoria com foco em Direito de Família, Sucessões e Imobiliário.

---

## Instalação

Cada skill está disponível como arquivo `.skill` na pasta [`skills-instalacao/`](../skills-instalacao/).

**Para instalar no Claude (Cowork mode):**
1. Baixe o arquivo `.skill` da skill desejada
2. No Claude desktop, acesse **Plugins → Instalar plugin**
3. Selecione o arquivo `.skill` baixado
4. A skill estará disponível imediatamente

---

## Skills disponíveis

### Operacionais — Produção Jurídica

| Skill | Arquivo | Quando usar |
|---|---|---|
| Viabilidade do caso | `skill-01-viabilidade-caso.skill` | Avaliar GO/NO-GO antes de aceitar um caso |
| Diagnóstico de processo | `skill-02-diagnostico-processo.skill` | Analisar processo em andamento ou herdado |
| Transcrição de vídeo | `skill-03-transcricao-video.skill` | Transcrever consultas, audiências e reuniões |
| Analisar peça como juiz | `skill-04-analise-peca-como-juiz.skill` | Revisar peça na perspectiva do magistrado |
| Estruturar peça | `skill-05-estruturar-peca.skill` | Gerar esqueleto padronizado de peça |
| Revisar peça para protocolo | `skill-06-revisar-peca-protocolo.skill` | Checklist final antes do protocolo |
| Enxugar peça | `skill-07-enxugar-peca.skill` | Reduzir extensão sem perder técnica |

### Comercial e Marketing

| Skill | Arquivo | Quando usar |
|---|---|---|
| Artigos para o blog | `skill-08-artigos-advocacia.skill` | Produzir artigos SEO/GEO para o site |
| Roteiro para Instagram | `skill-09-roteiro-instagram.skill` | Criar roteiros de Reels e stories |
| Qualificar leads | `skill-10-qualificar-leads.skill` | Triagem e classificação de contatos novos |
| Análise de concorrência | `skill-11-analise-concorrencia-redes.skill` | Mapear concorrentes nas redes sociais |

### Automação

| Skill | Arquivo | Quando usar |
|---|---|---|
| Tarefas programadas | `skill-12-tarefas-programadas.skill` | Orquestrar tarefas recorrentes do escritório |

---

## Estrutura do repositório

```
skills/
├── README.md                              ← este arquivo
├── skill-01-viabilidade-caso/
│   ├── SKILL.md                           ← prompt instalável
│   ├── ficha-da-skill.md                  ← documentação da skill
│   └── CLAUDE.md                          ← instruções completas
├── skill-02-diagnostico-processo/
│   └── ...
└── ...

skills-instalacao/
├── skill-01-viabilidade-caso.skill        ← arquivo para instalar no Claude
├── skill-02-diagnostico-processo.skill
└── ...
```

---

## Nicho e contexto

- **Escritório:** Nilma Alves de Oliveira — Advocacia
- **Área:** Direito de Família, Sucessões e Imobiliário (regularização)
- **Localização:** Guarujá/SP — atende Santos e litoral SP
- **Tom:** técnico-acessível, sem juridiquês, sem alarmismo

---

## Licença

Uso restrito ao escritório Nilma Alves Advocacia e às mentoradas autorizadas pela mentora.
