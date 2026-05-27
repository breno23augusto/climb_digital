# Climb Digital — Landing Page

Landing page institucional da **Climb Digital**, agência de marketing e vendas. Site _single-page_ com foco em conversão, construído com HTML, CSS e JavaScript puros.

## Estrutura do Projeto

```
climb_digital_1/
├── index.html      # Página principal (SPA completa)
├── logo.png        # Logotipo da agência
├── partners.png    # Imagem de parceiros/clientes
```

## Funcionalidades

- **Design escuro** com identidade visual em vermelho e dourado
- **Parallax** nas montanhas do hero ao rolar a página
- **Scroll reveal** com animações de entrada nas seções
- **Contador animado** nas métricas com easing cúbico
- **Carrossel de depoimentos** com Swiper.js (embeds do Instagram)
- **Botão flutuante do WhatsApp** com tooltip
- **Barra de progresso** de leitura no topo
- **Totalmente responsivo** (mobile, tablet, desktop)

## Seções

| Seção         | Descrição                                      |
| ------------- | ---------------------------------------------- |
| Hero          | Chamada principal com CTA e estatísticas       |
| Social Proof  | Selos de parceiros (Meta, Google, RD Station)  |
| Problema      | Dores do cliente-alvo                          |
| Solução       | Serviços oferecidos (tráfego, inbound, CRO)    |
| Métricas      | Resultados + carrossel de depoimentos          |
| Método        | Processo de 4 etapas (diagnóstico ao topo)     |
| CTA Final     | Convite para consultoria gratuita              |
| Footer        | Dados da empresa e copyright                   |

## Como usar

1. Clone o repositório
2. Substitua `logo.png` e `partners.png` pelos assets reais
3. Altere a constante `WHATSAPP_NUMBER` no `<script>` para o número correto
4. Atualize os links dos Reels do Instagram no carrossel
5. Abra o `index.html` no navegador ou sirva com qualquer servidor estático

## Tecnologias

- HTML5 semântico
- CSS3 (custom properties, grid, flexbox, animações)
- JavaScript vanilla (Intersection Observer, requestAnimationFrame)
- [Swiper.js 11](https://swiperjs.com/) (carrossel)
- [Google Fonts](https://fonts.google.com/) (Bebas Neue, DM Sans)
