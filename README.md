# Aura — Estúdio de Estudo Local-First & Cloud Sync

> Estúdio de estudo integrado, sem fricção, operando em tempo real com arquitetura local-first e sincronização em nuvem multi-dispositivo.

## 🚀 Funcionalidades Principais

- **Leitura & Anotação Ativa**: Suporte a textos e PDFs com highlight em 4 cores semânticas e exportação direta.
- **Caderno Cornell & Grafo de Conhecimento**:
  - Sistema de notas com links bidirecionais (`[[Nota]]`).
  - Grafo interativo SVG (Local e Global): arraste livre de nós, conexão rápida entre conceitos e realce de vizinhança.
  - Lousa Cornell livre com desenho vetorial e exportação SVG/PNG.
- **Mapas Mentais**: Criação visual de nós em árvore com atalhos de teclado ágeis (`Tab` para filho, `Enter` para irmão).
- **Revisão Ativa & Flashcards FSRS**:
  - Algoritmo moderno de repetição espaçada FSRS (Free Spaced Repetition Scheduler) com cálculo de estabilidade e dificuldade.
  - Vínculo direto entre flashcards e trechos de notas.
- **Agenda Semanal & Consistência**:
  - Bloco de tempo semanal para agendamento de sessões.
  - Metas de estudo com acompanhamento de progresso em tempo real.
  - Heatmap de consistência (28 dias) para manutenção de hábitos.
- **Cronômetro Pomodoro Preciso**: Foco imersivo com drift correction (`Date.now()`).
- **Autenticação & Nuvem Multi-Dispositivo**:
  - IndexedDB para performance instantânea (< 16ms) e uso offline.
  - Sincronização em nuvem com Supabase (PostgreSQL + Row Level Security).
  - Acesso sincronizado no computador e celular.

## 🛠️ Tecnologias

- HTML5 / CSS3 moderno (Design Tokens, 3 temas ergonômicos: Escuro Fosco, Papel Sépia e Claro)
- JavaScript Vanilla otimizado (zero overhead, execução nativa no navegador)
- IndexedDB (`AuraStudyDB`)
- Supabase JS SDK (Autenticação e Nuvem)
