
2. Contextualização do Papel da TI em Relação à LGPD
2.1 Aplicação da LGPD nas Tarefas da TI
O setor de Tecnologia da Informação da Melhores Compras tem papel central na proteção dos dados pessoais. No dia a dia, a equipe lida com o controle e o tratamento de informações de clientes, funcionários e parceiros — desde dados básicos, como nome e e-mail, até informações sensíveis como CPF, data de nascimento, histórico de compras, visualizações de vídeo e atendimentos via SAC.

A TI deve garantir que:
	Acesso aos dados esteja restrito: Utilizar autenticação segura (login/senha, autenticação multifator) e controle por perfil de acesso.
	Dados sejam armazenados com segurança: Utilizar criptografia, firewalls e backups regulares.
	Logs de acesso e alterações sejam monitorados: Para rastrear quem acessou ou modificou informações.
	Dados de colaboradores e funcionários estejam protegidos: Salários, avaliações, e dados pessoais dos funcionários, como CPF e data de nascimento, devem ser tratados com o mesmo rigor aplicado aos clientes.
	Requisições dos titulares sejam atendidas: Os sistemas precisam permitir a exclusão, correção ou portabilidade dos dados conforme solicitado pelos usuários.

2.2 Aplicação da LGPD na Plataforma de ecommerce
A plataforma de e-commerce da Melhores Compras coleta e trata dados sensíveis dos clientes, como:
	Nome completo, CPF, e-mail, telefone e endereço completo
	Preferências e histórico de compras
	Interações com vídeos de produtos (data e horário da visualização, tempo assistido)
	Atendimentos registrados no SAC (incluindo satisfação do cliente)

Para garantir o cumprimento da LGPD, a TI deve assegurar:
	Consentimento explícito: Os usuários precisam autorizar o uso dos dados de forma clara e objetiva.
	Política de privacidade acessível: Explicando quais dados são coletados, por que e como serão usados.
	Mecanismos de revogação do consentimento e acesso aos dados: O cliente pode, por exemplo, visualizar o histórico de visualizações de vídeos ou pedir a exclusão de dados do SAC.
	Anonimização de dados em relatórios analíticos: Utilizar dados de forma agregada e não identificável.

3. Recomendações de Proteção aos Dados
3.1 Recomendação 1: Controle de Acesso com Perfis e Autenticação Multifator
Descrição:
Implementar um sistema de controle de acesso com autenticação por múltiplos fatores (2FA, MFA, FIDO2), combinado a perfis de permissão. Funcionários de SAC, por exemplo, devem acessar apenas os dados necessários para seu atendimento.
Benefícios:
Reduz o risco de vazamentos de dados por acessos indevidos e limita a exposição de informações sensíveis, como CPF, e-mail ou dados de SAC. Melhora a segurança e fortalece a conformidade com os princípios da LGPD.

3.2 Recomendação 2: Anonimização de Dados para Relatórios Analíticos
Descrição:
Criar rotinas automáticas de anonimização para dados utilizados em relatórios gerenciais, como preferências de produtos, visualizações de vídeo e registros do SAC. Os dados devem ser tratados de forma agregada, sem associação direta ao cliente.
Benefícios:
Permite que a empresa continue gerando insights estratégicos sem comprometer a privacidade individual dos clientes. Garante o cumprimento do princípio da necessidade e minimização da LGPD, que orienta o uso apenas do necessário.

4. Anonimização
4.1 Relação de Dados de Clientes Disponíveis na Plataforma
A empresa coleta e trata os seguintes dados de clientes:
	Nome completo
	CPF
	Data de nascimento
	Sexo biológico e identidade de gênero
	Endereço completo (logradouro, número, complemento, bairro, cidade, estado, CEP)
	E-mail
	Telefone
	Nome de login e senha
	Histórico de compras e valores gastos
	Preferências de produtos
	Visualizações de vídeos de produtos (data, hora, tempo assistido)
	Interações com o SAC (mensagens, nível de satisfação, tempo de resposta)

4.2 Definição de Dados para Anonimização
Dado 1: CPF
Justificativa:
O CPF é um identificador único e sensível. Sua exposição pode causar sérios prejuízos ao titular, como fraudes e golpes. Em relatórios gerenciais, ele deve ser substituído por identificadores anônimos.

Dado 2: Endereço completo
Justificativa:
O endereço, quando associado a outros dados (como nome e e-mail), permite a identificação precisa do cliente. Para análises de comportamento por região, é suficiente manter apenas a cidade ou estado — descartando rua e número.

Referências
BRASIL. Lei nº 13.709, de 14 de agosto de 2018. Lei Geral de Proteção de Dados Pessoais (LGPD).
DONEDA, L. Da Privacidade à Proteção de Dados Pessoais. Revista dos Tribunais, 2019.
MACHADO, D. F. Proteção de Dados Pessoais: A LGPD e os Desafios para as Empresas. Atlas, 2021.
