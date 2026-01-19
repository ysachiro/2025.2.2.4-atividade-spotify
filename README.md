# Atividade Spotify (2025.2.2.4)
Atividade avaliativa de reprodução de UI Web a partir de imagem

## Sumário
1. [Objetivo](#objetivo)
2. [Protótipos](#protótipos)
3. [Checklist de Implementação](#checklist-de-implementação)
   - [Preparação](#preparação)
   - [Estrutura HTML](#estrutura-html)
   - [Estilização CSS3 Mobile First](#estilização-css3-mobile-first)
   - [Responsividade](#responsividade)
   - [Finalização](#finalização)

---

## Objetivo
Reproduzir a interface de usuário do Spotify utilizando HTML5 e CSS3 externo com abordagem mobile-first, baseando-se nos protótipos fornecidos.

## Protótipos
Os protótipos de referência estão disponíveis no diretório `prototipos/`:
- `spotify-mobile.png` - [Design para dispositivos móveis](prototipos/spotify-mobile.png)
- `spotify-desktop.png` - [Design para desktop](prototipos/spotify-desktop.png)

---

## Checklist de Implementação

---

### Preparação
- [X] Analisar os protótipos mobile e desktop
- [X] Identificar os componentes principais da interface
- [X] Planejar a estrutura semântica do HTML
- [X] Definir breakpoints para responsividade

---

### Estrutura HTML
- [X] Criar arquivo `index.html` na raiz do projeto
- [X] Configurar a estrutura básica HTML5:
  - [X] Adicionar `<!DOCTYPE html>`
  - [X] Configurar tag `<html>` com atributo `lang="pt-BR"`
  - [X] Criar seção `<head>` com:
    - [X] Meta charset UTF-8
    - [X] Meta viewport para responsividade
    - [X] Tag `<title>` apropriada
    - [X] Link para arquivo CSS externo
- [X] Estruturar o `<body>` com elementos semânticos:
  - [X] Header (cabeçalho/navegação)
  - [X] Main (conteúdo principal)
  - [X] Footer (rodapé)
- [X] Adicionar conteúdo textual e imagens conforme protótipo mobile

---

### Estilização CSS3 Mobile First
- [X] Criar arquivo `spotify.css` (recomendado: criar pasta `css/` e salvar como `css/spotify.css`)
- [X] Configurar reset/normalize CSS:
  - [X] Remover margens e paddings padrão
  - [X] Definir box-sizing como border-box
- [X] Implementar estilos base (mobile first):
  - [X] Tipografia (fontes, tamanhos, cores)
  - [X] Cores de fundo
  - [X] Espaçamentos (margins e paddings)
  - [X] Layout flexbox ou grid
- [X] Estilizar componentes específicos:
  - [X] Barra de navegação/header
  - [X] Cards ou seções de conteúdo
  - [X] Botões e elementos interativos
  - [X] Imagens e ícones
  - [X] Footer
- [X] Aplicar efeitos CSS3:
  - [X] Transições
  - [X] Sombras (box-shadow)
  - [X] Bordas arredondadas (border-radius)
  - [X] Gradientes (se aplicável)

---

### Responsividade
- [X] Implementar media queries para tablet (min-width: 768px):
  - [X] Ajustar layouts
  - [X] Modificar tamanhos de fonte
  - [X] Reorganizar elementos se necessário
- [X] Implementar media queries para desktop (min-width: 1024px):
  - [X] Aplicar layout do protótipo desktop
  - [X] Ajustar larguras máximas
  - [X] Otimizar espaçamentos
- [X] Testar em diferentes tamanhos de tela (sugestão: 320px, 768px, 1024px, 1440px) usando DevTools do navegador

---

### Finalização
- [X] Testar a página em navegadores diferentes (Chrome, Firefox, Safari, Edge)
- [X] Verificar acessibilidade básica:
  - [X] Alt text em imagens
  - [X] Contraste de cores adequado
  - [X] Estrutura de headings hierárquica
- [X] Validar CSS em https://jigsaw.w3.org/css-validator/
- [X] Otimizar performance:
  - [X] Comprimir imagens se necessário
  - [X] Remover código CSS não utilizado
     
---

### Observações

- as imagens e artistas são da conta real do professor
- pode utilizar as mesmas imagens do protótipo ou pegar suas próprias imagens
- as imagens devem ser colocadas em uma pasta, sugestão `imagens`
- deve ter mais que 3 itens em cada _carousel_
- [X] Documentar decisões técnicas (se necessário)
- [X] Fazer commit final do projeto
