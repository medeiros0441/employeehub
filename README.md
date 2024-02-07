Employee Hub PJ - Software de Gestão de Vagas

Bem-vindo ao Employee Hub PJ, um software web desenvolvido em .NET 4.8 utilizando WebForms. Este sistema oferece funcionalidades abrangentes para gerenciamento de vagas, destinado a dois tipos de usuários: empresas e profissionais.
Funcionalidades Principais
Para Empresas

    Criação e publicação de vagas disponíveis.
    Busca por profissionais e análise de seus currículos gerados por meio do C# com o auxílio de bibliotecas como iTextSharp para a geração de PDFs.
    Edição e cadastro de perfis de empresa para que os profissionais possam visualizar as vagas disponíveis.

Para Profissionais

    Geração de currículo em PDF ou armazenamento de um já existente.
    Criação, exclusão e edição de informações como experiências profissionais e certificações.
    Atualização do perfil e candidatura a vagas disponíveis.

Processo de Cadastro de Vagas

Oferecemos duas opções para o cadastro de vagas:

    Cadastro a partir do Login:
        Empresas podem cadastrar vagas de forma detalhada.

    Cadastro Simplificado:
        Profissionais inserem informações básicas como nome, e-mail e WhatsApp.
        O currículo é enviado mediante upload.
        A empresa recebe um e-mail com as informações do profissional que se candidatou.

Estrutura do Projeto

    BLL (Business Logic Layer): Responsável pela conexão com o DAL e pelas verificações.
    DTO (Data Transfer Object): Armazena os modelos.
    DAL (Data Access Layer): Responsável pela conexão com o banco de dados SQL Server, contendo todas as operações CRUD necessárias para o funcionamento do software.

Por razões de segurança, apenas o front-end é visível. O back-end foi construído utilizando bibliotecas .NET Framework.

Sinta-se à vontade para explorar e melhorar a documentação do projeto conforme necessário. Estamos comprometidos com a qualidade e eficiência na gestão de vagas.
