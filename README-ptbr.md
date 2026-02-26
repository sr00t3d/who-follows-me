# 🕵️‍♂️ Who Follows Me?

[English](README.md)

![Licença](https://img.shields.io/github/license/sr00t3d/who-follows-me)
![Javascript](https://img.shields.io/badge/language-Javascript-green.svg)

<img width="700" src="who-follows-me-cover.webp" />

**Who Follows Me?** é uma extensão para navegador (Manifest V3) projetada para ajudar você a gerenciar suas conexões no Instagram de forma inteligente, visual e, acima de tudo, segura.

Diferente de outros apps que podem comprometer sua conta, esta ferramenta roda localmente no seu navegador, respeitando os limites da plataforma e mantendo seus dados privados.

## ✨ Principais Funcionalidades

- **Varredura Automática:** Identifica quem não te segue de volta, quem são seus seguidores mútuos, contas verificadas e perfis privados.
- **Filtros Avançados:** Organize sua lista com apenas um clique para focar em quem realmente importa.
- **Unfollow Seguro:** Sistema de *Safe-Mode* com ritmo adaptativo, cooldown automático e simulação para evitar bloqueios do Instagram.
- **Exportação de Dados:** Salve seus relatórios em formatos CSV ou JSON para análise externa.
- **Interface Moderna:** Layout compacto, suporte a microinterações, tooltips informativas e feedback visual de risco.
- **Multi-idioma:** Suporte nativo para Português (PT) e Inglês (EN) baseado nas configurações do seu navegador.

## 🛡️ Segurança em Primeiro Lugar

O Instagram possui políticas rígidas contra automações agressivas. O **Who Follows Me?** foi construído com camadas de proteção:
- **Modo Simulação:** Teste as ações antes de executá-las de verdade.
- **Proteção de Notas:** Perfis que você marcou com notas ou considerou importantes são protegidos contra unfollow acidental.
- **Fila de Falhas:** Se algo der errado, a extensão gerencia as tentativas automaticamente sem disparar alertas nativos chatos.

## 🚀 Como instalar (Desenvolvedor)

Como esta versão está em desenvolvimento, você pode instalá-la manualmente:

1. Faça o download ou clone este repositório.
2. Abra o seu navegador (Chrome, Edge, Brave ou Opera).
3. Vá para a página de Extensões (`chrome://extensions/`).
4. Ative o **"Modo do desenvolvedor"** no canto superior direito.
5. Clique em **"Carregar sem compactação"** e selecione a pasta onde os arquivos do projeto estão localizados.

## 💡 Como usar

1. Acesse o [Instagram](https://www.instagram.com) e faça login na sua conta.
2. Clique no ícone da extensão na sua barra de ferramentas.
3. A extensão abrirá uma interface integrada (modal) diretamente na página.
4. Aguarde o carregamento da lista e use os filtros para analisar seus seguidores.

## 🛠️ Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **Chrome Extension API (Manifest V3)**
- **CSS3** (Layouts dinâmicos e Blur de backdrop)
- **SweetAlert2** (Para feedbacks visuais elegantes)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
*Aviso: Este projeto não é afiliado, associado, autorizado, endossado por, ou de qualquer forma oficialmente conectado ao Instagram, Facebook ou Meta Platforms, Inc.*