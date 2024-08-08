# Sistema Front-End com Dark Mode

Este é um sistema front-end básico desenvolvido em JavaScript, HTML e CSS. O sistema possui a funcionalidade de dark mode, permitindo que os usuários alternem entre o modo claro e o modo escuro. Este sistema é independente e ainda não está integrado com nenhum backend.

## Funcionalidades
- Alternar entre Modo Claro e Modo Escuro (Dark Mode)
- Interface Responsiva

## Pré-requisitos
- Navegador Web (Google Chrome, Mozilla Firefox, etc.)

## Passo a Passo para Rodar o Sistema Localmente

1. **Clonar o Repositório**
   - Clone o repositório do projeto para o seu ambiente local:
     ```bash
     git clone https://github.com/Gustavo-Vinicius-Santana/front-dark-mode
     cd front-dark-mode
     ```

4. **Configurar o Projeto**
   - Certifique-se de que todos os arquivos estejam na mesma pasta ou no servidor web local.
   - Não há necessidade de configuração adicional, pois o projeto é totalmente baseado em cliente (HTML, CSS, JavaScript).

3. **Executar o Projeto**
   - Abra o arquivo `index.html` em um navegador web.
   - Alternativamente, coloque todos os arquivos do projeto em um servidor web local (como XAMPP ou WAMP) na pasta `htdocs` e acesse através de `http://localhost/front-dark-mode`.

4. **Usar o Sistema**
   - **Alternar Dark Mode:** O sistema possui um botão de alternância (toggle) que permite ao usuário mudar entre o modo claro e o modo escuro. Ao clicar no botão, o tema da interface muda instantaneamente.

5. **Observações**
   - O dark mode é aplicado usando JavaScript para adicionar ou remover uma classe CSS específica que altera os estilos da página.
   - Como o sistema ainda não está integrado com o backend, as preferências do usuário (como o modo selecionado) são salvas na memoria cache após a recarga da página.
