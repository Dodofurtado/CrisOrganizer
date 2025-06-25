# Configuração Google Ads - Página de Contato

## Arquivos Criados

### 1. contato.html
- Página de contato dedicada para campanhas do Google Ads
- URL: `seu-dominio.com/contato.html`
- Otimizada para conversões

## Configuração do Google Ads

### Passo 1: Substituir IDs de Conversão
No arquivo `contato.html`, substitua os seguintes placeholders:

```html
<!-- Linha 16: ID da conta Google Ads -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-SEU_ID_AQUI"></script>

<!-- Linha 21: ID da conta Google Ads -->
gtag('config', 'AW-SEU_ID_AQUI');

<!-- Linhas com onclick: IDs de conversão -->
onclick="gtag('event', 'conversion', {'send_to': 'AW-SEU_ID_AQUI/SEU_LABEL_WHATSAPP'});"
onclick="gtag('event', 'conversion', {'send_to': 'AW-SEU_ID_AQUI/SEU_LABEL_INSTAGRAM'});"
```

### Passo 2: Configurar Conversões no Google Ads
1. Acesse sua conta do Google Ads
2. Vá em "Ferramentas e configurações" > "Conversões"
3. Clique em "+" para criar nova conversão
4. Escolha "Website"
5. Configure as seguintes conversões:

#### Conversão WhatsApp:
- Nome: "Contato WhatsApp"
- Categoria: "Contato"
- Valor: Use o valor do seu serviço médio
- Contagem: "Uma"

#### Conversão Instagram:
- Nome: "Follow Instagram"
- Categoria: "Inscrição"
- Valor: Configure conforme estratégia
- Contagem: "Uma"

### Passo 3: Implementar os IDs
Após criar as conversões, copie os IDs e substitua no código:
- `AW-SEU_ID_AQUI` = ID da sua conta Google Ads
- `SEU_LABEL_WHATSAPP` = Label da conversão WhatsApp
- `SEU_LABEL_INSTAGRAM` = Label da conversão Instagram

## URLs para Campanhas

### URL Principal da Página:
```
https://seu-dominio.com/contato.html
```

### URLs com UTM para Tracking:
```
https://seu-dominio.com/contato.html?utm_source=google&utm_medium=cpc&utm_campaign=organizer&utm_content=contato
```

## Funcionalidades da Página

### ✅ Recursos Incluídos:
- Tracking de conversões Google Ads
- Design responsivo
- Botões de WhatsApp com mensagem personalizada
- Link para Instagram
- Visualização dos serviços
- Banner de urgência
- Animações suaves
- Botão flutuante do WhatsApp
- Backdrop blur effect moderno

### 📊 Eventos Rastreados:
- Cliques no WhatsApp
- Cliques no Instagram  
- Visualizações da página
- Conversões completas

## Otimizações SEO

### Meta Tags Incluídas:
- Title otimizado
- Meta description
- Meta keywords
- Favicon

### Estrutura para SEO:
- URLs amigáveis
- Texto relevante
- Call-to-actions claros
- Carregamento rápido

## Personalização

### Textos Personalizáveis:
- Mensagem do WhatsApp (identificando origem Google)
- Banner de urgência ("Resposta em até 2 horas!")
- Título e subtítulo da página

### Cores e Estilos:
- Variáveis CSS no topo do arquivo
- Esquema de cores: preto, dourado e prata
- Fácil personalização das cores
- Efeitos visuais modernos

## Teste da Implementação

### 1. Teste Local:
- Abra `contato.html` no navegador
- Verifique se todos os elementos carregam
- Teste os botões de contato

### 2. Teste de Conversão:
- Use o Google Tag Assistant
- Verifique se as conversões são registradas
- Teste em diferentes dispositivos

### 3. Teste de Performance:
- Use Google PageSpeed Insights
- Verifique tempo de carregamento
- Teste responsividade

## Monitoramento

### Métricas Importantes:
- Taxa de conversão da página
- Tempo na página
- Taxa de rejeição
- Cliques nos botões de contato

### Relatórios Google Ads:
- Conversões por fonte
- Custo por conversão
- ROI das campanhas
- Performance por dispositivo

## Integração com Site Principal

### Direcionamento:
- Botão "Fale comigo" da página principal deve apontar para `contato.html`
- Mantém o botão flutuante do WhatsApp
- Link de retorno para o site principal

### Consistência Visual:
- Mesma paleta de cores
- Mesma tipografia (Playfair Display + Poppins)
- Mesmo favicon
- Design coerente com a marca

## Manutenção

### Atualizações Regulares:
- Verificar funcionamento dos links
- Atualizar textos sazonais
- Monitorar performance
- Testar em novos dispositivos

### Backup:
- Manter backup dos arquivos
- Documentar mudanças
- Versionar modificações
