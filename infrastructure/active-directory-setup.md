# Configuração do Active Directory no Windows Server

Para utilizar Active Directory é necessário instalar e configurar o serviço em um servidor Windows.

## Etapas principais

### 1. Instalar Windows Server

Primeiro é necessário instalar o sistema operacional Windows Server.

### 2. Instalar a função Active Directory

No Server Manager, instalar o serviço:

Active Directory Domain Services (AD DS)

### 3. Promover o servidor a Domain Controller

Após instalar o serviço, o servidor deve ser promovido a controlador de domínio.

Isso cria um novo domínio.

Exemplo:

empresa.local

### 4. Criar usuários e grupos

Depois da instalação, o administrador pode criar:

- contas de usuários
- grupos
- computadores

### 5. Aplicar políticas de segurança

Utilizando Group Policy é possível aplicar regras automaticamente para toda a rede.

## Benefícios

- gerenciamento centralizado
- segurança
- controle de acesso
- padronização de configurações
