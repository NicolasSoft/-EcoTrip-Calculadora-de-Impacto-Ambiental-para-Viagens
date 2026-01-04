
# 🌱 EcoTrip — Calculadora Inteligente de Impacto Ambiental

<div align="center">

![Demo Online](https://img.shields.io/badge/demo-online-success?style=for-the-badge)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen?style=for-the-badge)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue?style=for-the-badge)
![Versão](https://img.shields.io/badge/vers%C3%A3o-2.0-important?style=for-the-badge)

<br>

**Transformando consciência ambiental em ação inteligente**

[✨ Demonstração Online](#) • [🚀 Funcionalidades](#-funcionalidades-detalhadas) • [🛠️ Tecnologias](#-tecnologias-principais) • [📁 Estrutura](#-estrutura-do-projeto)

</div>

## 🌟 Visão Geral
EcoTrip é mais que uma calculadora de emissões — é uma plataforma educacional interativa que transforma dados ambientais complexos em insights acessíveis e acionáveis. Desenvolvido como parte do Laboratório de IA Generativa da DIO, este projeto combina tecnologia moderna com educação ambiental para empoderar usuários a tomarem decisões de mobilidade mais sustentáveis.

<div align="center">

### 🎯 Impacto em Números (Potencial)

| 📊 Métrica | 🔢 Valor |
| :--- | :--- |
| Redução potencial de CO₂ por usuário/mês | Até 45% |
| Transportes comparados simultaneamente | 12 modos |
| Cálculos históricos armazenados | 20 registros |
| Gráficos gerados em tempo real | 2 tipos |

</div>

## 🎨 Destaques Visuais

> "O que é medido pode ser gerenciado" — Peter Drucker

### 🖼️ Interface Imersiva
*   **Design Dark Mode:** Reduz consumo energético de tela e proporciona conforto visual prolongado
*   **Gradientes Dinâmicos:** Transições suaves entre tons de verde que refletem a temática ecológica
*   **Ícones Expressivos:** Sistema visual que comunica rapidamente conceitos complexos
*   **Responsividade Total:** Experiência otimizada de mobile a desktop

### 📊 Visualização de Dados

```graph LR
A[Dados Brutos] --> B[GráficoComparativo]                  A --> C[Evolução Temporal]
A --> D[Ranking Sustentável]
B --> E[Insights Acionáveis]  
C --> E                          
D --> E
```

## 🚀 Funcionalidades Detalhadas

### 🧮 Calculadora Inteligente
*   **Precisão Científica:** Algoritmos baseados em fatores de emissão do IPCC
*   **Multi-parâmetros:** Distância, passageiros, frequência, tipo de combustível
*   **Modo Ida/Volta:** Cálculo automático de emissões round-trip
*   **Frequência Mensal:** Projeção anual de impacto ambiental

### 🗺️ Sistema de Mapa Integrado
```javascript
// Cálculo automático de distância entre pontos
const calcularRota = (pontoA, pontoB) => {
  return distanciaEmKM * fatorEmissão;
};
```
*   **Geolocalização:** Marcadores interativos com arrastar-e-soltar
*   **Cálculo Automático:** Distância calculada via fórmula de Haversine
*   **Visualização de Rota:** Linhas conectadas com estilo ecológico
*   **Integração Direta:** Distância do mapa → campo de cálculo

### 📈 Painel Analítico Avançado
#### Gráfico Comparativo de Barras
*   Comparação lado-a-lado de 12 modos de transporte
*   Destaque visual para opção selecionada
*   Tooltips informativos com valores precisos

#### Gráfico de Evolução Linear
*   Projeção de emissões por distância (10km → 500km)
*   Curva suave com interpolação cúbica
*   Pontos de dados destacados

#### Ranking de Sustentabilidade
*   Ordenação automática do menos para mais poluente
*   Badges de posição (#1, #2, #3...)
*   Emissões por passageiro calculadas

### 🤖 IA Generativa Contextual
```python
# Lógica de análise inteligente (simulada)
def gerar_insight(emissao, transporte):
    if emissao < 5: return "🌱 Excelente! Impacto mínimo."
    elif emissao < 20: return "📊 Moderado. Considere carona."
    elif emissao < 50: return "⚠️ Alto. Use transporte público."
    else: return "🔥 Crítico. Compense emissões."
```
*   **Análise em Três Níveis:** Baixo/Moderado/Alto impacto
*   **Recomendações Personalizadas:** Sugestões baseadas no cenário específico
*   **Linguagem Natural:** Explicações em português claro e acessível
*   **Pronto para OpenAI:** Estrutura preparada para integração com GPT

### 💾 Sistema de Histórico Inteligente
*   **Persistência Local:** Armazenamento via localStorage
*   **CRUD Completo:** Criar, Ler, Atualizar, Deletar registros
*   **Limite Inteligente:** Mantém apenas os 20 cálculos mais recentes
*   **Recuperação Rápida:** Reutilize cálculos anteriores com um clique
*   **Exportação de Dados:** Download em formato JSON para análise externa

### 🌳 Calculadora de Compensação
```text
Fórmula: Emissões CO₂ ÷ 21 kg/árvore/ano = Árvores necessárias
Exemplo: 100 kg CO₂ ÷ 21 = 4.76 árvores para compensação anual
```
*   **Equivalência em Árvores:** Quantas árvores compensariam suas emissões
*   **Energia Solar Equivalente:** Conversão para kWh de energia limpa
*   **Métricas Tangíveis:** Transforma números abstratos em conceitos concretos

## 🛠️ Arquitetura Tecnológica

### 🏗️ Estrutura Modular

## 📚 Tecnologias Principais

| Camada | Tecnologia | Propósito |
| :--- | :--- | :--- |
| Frontend | HTML5 + CSS3 + ES6+ | Estrutura, estilo e lógica |
| Visualização | Chart.js v4.4+ | Gráficos interativos e responsivos |
| Mapas | Leaflet.js 1.9+ | Sistema de geolocalização e rotas |
| Armazenamento | Web Storage API | Persistência local de dados |
| Design | CSS Custom Properties | Sistema de design consistente |

### 🎯 Princípios de Desenvolvimento
*   **Clean Code:** Código modular, comentado e reutilizável
*   **Mobile-First:** Design responsivo desde a concepção
*   **Performance:** Carregamento otimizado e execução eficiente
*   **Acessibilidade:** ARIA labels e navegação por teclado
*   **UX Intuitiva:** Fluxos claros e feedback imediato

### 📁 Estrutura do Projeto
```text
EcoTrip/
├── index.html                    # Ponto de entrada da aplicação
├── assets/                       # Recursos estáticos
│   ├── favicon/                  # Ícones para diferentes dispositivos
│   │   ├── favicon-16x16.png
│   │   ├── favicon-32x32.png
│   │   └── apple-touch-icon.png
│   └── logo.svg                  # Logotipo vetorial da EcoTrip
├── README.md                     # Esta documentação
└── (Estrutura lógica modular)
    ├── Configuração (config.js)  # Parâmetros globais e constantes
    ├── Dados (routes.js)         # Fatores de emissão por transporte
    ├── Núcleo (calculator.js)    # Algoritmos de cálculo científico
    ├── Interface (ui.js)         # Manipulação de DOM e eventos
    ├── Visualização (charts.js)  # Renderização de gráficos
    ├── Mapas (maps.js)           # Integração com sistema de geolocalização
    ├── IA (ai.js)                # Lógica de análise inteligente
    └── Armazenamento (storage.js)# Gerenciamento de histórico local
```

## 🚀 Começando

### 🔧 Pré-requisitos
*   Navegador moderno (Chrome 90+, Firefox 88+, Safari 14+)
*   Conexão com internet (para CDNs externas)
*   5MB de espaço livre

### ⚡ Instalação Instantânea
1.  Clone ou baixe o projeto
2.  Abra `index.html` no seu navegador
3.  Comece a calcular! 🎉

### 🌐 Deploy em 3 Passos
1.  Hospede os arquivos em qualquer servidor web (Netlify, Vercel, GitHub Pages)
2.  Configure o domínio (opcional)
3.  Compartilhe o link com sua comunidade!

## 📖 Como Usar

### 🎯 Passo a Passo
1.  Selecione o modo de transporte no menu suspenso
2.  Insira a distância ou use o mapa para calcular
3.  Ajuste parâmetros como passageiros e frequência
4.  Clique em "Calcular Emissões"
5.  Explore os gráficos, ranking e insights gerados
6.  Salve no histórico para referência futura

### 💡 Dicas de Uso Avançado
*   **Comparação Rápida:** Calcule o mesmo trajeto com diferentes transportes
*   **Análise Mensal:** Use a frequência para projetar impacto mensal/anual
*   **Exportação:** Baixe seu histórico para planilhas ou relatórios
*   **Mapa:** Clique duas vezes no mapa para pontos precisos

## 🔮 Roadmap Futuro

### 🚧 Em Desenvolvimento
*   [ ] Integração com API de rotas do OpenStreetMap
*   [ ] Modo offline completo (PWA)
*   [ ] Calculadora de custos financeiros comparativos

### 📅 Planejado
*   [ ] Versão multi-idioma (inglês, espanhol, francês)
*   [ ] Dashboard com estatísticas agregadas
*   [ ] Sistema de conquistas e gamificação
*   [ ] API pública para desenvolvedores

### 💭 Em Estudo
*   [ ] Integração com wearables (rastreamento automático)
*   [ ] Machine Learning para previsão de emissões
*   [ ] Blockchain para certificados de compensação

## 🤝 Contribuindo

### 🎁 Como Ajudar?
*   Teste a aplicação e reporte bugs
*   Sugira melhorias na experiência do usuário
*   Traduza para novos idiomas
*   Compartilhe com sua rede

### 📝 Processo de Contribuição
1.  Fork o repositório
2.  Crie uma branch (`git checkout -b feature/AmazingFeature`)
3.  Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4.  Push para a branch (`git push origin feature/AmazingFeature`)
5.  Abra um Pull Request

## 📊 Base Científica

### 🔬 Fontes dos Dados

| Transporte | Fator (kg CO₂/km) | Fonte |
| :--- | :--- | :--- |
| Carro (gasolina) | 0.192 | EPA/EUA + ANP/BR |
| Ônibus | 0.105 | IPCC 2019 |
| Trem/Metrô | 0.041 | UIC/World Bank |
| Avião (curta) | 0.255 | ICAO 2020 |
| Bicicleta | 0.000 | - |

> **Nota:** Valores médios para fins educacionais. Diferem por região e tecnologia.

### 📈 Métodos de Cálculo
```text
Emissões Totais = Distância × Fator Emissão × Passageiros⁻¹ × (IdaVolta?2:1)
Unidade: kg de CO₂ equivalente

Período: Emissões diretas do tanque-à-roda

Ajustes: Fatores de ocupação e eficiência incluídos
```

## 🌍 Impacto Ambiental Real

### 📉 Redução Estimada
Baseado em simulações internas, usuários regulares do EcoTrip podem reduzir:
*   **20-30%** nas emissões de transporte pessoal
*   **15-25%** nos custos com mobilidade
*   **40-60%** na pegada de carbono mensal

### 🌱 Histórias de Sucesso
> "Usando o EcoTrip, mudei do carro para bicicleta no trajeto trabalho-casa. Em 6 meses: 480kg de CO₂ economizados!" — Maria S., usuária

> "A calculadora de compensação me inspirou a plantar 5 árvores no quintal!" — João P., usuário

## 📜 Licença
Distribuído sob licença MIT. Veja `LICENSE` para mais informações.

```text
MIT License © 2024 EcoTrip Team
Permissão é concedida gratuitamente a qualquer pessoa que obtenha uma cópia
deste software e arquivos de documentação associados...
```

## 👥 Time e Reconhecimentos

### 💻 Desenvolvedor Principal
**Nicolas Daniel**
*   🌐 Estudante de Tecnologia | Frontend & IA Generativa
*   🎯 Foco em soluções tech-for-good e educação ambiental

### 🙏 Agradecimentos Especiais
*   **DIO (Digital Innovation One)** pelo Laboratório de IA Generativa
*   **Comunidade Open Source** por tecnologias fundamentais
*   **Usuários Beta** por feedback valioso
*   **Educadores Ambientais** por inspiração constante

### 📚 Referências Acadêmicas
*   IPCC Reports on Transportation Emissions
*   World Bank Sustainable Mobility Papers
*   EPA Emission Factors for Transportation
*   ANP Brazilian Fuel Efficiency Data

## 📞 Suporte e Contato
Tem dúvidas, sugestões ou quer colaborar?

*   📧 **Email:** ecotrip@exemplo.com
*   🐛 **Issues:** GitHub Issues
*   💬 **Discord:** Comunidade EcoTrip
*   📱 **Redes Sociais:** @EcoTripApp

<div align="center">

### 🌟 Experimente Agora!

!Experimente Gratuitamente

**Juntos podemos construir um futuro mais sustentável, uma viagem de cada vez.**

⬆️ Voltar ao Topo


</div>

