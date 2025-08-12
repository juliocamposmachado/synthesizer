# 🎛️ SynthBat Studio - Sintetizador e Sequenciador Musical Avançado

**Uma aplicação web musical completa que combina sintetizador, bateria virtual e sequenciador profissional em uma interface moderna e personalizável.**

[![Deploy](https://img.shields.io/badge/deploy-vercel-black?style=for-the-badge&logo=vercel)](https://syntbat-ftz4i9ohz-astridnielsen-labs-projects.vercel.app)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](LICENSE)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-enabled-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

## 🎵 Demonstração

🔗 **[Acesse o SynthBat Studio Online](https://syntbat-ftz4i9ohz-astridnielsen-labs-projects.vercel.app)**

## ✨ Funcionalidades

### 🥁 **Bateria Virtual (16 Pads)**
- **9 Sons de Bateria**: Kick, Snare, Hi-Hat, Open Hat, Crash, Ride, Tom, Clap, Perc
- **Síntese Procedural**: Sons gerados em tempo real com Web Audio API
- **Visual Feedback**: Animações e cores específicas para cada pad
- **Touch Support**: Funciona perfeitamente em dispositivos móveis

### 🎹 **Sintetizador Completo (6 Instrumentos)**
- **Piano**: Som harmônico com múltiplas frequências
- **Bass**: Sintetizador de baixo com filtro passa-baixa
- **Lead**: Sintetizador principal com filtro dinâmico  
- **Pad**: Sons atmosféricos e envolventes
- **Pluck**: Instrumentos de corda sintéticos
- **Organ**: Órgão com harmônicos ricos

### 🎛️ **Efeitos Especiais (3 FX)**
- **Reverse**: Efeito reverso simulado
- **Sweep**: Filtros deslizantes em tempo real
- **White Noise**: Gerador de ruído branco

### 🎼 **Sequenciador Avançado**
- **32 Steps**: Sequenciador profissional de 32 passos
- **8 Trilhas**: Controle independente de 8 instrumentos
- **BPM Ajustável**: 60-180 BPM com controle em tempo real
- **Gravação de Áudio**: Captura e download de performances
- **Save/Load**: Sistema de salvamento de sequências em JSON

### 🎵 **Patches de Ritmo Pré-definidos**
- **🎸 Funk** (110 BPM) - Grooves clássicos do funk
- **🤘 Rock** (140 BPM) - Batidas de rock poderosas  
- **⭐ Pop** (128 BPM) - Ritmos pop comerciais
- **💎 Trap** (140 BPM) - Beats de trap modernos
- **🎛️ House** (124 BPM) - Batidas eletrônicas dançantes
- **🌴 Reggae** (90 BPM) - Ritmos jamaicanos autênticos

### 🎚️ **Controle XY Pad**
- **3 Modos de Síntese**:
  - Misturar Samples (Blend entre timbres)
  - Oscilador (Controle de frequência e filtro)
  - Morph Bateria (Transição entre sons de bateria)
- **Controle Tempo Real**: X para timbres, Y para pitch/volume
- **Interface Visual**: Canvas interativo com feedback visual

### 🏗️ **Interface Personalizável**
- **Layout 3 Colunas**: Tabela ajustável com redimensionamento
- **Cards Redimensionáveis**: Altura e largura ajustáveis independentemente  
- **Drag & Drop**: Reorganize elementos arrastando
- **Cards Recolhíveis**: Maximize o espaço de trabalho
- **Estado Salvo**: Layout preservado no localStorage
- **Responsivo**: Adapta-se perfeitamente a mobile e desktop

### ⚙️ **Controles Globais**
- **BPM Master**: 40-200 BPM
- **Volume Geral**: Controle de gain principal
- **Pitch Range**: Ajuste da faixa tonal
- **Metrônomo**: Click track opcional
- **Presets**: Sistema de salvamento de configurações

## 🚀 Tecnologias

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Audio Engine**: Web Audio API nativa
- **Interface**: CSS Grid, Flexbox, CSS Animations
- **Storage**: localStorage para persistência
- **Media**: MediaRecorder API para gravação
- **Deploy**: Vercel com CI/CD automático

## 🎯 Como Usar

### 🎵 **Criando Música**

1. **Toque os Pads**: Clique nos pads coloridos para tocar sons
2. **Use o Sequenciador**: 
   - Clique em GRAVAR para ativar o modo gravação
   - Toque os pads para adicionar à sequência
   - Use PLAY para tocar a sequência
3. **Experimente Patches**: Carregue ritmos pré-definidos
4. **Controle XY**: Use a área de controle para manipulação em tempo real

### 🎛️ **Personalizando a Interface**

1. **Redimensionar Cards**: Arraste o canto inferior direito (↘)
2. **Ajustar Colunas**: Arraste as bordas entre colunas
3. **Reorganizar**: Arraste cards pelos cabeçalhos
4. **Recolher**: Use os botões − para minimizar seções

### 💾 **Salvando Trabalho**

1. **Sequências**: Use SALVAR/CARREGAR para sequências JSON
2. **Gravações**: GRAVAR + PLAY gera arquivo de áudio
3. **Presets**: Salve configurações globais
4. **Layout**: Interface salva automaticamente

## 🛠️ Instalação Local

```bash
# Clone o repositório
git clone https://github.com/juliocamposmachado/synthesizer.git

# Entre no diretório
cd synthesizer

# Sirva com servidor local (exemplo com Python)
python -m http.server 8000

# Ou use qualquer servidor estático de sua preferência
npx serve .
```

Acesse `http://localhost:8000` no navegador.

### Controles Principais

#### 🎵 Pads de Bateria
- **Kick (Bumbo)**: Frequências graves para a base rítmica
- **Snare (Caixa)**: Som de caixa com reverb natural
- **Hi-Hat**: Sons de chimbal fechado e aberto
- **Crash/Ride**: Pratos para acentos e sustain

#### 🎹 Instrumentos Melódicos
- **Piano**: Som acústico clássico
- **Bass**: Graves profundos para linha de baixo
- **Lead**: Sons agudos para melodias principais
- **Pad**: Texturas atmosféricas e ambientes

#### ⏯️ Sequenciador
- **Play/Pause**: Inicia/pausa a reprodução
- **Stop**: Para e volta ao início
- **Clear**: Limpa todo o pattern
- **BPM**: Ajuste de 60 a 200 BPM


## 📱 Compatibilidade

- ✅ **Chrome/Chromium** (Recomendado)
- ✅ **Firefox** 
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Mobile Browsers** (iOS Safari, Chrome Mobile)
- ⚠️ **IE** (Não suportado - Web Audio API necessária)

## 🎨 Recursos Visuais

### Layout Adaptativo
- **Modo Coluna**: Layout vertical para telas menores
- **Modo Multi-Coluna**: Layout horizontal para telas maiores
- **Cards Redimensionáveis**: Ajuste manual do tamanho dos componentes
- **Expansão Centralizada**: Cards se expandem equilibradamente
- **Sistema Anti-Sobreposição**: Prevenção automática de overlaps

### Tema Visual
- **Paleta de Cores**: Tons de azul com acentos coloridos
- **Gradientes**: Efeitos de profundidade e modernidade
- **Animações**: Transições suaves e feedback visual
- **Glass Morphism**: Efeitos de transparência e blur
- **Favicon Personalizado**: Ícone SVG otimizado para o tema

### Compartilhamento Social
- **Open Graph**: Imagens otimizadas para redes sociais (1200x630)
- **Meta Tags**: SEO completo com descrições e palavras-chave
- **Favicon**: Ícone SVG responsivo com tema musical

## 🔧 Personalização

### Adicionando Novos Sons
1. Substitua os arquivos de áudio na estrutura de dados
2. Ajuste as configurações de volume e efeitos
3. Personalize as cores dos pads no CSS

### Modificando o Sequenciador
- Altere o número de steps modificando a variável `maxSteps`
- Adicione novos tracks editando o array `tracks`
- Customize o BPM padrão e limites

## 🔧 Arquitetura

```
SynthBat Studio/
├── index.html              # Aplicação principal (SPA)
├── README.md               # Este arquivo
├── LICENSE                 # Licença MIT
├── .gitignore             # Arquivos ignorados
└── assets/                # Assets futuros (imagens, samples)
```

### 🏗️ **Componentes Principais**

- **AudioEngine**: Gerenciamento Web Audio API
- **Synthesizer**: Classes de síntese de sons
- **Sequencer**: Motor de sequenciamento MIDI-style  
- **UIManager**: Controle de interface e drag-drop
- **StorageManager**: Persistência localStorage
- **RhythmPatches**: Sistema de patches predefinidos

## 📈 Atualizações Recentes

### v3.0 - Layout de 3 Colunas e Interface Avançada ✨
- ✅ **Layout de 3 Colunas**: Tabela ajustável com redimensionamento independente
- ✅ **Cards Redimensionáveis**: Altura e largura ajustáveis com resize nativo
- ✅ **Colunas Ajustáveis**: Arraste as bordas para redimensionar colunas
- ✅ **Estado Persistente**: Larguras de colunas salvas no localStorage
- ✅ **Interface Responsiva**: Layout adapta-se perfeitamente ao mobile
- ✅ **XY Pad Integrado**: Controle em tempo real incorporado à interface

### v2.5 - Patches de Ritmo e Recursos Avançados
- ✅ **6 Patches de Ritmo**: Funk, Rock, Pop, Trap, House, Reggae
- ✅ **Gravação de Áudio**: Sistema completo de captura e download
- ✅ **Save/Load Sequências**: Persistência em formato JSON
- ✅ **Efeitos Especiais**: Reverse, Sweep, White Noise
- ✅ **Controles Globais**: BPM, Volume, Pitch Range, Metrônomo

### v2.1 - Expansão Centralizada e UX Aprimorada
- ✅ **Expansão centralizada de cards**: Cards expandem equilibradamente
- ✅ **Sistema anti-sobreposição**: Detecção automática de overlaps
- ✅ **Animações melhoradas**: Transições suaves com cubic-bezier
- ✅ **SEO completo**: Meta tags e Open Graph otimizados

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

### 🎯 **Áreas para Contribuição**

- 🎵 Novos instrumentos e sons
- 🎨 Melhorias de UI/UX  
- 🔧 Otimizações de performance
- 📱 Melhorias mobile
- 🎼 Novos patches de ritmo
- 🌐 Internacionalização
- 📖 Documentação

## 📋 Roadmap

- [ ] **VST Integration**: Suporte a plugins VST via WebAssembly
- [ ] **MIDI Support**: Entrada/saída MIDI para controladores
- [ ] **Cloud Sync**: Sincronização de projetos na nuvem
- [ ] **Colaboração**: Edição multiusuário em tempo real
- [ ] **Sample Import**: Upload de samples personalizados
- [ ] **Advanced FX**: Reverb, Delay, Distortion, EQ
- [ ] **Piano Roll**: Editor MIDI visual avançado
- [ ] **Export Formats**: WAV, FLAC, MIDI export

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**Julio Campos Machado**
- 🌐 Website: [Like Look Solutions](https://likelook.wixsite.com/solutions)
- 📧 Email: [contato](mailto:julio@likelook.com)
- 🐙 GitHub: [@juliocamposmachado](https://github.com/juliocamposmachado)
- 📱 WhatsApp: [+55 11 99294-6628](https://wa.me/5511992946628)

## 🙏 Agradecimentos

- **Web Audio API Community** pela documentação excelente
- **Vercel** pela plataforma de deploy gratuita
- **MDN Web Docs** pela referência técnica
- **Open Source Community** pela inspiração

---

**🎵 Divirta-se criando música! 🎛️📱🎼**

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)](https://github.com/juliocamposmachado)
[![Brazilian Developer](https://img.shields.io/badge/🇧🇷-Brazilian%20Developer-green?style=for-the-badge)](https://github.com/juliocamposmachado)
