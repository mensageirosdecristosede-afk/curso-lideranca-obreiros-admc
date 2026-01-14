# GUIA DE CONVERSÃO DE SLIDES
## Como converter os arquivos .md para PowerPoint ou Google Slides

---

## 🎯 OPÇÕES DE CONVERSÃO

Você tem 3 opções principais para usar os slides:

1. **Criar manualmente** (mais controle visual)
2. **Usar ferramentas online** (rápido)
3. **Usar Marp/Pandoc** (para quem tem experiência técnica)

---

## 📌 OPÇÃO 1: CRIAR MANUALMENTE (RECOMENDADO)

### Vantagens:
✅ Controle total do design  
✅ Adicionar logo da ADMC  
✅ Cores personalizadas  
✅ Animações e transições  

### Como fazer:

#### NO POWERPOINT:

**PASSO 1: Configurar o template**
1. Abra PowerPoint
2. Tamanho: 16:9 (widescreen)
3. Escolha tema simples e clean
4. Defina paleta de cores da ADMC
5. Adicione logo no rodapé (se houver)

**PASSO 2: Criar os slides**
1. Abra o arquivo `SLIDES-ENCONTRO-1.md`
2. Cada seção marcada com `## SLIDE X` é um slide
3. Copie o conteúdo e cole no PowerPoint
4. Formate:
   - Títulos em fonte grande (32-44pt)
   - Texto principal (18-24pt)
   - Versículos em itálico
   - Emojis podem ser mantidos ou substituídos por ícones

**PASSO 3: Aplicar design**
- Use espaços em branco
- Não sobrecarregue os slides
- Use imagens de fundo sutis (opcional)
- Mantenha legibilidade

**PASSO 4: Adicionar animações (opcional)**
- Títulos: aparecer
- Listas: aparecer item por item
- Transições suaves entre slides

---

#### NO GOOGLE SLIDES:

**PASSO 1: Configurar**
1. Acesse [slides.google.com](https://slides.google.com)
2. Novo > Em branco
3. Tamanho padrão (16:9)
4. Escolha tema ou crie personalizado

**PASSO 2: Criar slides**
- Mesmo processo do PowerPoint
- Copiar e colar conteúdo dos arquivos .md
- Formatar conforme necessário

**PASSO 3: Colaboração**
- Compartilhar com equipe
- Editar colaborativamente
- Apresentar diretamente do navegador

---

### 🎨 SUGESTÕES DE DESIGN:

#### PALETA DE CORES (adapte às cores da ADMC):

**Opção 1 - Profissional:**
- Título: Azul escuro (#1a237e)
- Texto: Cinza escuro (#424242)
- Destaque: Laranja (#ff6f00)
- Fundo: Branco ou cinza claro

**Opção 2 - Moderno:**
- Título: Verde escuro (#2e7d32)
- Texto: Preto (#000000)
- Destaque: Amarelo (#fbc02d)
- Fundo: Branco

**Opção 3 - Elegante:**
- Título: Roxo (#6a1b9a)
- Texto: Cinza (#616161)
- Destaque: Rosa (#e91e63)
- Fundo: Branco cremoso

#### FONTES RECOMENDADAS:

**Para Títulos:**
- Montserrat (moderna)
- Poppins (clean)
- Roboto (simples)
- Open Sans (legível)

**Para Texto:**
- Lato
- Roboto
- Open Sans
- Arial (sempre funciona)

#### LAYOUT:

**Slide de Título:**
```
╔══════════════════════════════════════╗
║                                      ║
║                                      ║
║         TÍTULO PRINCIPAL             ║
║           Subtítulo                  ║
║                                      ║
║          [LOGO ADMC]                 ║
║                                      ║
╚══════════════════════════════════════╝
```

**Slide de Conteúdo:**
```
╔══════════════════════════════════════╗
║  TÍTULO DO SLIDE                     ║
║  ────────────────                    ║
║                                      ║
║  • Ponto 1                           ║
║  • Ponto 2                           ║
║  • Ponto 3                           ║
║                                      ║
║  Imagem ou ícone (opcional)          ║
║                                      ║
╚══════════════════════════════════════╝
```

**Slide de Versículo:**
```
╔══════════════════════════════════════╗
║                                      ║
║                                      ║
║  "Texto do versículo..."             ║
║                                      ║
║           Referência                 ║
║                                      ║
║                                      ║
╚══════════════════════════════════════╝
```

---

## 📌 OPÇÃO 2: FERRAMENTAS ONLINE

### 1. USAR MARP (Markdown Presentation)

**O que é:** Ferramenta que converte Markdown em slides

**Como usar:**

1. Acesse: https://marp.app/
2. Ou instale extensão Marp no VS Code
3. Copie conteúdo dos arquivos .md
4. Adicione cabeçalho Marp:

```markdown
---
marp: true
theme: default
paginate: true
---

<!-- Depois cole o conteúdo dos slides -->
```

4. Exporte para PDF ou PowerPoint

**Vantagem:** Rápido  
**Desvantagem:** Menos controle visual

---

### 2. USAR SLIDEV

**O que é:** Framework moderno para slides

**Para desenvolvedores:**
1. Instale Node.js
2. `npm init slidev@latest`
3. Adapte o conteúdo Markdown
4. Apresente ou exporte

**Vantagem:** Interativo, animações avançadas  
**Desvantagem:** Requer conhecimento técnico

---

### 3. USAR PANDOC

**Para converter para PowerPoint:**

```bash
pandoc SLIDES-ENCONTRO-1.md -o encontro-1.pptx
```

**Vantagem:** Automático  
**Desvantagem:** Resultado genérico, precisa editar depois

---

## 📌 OPÇÃO 3: USAR FERRAMENTAS DE IA

### ChatGPT / Claude:

Você pode pedir para formatar cada slide especificamente:

**Exemplo de prompt:**
```
"Crie um slide de PowerPoint com este conteúdo:
[colar conteúdo do slide]
Formato: título grande, 3 bullet points, fonte clean"
```

### Canva:

1. Acesse [canva.com](https://canva.com)
2. Escolha template de apresentação
3. Copie e cole conteúdo dos slides
4. Personalize design
5. Baixe como PowerPoint ou PDF

**Vantagem:** Design bonito e fácil  
**Desvantagem:** Versão gratuita tem limitações

---

## 🎬 COMO APRESENTAR OS SLIDES

### PREPARAÇÃO:

**1 Semana Antes:**
- [ ] Criar todos os slides
- [ ] Revisar conteúdo
- [ ] Adicionar notas do apresentador
- [ ] Testar em projetor/TV

**1 Dia Antes:**
- [ ] Backup em pen drive
- [ ] Backup em nuvem (Google Drive/OneDrive)
- [ ] Testar equipamentos
- [ ] Praticar apresentação

**No Dia:**
- [ ] Chegar 1h antes
- [ ] Abrir apresentação
- [ ] Modo apresentador (para ver notas)
- [ ] Timer visível

---

### DURANTE A APRESENTAÇÃO:

#### Dicas de Ouro:

**✅ FAÇA:**
- Olhe para a audiência, não para os slides
- Use controle remoto para avançar slides
- Pause nos slides importantes
- Faça perguntas ao público
- Use laser pointer (se necessário)
- Tenha água por perto

**❌ NÃO FAÇA:**
- Ler os slides palavra por palavra
- Ficar de costas para o público
- Avançar muito rápido
- Pular slides importantes
- Deixar slide errado na tela

#### Modo Apresentador:

**PowerPoint:**
- Exibição > Modo de Apresentação
- Você vê: slide atual, próximo slide, notas, timer
- Público vê: apenas slide atual

**Google Slides:**
- Apresentar > Modo apresentador
- Mesmas funcionalidades

---

## 🎨 RECURSOS VISUAIS GRATUITOS

### Imagens e Ícones:

**Sites gratuitos:**
- [Unsplash](https://unsplash.com) - Fotos de alta qualidade
- [Pexels](https://pexels.com) - Fotos e vídeos
- [Flaticon](https://flaticon.com) - Ícones
- [Freepik](https://freepik.com) - Vetores e imagens

**Buscar por:**
- "leadership" (liderança)
- "teamwork" (trabalho em equipe)
- "mentor" (mentoria)
- "church" (igreja)
- "community" (comunidade)
- "helping hands" (mãos ajudando)

### Ícones para os slides:

**Conceitos do curso:**
- 🌉 Ponte - para "líder como ponte"
- 🌱 Semente - para "multiplicação"
- ❤️ Coração - para "cuidar de pessoas"
- 🎯 Alvo - para "objetivos"
- ✅ Check - para "completar"
- 🙌 Mãos - para "servir"

---

## 📝 CHECKLIST DE CONVERSÃO

### Para cada arquivo de slides:

- [ ] Criar apresentação nova (PowerPoint/Google Slides)
- [ ] Definir template e cores
- [ ] Adicionar logo da ADMC (se houver)
- [ ] Converter todos os slides (um por um)
- [ ] Formatar títulos e textos
- [ ] Adicionar imagens/ícones relevantes
- [ ] Inserir versículos com formatação especial
- [ ] Adicionar notas do apresentador
- [ ] Revisar ortografia
- [ ] Testar em projetor
- [ ] Criar backup
- [ ] Pronto! ✅

---

## 💡 DICAS ESPECÍFICAS POR TIPO DE SLIDE

### SLIDE DE VERSÍCULO:

**Design sugerido:**
- Fundo com imagem sutil (céu, natureza)
- Texto do versículo em BRANCO ou cor clara
- Fonte maior (28-32pt)
- Referência menor em itálico
- Centralizado

**Exemplo:**
```
Fundo: Imagem desfocada de céu azul

        "A seara é grande, mas poucos
         são os trabalhadores"

              Mateus 9:37-38
```

---

### SLIDE DE TABELA COMPARATIVA:

**Design sugerido:**
- 2 colunas lado a lado
- Cores diferentes para cada lado
- Linhas alternadas

**Exemplo: Ovelhas vs Trabalhadores**

```
╔════════════════╦════════════════╗
║   OVELHAS      ║ TRABALHADORES  ║
╠════════════════╬════════════════╣
║ Pastoreio      ║ Aperfeiçoamento║
║ Consolo        ║ Desafio        ║
║ Cuidado        ║ Propósito      ║
╚════════════════╩════════════════╝
```

---

### SLIDE DE LISTA COM CHECKS:

**Design sugerido:**
- Usar ícones de check (✅) ao invés de bullets
- Animação: aparecer um por um
- Cores alternadas (opcional)

**Exemplo:**
```
OBJETIVOS DO ENCONTRO:

✅ Identificar diferença entre ovelha e trabalhador
✅ Compreender identidade do líder servo
✅ Cuidar de pessoas, não de funções
✅ Reconhecer comportamentos de ponte ou barreira
```

---

### SLIDE DE CITAÇÃO:

**Design sugerido:**
- Aspas grandes decorativas
- Texto em itálico
- Fundo colorido ou imagem
- Autor/fonte menor

**Exemplo:**
```
╔══════════════════════════════════════╗
║                                      ║
║   "                                  ║
║                                      ║
║   Multiplicar é mais                 ║
║   poderoso do que reter              ║
║                                      ║
║                              "       ║
║                                      ║
╚══════════════════════════════════════╝
```

---

### SLIDE DE REFLEXÃO/PERGUNTAS:

**Design sugerido:**
- Fundo mais escuro
- Perguntas em branco ou amarelo
- Ícone de interrogação
- Tempo para silêncio

**Exemplo:**
```
╔══════════════════════════════════════╗
║  🤔 REFLEXÃO PESSOAL                 ║
║                                      ║
║  Pergunte-se:                        ║
║                                      ║
║  • Como as pessoas me veem?          ║
║  • Estou formando ou usando pessoas? ║
║  • Sou ponte ou barreira?            ║
║                                      ║
╚══════════════════════════════════════╝
```

---

## 🎯 CUSTOMIZAÇÃO PARA A ADMC

### Elementos a adicionar:

1. **Logo da ADMC**
   - No rodapé de todos os slides
   - Ou na primeira e última página

2. **Cores da igreja**
   - Use paleta de cores oficial
   - Mantenha identidade visual

3. **Fotos da igreja**
   - Equipe de liderança
   - Ministérios em ação
   - Comunidade servindo

4. **Versículo tema da igreja**
   - Se houver, adicionar em slide especial

5. **Informações de contato**
   - No último slide
   - Redes sociais da igreja

---

## 📱 COMPARTILHAMENTO E BACKUP

### Onde salvar:

**Nuvem (recomendado):**
- Google Drive (compartilhamento fácil)
- OneDrive (integrado ao PowerPoint)
- Dropbox

**Backup local:**
- Computador
- Pen drive
- HD externo

### Formatos para salvar:

1. **.pptx** (PowerPoint) - editável
2. **.pdf** - backup não editável
3. **.odp** (LibreOffice) - compatibilidade

**Salve sempre 2-3 versões em locais diferentes!**

---

## ⚠️ RESOLUÇÃO DE PROBLEMAS

### "As fontes não aparecem direito"

**Solução:**
- Use fontes do sistema (Arial, Calibri)
- Ou incorpore fontes ao salvar (PowerPoint > Salvar Como > Ferramentas > Incorporar fontes)

### "Os emojis não aparecem"

**Solução:**
- Substitua por ícones
- Ou use imagens de emojis
- Site: https://emojipedia.org

### "O vídeo não roda"

**Solução:**
- Não use vídeos embutidos
- Use links do YouTube
- Teste antes da apresentação

### "O projetor não conecta"

**Solução:**
- Leve adaptadores (HDMI, VGA, USB-C)
- Tenha versão em PDF como backup
- Teste com antecedência

---

## ✅ CHECKLIST FINAL ANTES DO DIA

- [ ] Apresentação criada e formatada
- [ ] Testada em outro computador
- [ ] Backup em 3 lugares
- [ ] Fontes compatíveis
- [ ] Imagens carregadas
- [ ] Notas do apresentador adicionadas
- [ ] Ortografia revisada
- [ ] Timer configurado
- [ ] Testada em projetor/TV
- [ ] Controle remoto funcionando
- [ ] PRONTO PARA APRESENTAR! 🎉

---

## 🎓 RECURSOS ADICIONAIS

### Tutoriais em vídeo:

**YouTube:**
- "Como fazer slides profissionais no PowerPoint"
- "Design de apresentações minimalistas"
- "Dicas para apresentar em público"

### Cursos gratuitos:

- Canva Design School
- Google Workspace Learning Center
- Microsoft Office Training

---

## 💪 VOCÊ CONSEGUE!

Criar os slides pode parecer trabalhoso, mas:

✅ O conteúdo já está pronto (nos arquivos .md)  
✅ É só copiar, colar e formatar  
✅ Você pode fazer aos poucos  
✅ O resultado será incrível!  

**Tempo estimado:** 3-4 horas para ambos os encontros

---

## 📞 PRECISA DE AJUDA?

Se tiver dificuldades técnicas:

1. Peça ajuda a alguém da equipe de mídia da igreja
2. Assista tutoriais no YouTube
3. Use versão mais simples (sem muitas formatações)
4. O conteúdo é mais importante que o design!

---

**Lembre-se:** O mais importante não são os slides perfeitos, mas o coração transformado dos participantes! 💙

---

**Elaborado para o Curso de Liderança e Obreiros - ADMC Sede 2026**

*"Multiplicar é mais poderoso que reter"*
