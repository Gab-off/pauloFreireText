# Google Dorking: O Básico em 7 Minutos

## O que é Google Dorking?
- Técnica de pesquisa avançada no Google para encontrar informações não visíveis em buscas comuns
- Também chamada de "Google Hacking"
- Utiliza comandos especiais para buscar vulnerabilidades e dados sensíveis

## Por que é importante?
- Permite encontrar informações sigilosas expostas na internet
- Usada tanto por profissionais de segurança quanto por cibercriminosos
- No Brasil: forte impacto devido ao alto número de usuários online e casos de vazamentos

## Principais Comandos (O que realmente importa)

### site:
- Limita resultados a um domínio específico
- Exemplo: `site:gov.br confidencial`

### intitle:
- Busca texto no título das páginas
- Exemplo: `intitle:"painel de administração"`

### inurl:
- Busca texto específico nas URLs
- Exemplo: `inurl:admin`

### filetype:
- Busca tipos específicos de arquivos
- Exemplo: `filetype:pdf "confidencial"`

### Usos Práticos:
- Combinação: `site:exemplo.com.br filetype:xls senha`
- Câmeras: `intitle:webcamXP 5` (encontra câmeras sem proteção)
- Arquivos sensíveis: `filetype:log username password site:gov.br`

## Usos do Google Dorking

### Legítimos:
- Identificar vulnerabilidades em seus próprios sistemas
- Encontrar vazamentos de dados pessoais/empresariais
- Auditorias de segurança

### Maliciosos:
- Acesso a sistemas vulneráveis
- Coleta de dados para phishing
- Acesso a câmeras de segurança desprotegidas

## Casos Notáveis no Brasil
- Vazamento de chaves Pix
- Ataques ao Ministério da Saúde
- Vazamentos em grandes empresas (Netshoes, Enel)

## Como se Proteger (Essencial)

### Para Usuários:
- Use senhas fortes e autenticação de dois fatores
- Verifique suas próprias informações expostas
- Limite o que compartilha online

### Para Administradores:
- Use arquivos robots.txt para impedir indexação
- Configure corretamente permissões de acesso
- Verifique seu site usando as técnicas de dorking
- Remova conteúdo sensível dos mecanismos de busca

## Aspecto Legal
- A técnica não é ilegal, mas o uso pode ser
- O mau uso se enquadra na LGPD no Brasil
- Usar para acessar sistemas sem autorização é crime
