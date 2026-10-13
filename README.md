# 40 Facadinhas — versão 1

## Publicação e direitos autorais

O repositório é público para consulta. Não são aceitas modificações no repositório por terceiros sem autorização da proprietária. A publicação de obras derivadas não é permitida pelo regime **CC BY-NC-ND 4.0** adotado para os elementos autorais. Recursos de terceiros podem ter outros termos — consulte os créditos e o arquivo [LICENSE.md](LICENSE.md).

**Código:** Creative Commons não é a licença habitualmente recomendada para software; esta opção foi adotada por solicitação da autora para preservar a natureza de obra literária digital. Não confunda acesso ao código com permissão geral de reutilização.


---

# FACADINHAS - Experiência Interativa Web

## 📋 Sobre o Projeto

**FACADINHAS** é uma experiência interativa web que explora a violência através de uma narrativa visual envolvente. O projeto utiliza 40 cliques, movimento físico, notícias reais e poesia para criar uma reflexão sobre a violência na sociedade.

## 🎯 Conceito

O projeto parte do número "40" como elemento central - referência aos crimes com 40 facadas que frequentemente aparecem nas notícias. Através de uma jornada interativa, o usuário é levado a refletir sobre a violência de forma imersiva e poética.

## 🚀 Funcionalidades

### 📱 Fluxo de Experiência
0. **Página Inicial** (`0 - index.html`) - Botão interativo que requer 40 cliques
1. **Exercício Físico** (`1 - movement-page.html`) - Instruções para movimento corporal
2. **Camada de Notícias** (`2 - news-page.html`) - Imagens sobrepostas de notícias reais
3. **Seleção de Poemas** (`3 - poem-layer.html`) - Escolha entre três poemas
4. **Poema Primeiro** (`4 - poem-1.html`)
5. **Poema Segundo** (`5 - poem-2.html`)
6. **Poema Terceiro** (`6 - poem-3.html`)
7. **Casa da vovó** (`7 - casa da vovó.html`) - Imagem centralizada, botão de play e créditos
8. **Página Final/Mosaico** (`8 - page5.html`) - Mosaico visual com navegação completa

### 🎨 Elementos Visuais
- **Cursor Personalizado** - Imagem customizada em todas as páginas
- **Efeito de Sangue** - Manchas vermelhas que aparecem em cliques
- **Animações CSS** - Transições suaves e efeitos visuais
- **Imagens Assustadoras** - Aparição dramática no meio dos poemas
- **Responsividade** - Funciona em desktop e dispositivos móveis

### 🔊 Sistema de Áudio
- **Trilha Sonora Contínua** - Música de fundo que persiste entre páginas
- **Som do Cursor** - Efeitos sonoros de faca em cliques não-interativos
- **Controles de Áudio** - Botões para ativar/desativar som do cursor e trilha
- **Persistência de Estado** - Configurações salvas no localStorage
- **Volume Padronizado** - Volume ajustado para 0.08 em todos os áudios

### 🤖 Integração com IA
- **ChatGPT Programação** - Prompts para desenvolvimento de código
- **ChatGPT Imagem** - Prompts para criação de elementos visuais
- **Assistente de Desenvolvimento** - Suporte contínuo durante o projeto

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
- **JavaScript ES6+** - Interatividade e lógica
- **Responsive Design** - Adaptação para diferentes dispositivos
- **CSS Animations** - Efeitos visuais avançados
- **Custom Cursors** - Experiência visual personalizada
- **Web Audio API** - Controle de áudio avançado
- **localStorage** - Persistência de configurações

## 📁 Estrutura do Projeto

```
📦 40/
├── 0 - index.html (Página principal)
├── 1 - movement-page.html (Exercício físico)
├── 2 - news-page.html (Notícias)
├── 3 - poem-layer.html (Seleção de poemas)
├── 4 - poem-1.html (Poema Primeiro)
├── 5 - poem-2.html (Poema Segundo)
├── 6 - poem-3.html (Poema Terceiro)
├── 7 - casa da vovó.html (Imagem, botão de play e créditos)
├── 8 - page5.html (Página final/mosaico)
├── referencias.html (Referências de notícias)
├── informações sobre o desenvolvimento.html (Documentação técnica)
├── styles.css (Estilos principais)
├── blood-effect.css (Efeito de sangue)
├── blood-effect.js (JavaScript do sangue)
├── script.js (Script principal)
├── poem-layer.js, poem-1.js, poem-2.js, poem-3.js (Scripts dos poemas)
├── poem-layer.css, poem-1.css, poem-2.css, poem-3.css (Estilos dos poemas)
├── README.md (Esta documentação)
└── assets/ (Imagens e recursos)
    ├── cursor.png (Cursor personalizado)
    ├── faca.png (Imagem do botão)
    ├── mosaico.png (Imagem final)
    ├── poema 1.png, poema 2.png, poema 3.png (Imagens dos poemas)
    ├── crime.png (Imagem principal)
    ├── Casa da vovó glorinha 14 07 2025.jpeg (Imagem da casa)
    ├── 1.png a 8.png (Imagens de notícias)
    ├── trilha.mp3 (Trilha sonora de fundo)
    ├── faca 1.mp3 a faca 5.mp3 (Sons do cursor)
    └── 40 facadas.mp3 (Áudio específico da página 7)
```

## 🎭 Conteúdo Poético

O projeto inclui três poemas originais que exploram diferentes aspectos da violência:

4. **Poema Primeiro** - Reflexão sobre a contagem dos golpes
5. **Poema Segundo** - Análise da violência como sintoma social
6. **Poema Terceiro** - Mapeamento geográfico da violência

## 🏠 Página Especial: Casa da vovó

7. **Casa da vovó** - Uma página com uma imagem centralizada, fundo preto, botão de play (para áudio "40 facadas.mp3") e créditos discretos no canto inferior esquerdo.

## 📰 Referências de Notícias

O projeto inclui 8 referências de notícias reais sobre crimes com 40 facadas, demonstrando como a violência se manifesta em diferentes contextos e regiões do Brasil.

## 🔗 Links Importantes

- **Portfólio da Autora** - [Dayane Argentino](https://www.canva.com/design/DAGZkr98aeM/DAm6C8XZQkdNN2LWegVRQw/edit)
- **ChatGPT Programação** - [Prompts de Desenvolvimento](https://chatgpt.com/share/68706d89-627c-8003-baa5-e408e0333366)
- **ChatGPT Imagem** - [Prompts de Imagem](https://chatgpt.com/share/68706d9c-a9d4-8003-87fa-ded7c9d452b2)
- **Documentação Técnica** - [Desenvolvimento](informações%20sobre%20o%20desenvolvimento.html)

## 🎯 Objetivos Alcançados

- ✅ **Experiência Imersiva** - Interface que envolve o usuário
- ✅ **Narrativa Visual** - História contada através de interações
- ✅ **Reflexão Social** - Conteúdo que provoca pensamento
- ✅ **Inovação Técnica** - Uso criativo de tecnologias web
- ✅ **Acessibilidade** - Funciona em diferentes dispositivos
- ✅ **Sistema de Áudio Completo** - Trilha sonora e efeitos sonoros
- ✅ **Controles de Áudio** - Interface para gerenciar sons
- ✅ **Persistência de Configurações** - Estado salvo entre sessões

## 🚀 Como Executar

1. Clone ou baixe o projeto
2. Abra o arquivo `0 - index.html` em um navegador web
3. Siga a experiência interativa clicando e navegando pelas páginas
4. Explore todos os elementos e funcionalidades
5. Use os controles de áudio para personalizar a experiência

## 🔧 Correções Recentes

- ✅ **Correção de Duplicação de Código** - Removida duplicação de scripts de áudio
- ✅ **Padronização de Volume** - Volume ajustado para 0.08 em todos os áudios
- ✅ **Correção de Variáveis** - Eliminados conflitos de redeclaração
- ✅ **Unificação de Controles** - Scripts de áudio consolidados
- ✅ **Melhoria de Performance** - Código otimizado e limpo

## 📝 Notas de Desenvolvimento

Este projeto foi desenvolvido em colaboração com IA, demonstrando como a tecnologia pode ser usada para criar experiências artísticas significativas. Cada elemento foi cuidadosamente planejado para criar uma narrativa coesa sobre violência e reflexão social.

## 🎵 Créditos de Áudio

- **Trilha sonora de fundo:** "Life or Death" — Ethan Sloan
- **Sons do mouse:** "Strange Beast from the North (Instrumental Version)" — Grevens Tid
- **Áudio específico:** "40 facadas.mp3" — Áudio personalizado da página 7

## 👤 Autora

**Dayane Argentino** - Desenvolvedora e artista digital

---

*FACADINHAS - Uma experiência sobre violência, reflexão e arte digital* 