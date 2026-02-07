# 🏫 Imagens Realistas de Escola para Fundos

## Imagens Aplicadas no Site

### 1. **Hero Section (Seção Principal)**
```
Fundo: Sala de aula com carteiras
URL: https://images.unsplash.com/photo-1427504494785-3a9ca7044f45?w=1920&q=80
Opacidade: 90% overlay branco
Descrição: Sala de aula moderna e organizada
```

### 2. **Imagem Principal Hero**
```
Crianças estudando felizes
URL: https://images.unsplash.com/photo-1503676260728-1c00da094a0b?w=800&q=80
Estilo: Moldura branca com rotação 2°
Descrição: Grupo de crianças estudando juntas
```

### 3. **Seção Sobre (Quadro Negro)**
```
Fundo: Quadro negro/lousa
Estilo: Gradiente escuro (#1f2937 to #111827)
Borda: Madeira marrom (#92400e)
Texto: Efeito giz branco
```

### 4. **Seção Serviços**
```
Fundo: Sala de aula vista de trás
URL: https://images.unsplash.com/photo-1427504494785-3a9ca7044f45?w=1920&q=80
Opacidade: 5%
Descrição: Perspectiva de aluno vendo o quadro
```

## 📚 Outras Imagens Realistas Disponíveis

### Salas de Aula
```
1. Sala de aula vazia e organizada
https://images.unsplash.com/photo-1580582932707-520aed937b7b?w=1920&q=80

2. Sala de aula com decoração infantil
https://images.unsplash.com/photo-1588072432836-e10032774350?w=1920&q=80

3. Biblioteca escolar
https://images.unsplash.com/photo-1497633762265-9d179a990aa6?w=1920&q=80

4. Corredor de escola
https://images.unsplash.com/photo-1509062522246-3755977927d7?w=1920&q=80

5. Quadro branco com anotações
https://images.unsplash.com/photo-1581726707445-75cbe4efc586?w=1920&q=80
```

### Materiais Escolares
```
6. Mesa com livros e cadernos
https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=1920&q=80

7. Estante de livros coloridos
https://images.unsplash.com/photo-1481627834876-b7833e8f5570?w=1920&q=80

8. Lápis de cor organizados
https://images.unsplash.com/photo-1513364776144-60967b0f800f?w=1920&q=80

9. Cadernos abertos
https://images.unsplash.com/photo-1517842645767-c639042777db?w=1920&q=80

10. Mochila escolar
https://images.unsplash.com/photo-1577896851231-70ef18881754?w=1920&q=80
```

### Crianças Estudando
```
11. Grupo de crianças lendo
https://images.unsplash.com/photo-1503676260728-1c00da094a0b?w=1920&q=80

12. Criança concentrada escrevendo
https://images.unsplash.com/photo-1588072432836-e10032774350?w=1920&q=80

13. Alunos levantando a mão
https://images.unsplash.com/photo-1546410531-bb4caa6b424d?w=1920&q=80

14. Crianças em círculo
https://images.unsplash.com/photo-1503676382389-4809596d5290?w=1920&q=80

15. Estudante com tablet
https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1920&q=80
```

### Professores e Ensino
```
16. Professor no quadro
https://images.unsplash.com/photo-1524178232363-1fb2b075b655?w=1920&q=80

17. Professora ajudando aluno
https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=1920&q=80

18. Aula em grupo pequeno
https://images.unsplash.com/photo-1509062522246-3755977927d7?w=1920&q=80

19. Professor sorrindo
https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=1920&q=80

20. Tutoria individual
https://images.unsplash.com/photo-1544717297-fa95b6ee9643?w=1920&q=80
```

## 🎨 Como Usar as Imagens de Fundo

### Exemplo 1: Fundo com Overlay
```html
<div class="absolute inset-0 z-0">
    <img src="URL_DA_IMAGEM" 
         alt="Descrição" 
         class="w-full h-full object-cover">
    <div class="absolute inset-0 bg-white/90"></div>
</div>
```

### Exemplo 2: Fundo com Opacidade Baixa
```html
<div class="absolute inset-0 z-0">
    <img src="URL_DA_IMAGEM" 
         alt="Descrição" 
         class="w-full h-full object-cover opacity-10">
</div>
```

### Exemplo 3: Fundo Fixo (Parallax)
```html
<div class="fixed inset-0 z-0">
    <img src="URL_DA_IMAGEM" 
         alt="Descrição" 
         class="w-full h-full object-cover opacity-5">
</div>
```

## 🎯 Recomendações de Uso

### Hero Section
- **Imagem**: Sala de aula moderna
- **Overlay**: 85-95% branco
- **Objetivo**: Profissionalismo e clareza

### Seção Sobre
- **Imagem**: Quadro negro ou biblioteca
- **Overlay**: Escuro para contraste
- **Objetivo**: Ambiente educacional

### Seção Serviços
- **Imagem**: Crianças estudando
- **Overlay**: 95% branco (muito sutil)
- **Objetivo**: Foco nos cards

### Seção Depoimentos
- **Imagem**: Pais e filhos
- **Overlay**: 90% branco
- **Objetivo**: Confiança e proximidade

### Seção Contato
- **Imagem**: Entrada da escola
- **Overlay**: 85% branco
- **Objetivo**: Acolhimento

## 💡 Dicas de Otimização

1. **Tamanho**: Use w=1920 para fundos full-width
2. **Qualidade**: q=80 é ideal (balanço qualidade/tamanho)
3. **Formato**: WebP quando possível
4. **Loading**: Use `loading="lazy"` para fundos
5. **Alt Text**: Sempre descreva a imagem

## 🔧 CSS Útil

```css
/* Fundo fixo com parallax */
.fundo-escola {
    background-image: url('URL');
    background-attachment: fixed;
    background-size: cover;
    background-position: center;
}

/* Overlay personalizável */
.overlay-branco {
    background: rgba(255, 255, 255, 0.9);
}

.overlay-escuro {
    background: rgba(0, 0, 0, 0.7);
}

/* Desfoque sutil */
.fundo-desfocado {
    filter: blur(3px);
}
```

## 📱 Responsividade

```html
<!-- Imagem diferente para mobile -->
<picture>
    <source media="(max-width: 768px)" 
            srcset="URL_MOBILE">
    <img src="URL_DESKTOP" alt="Descrição">
</picture>
```

---

**Nota**: Todas as imagens do Unsplash são gratuitas para uso comercial e não requerem atribuição (mas é recomendado).
