# 🌐 TechWave Solutions – Site Institucional

## Descrição
Site institucional fictício para uma empresa de tecnologia chamada **TechWave Solutions**.  
O objetivo é criar uma página **profissional, moderna e responsiva**, mostrando serviços, equipe e formas de contato.

---

## Estrutura do Site

### 1. Cabeçalho (Header)
- Logo da empresa: “TechWave Solutions”  
- Menu: Início | Sobre | Serviços | Equipe | Contato  
- Menu fixo no topo (sticky)  
- Fundo azul-escuro `#182A42`, texto branco

---

### 2. Hero (Seção Principal)
- Imagem de fundo com overlay (`linear-gradient`)  
- Título: “Transformando ideias em soluções digitais”  
- Subtítulo: “Desenvolvemos sistemas modernos e personalizados para o seu negócio.”  
- Botão: “Fale conosco” (link para a seção de contato)

---

### 3. Sobre
- Título: “Quem somos”  
- Texto sobre missão e valores da empresa  
- Imagem ao lado do texto (use `flex` ou `grid`)

---

### 4. Serviços
- Título: “Nossos Serviços”  
- 3 a 4 cards, cada um com:
  - Ícone ou emoji  
  - Título  
  - Descrição breve  
- Exemplo: Desenvolvimento Web, Soluções em Nuvem, Segurança Digital, Consultoria em TI

---

### 5. Equipe
- Título: “Nosso Time”  
- 3 a 4 cards com:
  - Foto (ou avatar) redonda  
  - Nome  
  - Cargo  

---

### 6. Depoimentos (Opcional)
- Título: “O que nossos clientes dizem”  
- 2 a 3 comentários curtos com nome da pessoa  

---

### 7. Contato
- Título: “Entre em Contato”  
- Formulário simples:
  - Nome  
  - Email  
  - Mensagem  
  - Botão “Enviar mensagem”  
- Ao lado (ou abaixo): endereço, telefone e redes sociais  

---

### 8. Rodapé (Footer)
- Texto: “© 2025 TechWave Solutions - Todos os direitos reservados.”  
- Fundo azul-escuro `#182A42`, texto branco, centralizado

---

## Cores e Estilo
- Fundo principal: `#F5F7FA`  
- Azul-escuro (menu e footer): `#182A42`  
- Azul-claro (destaques): `#3B82F6`  
- Texto principal: `#333333`  
- Texto secundário: `#555555`  
- Fontes sugeridas: Poppins, Inter ou Roboto  

---

## Responsividade
- Use media queries para telas pequenas:
  - Empilhar colunas (Serviços, Equipe)  
  - Ajustar fontes e padding  
  - Menu pode virar botão hambúrguer (visual)

---

## Estrutura de Pastas
```
responsive-event-form/
│
├── index.html
├── style.css
└── assets/
    ├── img/
    └── icons/
```
