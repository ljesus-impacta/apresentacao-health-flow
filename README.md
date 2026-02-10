# HealthFlow Digital - Apresentação Corporativa

Apresentação interativa em HTML sobre a modernização da infraestrutura e inteligência de dados da plataforma de saúde HealthFlow Digital.

## 📋 Conteúdo da Apresentação

A apresentação conta com 10 slides principais:

1. **Título e Equipe** - Introdução ao HealthFlow Digital e apresentação da equipe do projeto
2. **Agenda Executiva** - Quatro pilares: Transformação Arquitetural, DevOps e Alta Disponibilidade, Segurança Zero Trust, e IA Generativa
3. **Cenário Anterior** - Infraestrutura Legacy: riscos, limitações e impactos operacionais (97% de disponibilidade)
4. **Arquitetura Moderna** - Solução cloud-native: EKS Multi-AZ, microsserviços, auto-scaling e balanceamento de carga (99.95% de uptime)
5. **Arquitetura Técnica** - Demonstração em vídeo da infraestrutura (arquitetura.mp4)
6. **Pipeline CI/CD** - Automação de ponta a ponta: GitHub → Trivy → ECR → ArgoCD → EKS (20 deploys/semana)
7. **Segurança em Camadas** - Modelo Zero Trust com WAF, IAM, GuardDuty e Blockchain para compliance HIPAA/LGPD
8. **IA Generativa** - Amazon Bedrock: resumo automático, alertas de interação, busca semântica e assistente clínico
9. **FinOps** - Otimização de custos e gestão financeira da infraestrutura
10. **Roadmap** - Fases de implementação: Migração Core (atual) → IA & Analytics (3-6 meses) → Global (+12 meses)

## 🚀 Como Usar

1. **Abrir no navegador:**
   - Abra o arquivo `index.html` em qualquer navegador moderno

2. **Navegar entre slides:**
   - **Botões:** Use os botões "Anterior" e "Próximo" na barra inferior
   - **Teclado:** Use as setas para esquerda/direita

3. **Visualizar progresso:**
   - O indicador "Slide X de 10" mostra sua posição atual

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura
- **Tailwind CSS** - Estilização responsiva
- **Chart.js** - Gráficos de uptime e economia
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia (Montserrat e Lato)
- **JavaScript Vanilla** - Navegação interativa

## 📱 Requisitos

- Navegador moderno com suporte a:
  - HTML5 e CSS3
  - JavaScript ES6+
  - Acesso à internet (para CDNs de fontes e ícones)
  - Suporte a vídeo MP4 (para slide de arquitetura)

## 📁 Estrutura dos Arquivos

```
apresentacao-health-flow/
├── index.html       # Arquivo principal da apresentação
├── arquitetura.mp4  # Vídeo de demonstração da arquitetura (opcional)
└── README.md        # Este arquivo
```

## 🎨 Design

- **Cores:** Paleta teal/turquesa (#2C7A7B) para marca
- **Layout:** Responsivo (desktop e mobile)
- **Animações:** Fade-in suave para melhor experiência visual
- **Acessibilidade:** Suporte a navegação por teclado

## 👥 Equipe

Projeto desenvolvido por:
- Bruno Amorim
- Fernando Jordão
- Henrique Lorente
- Ilberto Junior
- Jackson Gonzaga
- Luciano Jesus
- Marcos Paulo
- Raphael Carvalho
- Tiago Barbosa
- Ygor Monteiro

## 📝 Notas

- A apresentação é otimizada para resolução 16:9
- Certifique-se de que o arquivo `arquitetura.mp4` está no mesmo diretório do `index.html` para que o vídeo seja exibido corretamente
- Toda a estilização é inline (sem arquivos CSS externos) para máxima portabilidade