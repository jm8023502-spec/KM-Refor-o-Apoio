# 🚀 Guia Rápido: Substituir Imagens no Site

## 📋 Checklist de Imagens Necessárias

### Seção Hero (1 imagem)
- [ ] **Hero Principal**: Crianças estudando felizes (1920x1080)
  - Localização: Linha ~770
  - Atual: `photo-1503676260728-1c00da094a0b`

### Seção Serviços (4 imagens)
- [ ] **Acompanhamento Escolar**: Estudante com material (1000x800)
  - Localização: Linha ~899
  - Atual: `photo-1434030216411-0b793f4b4173`

- [ ] **Revisão de Conteúdos**: Criança revisando (1000x800)
  - Localização: Linha ~926
  - Atual: `photo-1513475382585-d06e58bcb0e0`

- [ ] **Foco nas Dificuldades**: Professor ajudando (1000x800)
  - Localização: Linha ~949
  - Atual: `photo-1571019613454-1cb2f99b2d8b`

- [ ] **Atendimento Especializado**: Apoio TEA/TDAH (1000x800)
  - Localização: Linha ~976
  - Atual: `photo-1544717297-fa95b6ee9643`

### Seção Diferenciais (3 imagens)
- [ ] **Material Didático**: Livros e cadernos (1000x800)
  - Localização: Linha ~1411
  - Atual: `photo-1481627834876-b7833e8f5570`

- [ ] **Aprender Brincando**: Jogos educativos (1000x800)
  - Localização: Linha ~1432
  - Atual: `photo-1606092195730-5d7b9af1efc5`

- [ ] **Ambiente Acolhedor**: Sala colorida (1000x800)
  - Localização: Linha ~1453
  - Atual: `photo-1503676260728-1c00da094a0b`

### Seção Depoimentos (4 imagens)
- [ ] **Background**: Crianças felizes estudando (1469x980)
  - Localização: Linha ~1478
  - Atual: `photo-1497486751825-1233686d5d80`

- [ ] **Ana Paula**: Foto de mãe (400x400)
  - Localização: Linha ~1493
  - Atual: `photo-1544005313-94ddf0286df2`

- [ ] **Roberto Silva**: Foto de pai (400x400)
  - Localização: Linha ~1512
  - Atual: `photo-1472099645785-5658abf4ff4e`

- [ ] **Mariana Costa**: Foto de mãe (400x400)
  - Localização: Linha ~1531
  - Atual: `photo-1438761681033-6461ffad8d80`

---

## 🔧 Como Substituir as Imagens

### Método 1: Usando Unsplash (Recomendado)

1. **Acesse**: https://unsplash.com
2. **Busque**: "children studying" ou "school classroom"
3. **Copie a URL** da imagem escolhida
4. **Formate** a URL:
   ```
   https://images.unsplash.com/photo-[ID]?w=1200&q=80
   ```

### Método 2: Usando Suas Próprias Imagens

1. **Otimize** a imagem:
   - Use https://tinypng.com para comprimir
   - Redimensione para o tamanho correto
   - Converta para WebP (opcional)

2. **Hospede** a imagem:
   - **GitHub**: Coloque na pasta `/images`
   - **Imgur**: Upload gratuito
   - **Cloudinary**: CDN gratuito

3. **Use** a URL completa no código

### Método 3: Gerando com IA

1. **Escolha** uma ferramenta (Leonardo.ai é grátis)
2. **Use** os prompts do arquivo `GERAR-IMAGENS-IA.md`
3. **Baixe** a imagem gerada
4. **Siga** o Método 2 acima

---

## 📝 Exemplo Prático de Substituição

### Antes:
```html
<img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2022&q=80" 
     alt="Crianças estudando com alegria" 
     class="w-full h-72 object-cover rounded-lg">
```

### Depois (Nova imagem do Unsplash):
```html
<img src="https://images.unsplash.com/photo-1588072432836-e10032774350?w=1200&q=80" 
     alt="Crianças estudando com alegria" 
     class="w-full h-72 object-cover rounded-lg">
```

### Depois (Imagem própria hospedada):
```html
<img src="./images/hero-criancas-estudando.jpg" 
     alt="Crianças estudando com alegria" 
     class="w-full h-72 object-cover rounded-lg">
```

---

## 🎨 Sugestões de Imagens por Seção

### Hero Section
**Buscar por**: "happy children studying together classroom"
**Características**: Colorida, alegre, grupo de crianças, iluminação natural

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1503676260728-1c00da094a0b?w=1920&q=80
2. https://images.unsplash.com/photo-1427504494785-3a9ca7044f45?w=1920&q=80
3. https://images.unsplash.com/photo-1497486751825-1233686d5d80?w=1920&q=80
```

### Acompanhamento Escolar
**Buscar por**: "student writing notebook homework"
**Características**: Criança concentrada, material escolar, ambiente organizado

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1434030216411-0b793f4b4173?w=1000&q=80
2. https://images.unsplash.com/photo-1588072432836-e10032774350?w=1000&q=80
3. https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=1000&q=80
```

### Revisão de Conteúdos
**Buscar por**: "children reviewing studying books"
**Características**: Livros abertos, revisão, concentração

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1513475382585-d06e58bcb0e0?w=1000&q=80
2. https://images.unsplash.com/photo-1512820790803-83ca734da794?w=1000&q=80
3. https://images.unsplash.com/photo-1497633762265-9d179a990aa6?w=1000&q=80
```

### Foco nas Dificuldades
**Buscar por**: "teacher helping student one on one"
**Características**: Professor e aluno, atenção individual, apoio

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=1000&q=80
2. https://images.unsplash.com/photo-1509062522246-3755977927d7?w=1000&q=80
3. https://images.unsplash.com/photo-1524178232363-1fb2b075b655?w=1000&q=80
```

### Atendimento Especializado (TEA/TDAH)
**Buscar por**: "special education teacher child"
**Características**: Atenção especializada, ambiente calmo, materiais adaptados

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1544717297-fa95b6ee9643?w=1000&q=80
2. https://images.unsplash.com/photo-1503454537195-1dcabb73ffb9?w=1000&q=80
3. https://images.unsplash.com/photo-1509062522246-3755977927d7?w=1000&q=80
```

### Material Didático
**Buscar por**: "colorful school books supplies"
**Características**: Livros coloridos, material organizado, visual atraente

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1481627834876-b7833e8f5570?w=1000&q=80
2. https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=1000&q=80
3. https://images.unsplash.com/photo-1497633762265-9d179a990aa6?w=1000&q=80
```

### Aprender Brincando
**Buscar por**: "children playing educational games"
**Características**: Jogos, diversão, aprendizado lúdico

**Opções Unsplash**:
```
1. https://images.unsplash.com/photo-1606092195730-5d7b9af1efc5?w=1000&q=80
2. https://images.unsplash.com/photo-1587654780291-39c9404d746b?w=1000&q=80
3. https://images.unsplash.com/photo-1503676382389-4809596d5290?w=1000&q=80
```

### Depoimentos (Avatares)
**Buscar por**: "portrait parent smiling"
**Características**: Rostos amigáveis, expressões positivas, profissional

**Opções Unsplash**:
```
Mães:
1. https://images.unsplash.com/photo-1544005313-94ddf0286df2?w=400&q=80
2. https://images.unsplash.com/photo-1438761681033-6461ffad8d80?w=400&q=80

Pais:
1. https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=400&q=80
2. https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&q=80
```

---

## ⚡ Substituição Rápida com Buscar e Substituir

### No VS Code:

1. Pressione `Ctrl + H` (Windows) ou `Cmd + H` (Mac)
2. Cole a URL antiga no campo "Find"
3. Cole a URL nova no campo "Replace"
4. Clique em "Replace All"

### Exemplo:
**Find**: `photo-1503676260728-1c00da094a0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2022&q=80`

**Replace**: `photo-1588072432836-e10032774350?w=1200&q=80`

---

## ✅ Checklist Final

Após substituir as imagens:

- [ ] Todas as imagens carregam corretamente
- [ ] Textos alternativos (alt) estão apropriados
- [ ] Imagens estão otimizadas (tamanho < 500KB cada)
- [ ] Site carrega rápido (teste em https://pagespeed.web.dev)
- [ ] Imagens são responsivas em mobile
- [ ] Cores das imagens combinam com o design
- [ ] Todas as imagens têm boa qualidade
- [ ] Não há imagens quebradas (404)

---

## 🆘 Solução de Problemas

### Imagem não carrega:
- Verifique se a URL está correta
- Teste a URL diretamente no navegador
- Verifique se há caracteres especiais mal formatados

### Imagem muito grande:
- Use https://tinypng.com para comprimir
- Reduza a qualidade para q=70 ou q=60
- Redimensione para o tamanho exato necessário

### Imagem distorcida:
- Verifique a proporção (aspect ratio)
- Use `object-fit: cover` no CSS
- Ajuste as dimensões width/height

---

## 📞 Precisa de Ajuda?

Consulte os arquivos:
- `IMAGENS-ESCOLARES.md` - Lista completa de imagens prontas
- `GERAR-IMAGENS-IA.md` - Como criar imagens com IA

---

**Tempo estimado**: 30-60 minutos para substituir todas as imagens do site.
