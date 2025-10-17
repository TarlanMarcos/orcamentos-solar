# Sistema de Orçamentos de Energia Solar

Sistema web automatizado para geração de orçamentos de energia solar fotovoltaica, desenvolvido para M Sol Energia e Engenharia.

## 🌟 Funcionalidades

### ✨ Análise Inteligente de Faturas
- Upload de faturas de energia (PDF, JPG, PNG)
- Extração automática de dados por IA simulada
- Identificação de consumo, tarifa e informações do cliente
- Histórico de consumo dos últimos 12 meses

### 🗺️ Localização e Dimensionamento
- Mapa interativo para seleção de coordenadas
- Cálculo automático de irradiância solar
- Dimensionamento técnico preciso baseado em:
  - Azimute e inclinação otimizados
  - Perdas do sistema
  - Eficiência dos módulos
  - Fatores de performance regionais

### 💰 Análise Econômica Completa
- Cálculo de payback do investimento
- Projeção de economia em 10, 15 e 25 anos
- Consideração da taxa de inflação
- Simulação de fatura mínima

### 🔗 Integração com Fornecedor
- Integração com plataforma Alumifix Solar
- Importação automática de orçamentos via link
- Extração de itens e valores por IA simulada

### 📄 Geração de Propostas
- Proposta técnica comercial completa
- Gráficos de consumo vs geração
- Análise de retorno do investimento
- Export em PDF e impressão
- Salvamento automático de propostas

### 🔍 Busca e Gerenciamento
- Sistema de busca de orçamentos antigos
- Visualização, edição e exclusão de propostas
- Interface intuitiva e responsiva

## 🚀 Tecnologias Utilizadas

- **React 18** - Framework frontend
- **Leaflet** - Mapas interativos
- **Recharts** - Gráficos e visualizações
- **Lucide React** - Ícones modernos
- **CSS3** - Animações e transições
- **GitHub Pages** - Hospedagem gratuita

## 📦 Instalação e Uso

### Pré-requisitos
- Node.js 16+ 
- npm ou yarn

### Instalação
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/orcamento-solar.git

# Entre no diretório
cd orcamento-solar

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
```

### Build para Produção
```bash
# Gere o build otimizado
npm run build

# Deploy no GitHub Pages
npm run deploy
```

## 🎯 Como Usar

1. **Dados do Cliente**: Preencha as informações básicas do cliente
2. **Upload de Fatura**: Faça upload da fatura para extração automática de dados
3. **Localização**: Use o mapa interativo para definir a localização da instalação
4. **Dimensionamento**: Configure os parâmetros técnicos do sistema
5. **Orçamento Alumifix**: Cole o link do orçamento da plataforma do fornecedor
6. **Precificação**: Ajuste custos e margens conforme necessário
7. **Análise Econômica**: Revise os cálculos de retorno do investimento
8. **Gerar Proposta**: Crie a proposta técnica comercial em PDF

## ⚙️ Configurações Padrão

- **Deslocamento e Estadia**: R$ 500,00
- **Imposto**: 2,7%
- **Taxa de Inflação Anual**: 6,45%
- **Perdas do Sistema**: 12%
- **Eficiência dos Módulos**: 22,65%

## 🤖 IA Simulada

O sistema simula funcionalidades de IA para:
- Extração de dados de faturas de energia
- Análise de orçamentos da plataforma Alumifix
- Geocodificação de endereços
- Consulta de dados de irradiância solar

Em um ambiente de produção, essas funcionalidades seriam implementadas com:
- OCR (Tesseract.js ou Google Vision API)
- NLP para extração de entidades
- APIs de geocodificação (Google Maps, OpenStreetMap)
- APIs de dados solares (INPE, NASA)

## 📊 Cálculos Técnicos

### Dimensionamento do Sistema
```
kWp = Consumo Total / (Irradiância × Perdas × Fator de Performance)
```

### Fator de Performance
- **Azimute**: Otimizado para 0° (Norte) no hemisfério sul
- **Inclinação**: Baseada na latitude local
- **Eficiência**: Normalizada para módulos de 20% de eficiência base

### Análise Econômica
```
Payback = Investimento Total / Economia Mensal
Economia Futura = PMT × ((1 + taxa)^n - 1) / taxa
```

## 🎨 Interface

- Design responsivo e moderno
- Animações suaves e micro-interações
- Tema claro com suporte a modo escuro
- Navegação intuitiva por etapas
- Feedback visual em tempo real

## 📞 Contato

**M Sol Energia e Engenharia**
- 📧 Email: contatomsol@yahoo.com
- 📱 WhatsApp: (46) 9 9914-1916
- 📍 Capanema - PR

---

Desenvolvido com ❤️ para automatizar e otimizar o processo de orçamentação de energia solar.
