# Envelhecer com Saúde — cartilha digital

Site estático, gratuito e sem coleta de dados pessoais, preparado para o projeto de extensão da disciplina Programa de Integração Comunitária.

## Como abrir

1. Descompacte a pasta.
2. Abra `index.html` no navegador; todas as páginas e imagens são locais.
3. Para publicar, envie todo o conteúdo da pasta para uma hospedagem de sites estáticos (por exemplo, GitHub Pages ou Netlify). Não é necessário banco de dados nem servidor de aplicações.
4. Depois da publicação, crie um QR Code **do endereço público definitivo** (não de `index.html` local). Teste o QR Code com celulares diferentes e imprima o link curto abaixo dele.

## Páginas

- `index.html`: início e navegação.
- `alimentacao.html`: 10 opções de refeições, combinações de saladas e informações nutricionais expansíveis.
- `atividade-fisica.html`: atividades diárias, exercícios em casa e sarcopenia.
- `prevencao-quedas.html`: prevenção e checklist interativo.
- `cuidados-saude.html`: vacinação, medicamentos e acompanhamento na UBS.
- `ubs.html`: **página provisória**. Não declara quais serviços são prestados na UBS.
- `fontes.html`: links para fontes oficiais e científicas.

## Dados a personalizar antes da divulgação

- Substituir `[Faculdade a preencher]` no rodapé pelo nome da instituição.
- Inserir nome, endereço, contato, horários e **lista de serviços confirmados** em `ubs.html`, depois de validação com a unidade.
- Opcionalmente adicionar logotipos autorizados da faculdade e UBS e fotos das ações com autorização adequada.
- Validar em equipe as imagens educativas, as recomendações clínicas e as informações nutricionais antes da divulgação institucional.
- Revisar periodicamente o Calendário Nacional de Vacinação, sempre confrontando com as regras vigentes na época da ação.

## Informações nutricionais: ponto de revisão

O arquivo `dados/receitas_nutricionais_rascunho.json` documenta os ingredientes, porções individuais e estimativas de energia e nutrientes. Os valores usam **médias de referência aproximadas por 100 g/mL**, e `dados/valores_referencia_rascunho.csv` detalha os coeficientes. A apresentação está preparada para educação em saúde, mas o cálculo ainda é **preliminar**.

**Antes de publicação institucional, um nutricionista deve validar e ajustar**: tipo e corte dos alimentos, marca, rendimento após cocção, quantidade de sal e óleo, peso de cada porção e valores de composição extraídos das entradas específicas da TACO/TBCA. Fotos são ilustrativas e não mostram precisamente as porções calculadas. O preparo pode modificar valores; não usar os números como prescrição alimentar individual.

Fontes de consulta:
- TBCA (USP): https://www.tbca.net.br/
- TACO (Unicamp): https://www.nepa.unicamp.br/publicacoes/tabela-taco-excel/

## Serviços da UBS: página em rascunho

O arquivo `dados/servicos_ubs_pendentes.json` inclui **possibilidades NÃO CONFIRMADAS** apenas para orientar a equipe editorial. Essas sugestões não aparecem como serviços oferecidos na página dos pacientes. Preencha a partir do documento oficial disponibilizado pela UBS, retire os serviços não realizados e só então disponibilize os detalhes.

## Atualização e privacidade

- Site feito com HTML5, CSS3 e JavaScript puro, sem bibliotecas externas, cookies ou rastreadores.
- A lista de prevenção de quedas não transmite informações e não grava os itens marcados.
- Para fotos com participantes, obtenha autorizações pertinentes e siga as orientações da faculdade, UBS e LGPD.
- O site não oferece diagnóstico, prescrição ou agendamento.
- Data desta preparação: 13 de outubro de 2026.

## Arquivos de mídia

As fotos de refeições e a ilustração anatômica foram geradas para o projeto e estão na pasta `assets/img`. As fotos não devem ser entendidas como representação exata de quantidades. A ilustração de sarcopenia é conceitual, não uma imagem diagnóstica e não apresenta idades específicas.

## Sugestão de próximos passos operacionais

Revisão pela equipe docente/profissionais da UBS → completar dados institucionais → testar acessibilidade e visual em diferentes aparelhos → hospedar → gerar QR Code do endereço final → testar durante uma ação piloto.
