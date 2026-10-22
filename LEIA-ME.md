# CRTE Conecta - Operação CRTE

Edição portátil para operação interna da equipe CRTE no computador local. Não é um formulário para os cursistas e não deve ser publicado ou compartilhado como link.

## Abrir
1. Extraia o ZIP completo para uma pasta de acesso restrito no computador da CRTE.
2. Abra `index.html` com um navegador moderno.
3. Use o mesmo computador, perfil do navegador e pasta. O armazenamento `file://` pode ser limitado por alguns navegadores.

## Importar respostas do Google Forms
1. Configure o Forms com estas perguntas/colunas: `Nome completo`, `Escola`, `Município`, `E-mail`, `Telefone com WhatsApp` e `Formação pretendida`.
2. Em `Formação pretendida`, use as opções `Curitiba (NRE-AMN)`, `Tunas`, `Itaperuçu`, `Cerro Azul` e `Pinhais`. Inclua no texto de ajuda: “Se a cidade do cursista não for um polo, escolha a cidade polo mais próxima.”
3. No Google Sheets de respostas, baixe a aba como CSV UTF-8. O aplicativo não lê diretamente arquivos XLSX.
4. Em `Eventos e inscrições`, escolha `Importar planilha CSV`, selecione o arquivo e confira a prévia. Só confirme depois de revisar as linhas válidas e ignoradas.

A importação valida cabeçalhos, campos obrigatórios, e-mail, telefone, polo conhecido, duplicidade por e-mail e vagas. Linhas com problemas são ignoradas e listadas na prévia. As inscrições são associadas ao evento do polo; em Curitiba, são distribuídas entre os dois encontros de acordo com a ocupação relativa e as vagas disponíveis. A escolha da cidade polo vem do Forms; o aplicativo não calcula distância geográfica.

A tela também permite cadastro manual com os mesmos campos, edição de eventos e polos, revisão/remoção de inscrições, exportação CSV e download de um modelo CSV vazio.

## Dados e privacidade
A versão começa sem inscrições. Eventos, datas, locais, regras regionais e capacidades são exemplos: revise-os antes de usar. Os cadastros ficam no perfil local do navegador; não há transmissão, sincronização, login ou criptografia pelo aplicativo. CSV e JSON podem conter dados pessoais. Restrinja dispositivo, pasta e cópias e siga os procedimentos institucionais de privacidade, guarda e descarte. Não registre senhas ou informações desnecessárias.

A planilha exportada do Google Forms contém dados pessoais. Baixe-a para um local autorizado, importe-a em equipamento da CRTE e remova cópias temporárias conforme as regras institucionais. Não compartilhe a planilha, o ZIP ou os backups em grupos ou links públicos.
