# 🏷️ Editor de Etiquetas Inteligente

Sistema de precificação e automação comercial desenvolvido para transformar valores de compra bruta em etiquetas de venda unitária de forma rápida e eficiente. O projeto simula um terminal de gôndola profissional, com suporte a leitura de códigos e gerenciamento de estoque local.

## 🚀 Funcionalidades

- **Cálculo de Margem Automático:** Processa o valor da caixa, divide pelas unidades e aplica margens de lucro de 10% a 50% com um clique.
- **Busca Inteligente:** Identifica produtos automaticamente através de um banco de dados interno ou códigos salvos anteriormente.
- **Persistência de Dados (Hybrid Storage):** Utiliza um banco fixo em JavaScript e permite o cadastro de novos produtos via `LocalStorage` do navegador.
- **Interface de Cadastro:** Caso um código bipado não seja reconhecido, o sistema abre uma janela (Modal) para cadastro imediato da descrição.
- **Modo de Impressão Otimizado:** Formatação CSS específica para gerar etiquetas limpas (apenas Nome, Preço e Código), prontas para impressoras térmicas ou folha A4.

## 🛠️ Tecnologias Utilizadas

- **HTML5** | **CSS3** | **JavaScript (ES6+)**
- **Google Fonts:** Fonte `Libre Barcode 39` para geração visual de códigos de barras.

## 📖 Como Usar (Passo a Passo)

Para operar o sistema, siga estas etapas simples:

1. **Entrada de Identificação:**
   - No campo **"Código do Produto"**, use um leitor de código de barras físico (bipar) ou digite manualmente o código (EAN/PLU).
   - O sistema buscará automaticamente o nome do produto. Se for um código novo, um aviso aparecerá.

2. **Dados de Custo:**
   - Insira o **"Valor Bruto"** (quanto você pagou pela caixa fechada).
   - Insira a **"Qtd. Unidades"** (quantos itens vêm dentro dessa caixa).

3. **Precificação:**
   - Clique em um dos botões de **Margem de Lucro** (10%, 20%, 30%, 40% ou 50%). O sistema calculará o preço final de venda unitário automaticamente.

4. **Geração e Cadastro:**
   - Clique em **"Gerar Etiqueta"**. 
   - *Nota:* Se o produto não estiver cadastrado, uma caixa de diálogo abrirá. Digite o nome do produto e clique em **"Salvar"**.

5. **Finalização e Impressão:**
   - Confira a etiqueta gerada no final da página.
   - Clique no botão verde **"Imprimir"**. O sistema abrirá a janela de impressão configurada para ocultar os formulários e imprimir apenas a etiqueta.

6. **Zerar Sistema:**
   - Use o botão **"Zerar"** para limpar todos os campos e iniciar uma nova precificação rapidamente.

---

## 👤 Desenvolvedor

**Márcio Alexandre** *Especialista em TI e Desenvolvedor focado em Automação Comercial.*

---
Este projeto faz parte do meu portfólio de soluções em tecnologia da informação.
