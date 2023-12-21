# corrigir_erro_vmware_kernel_novo
Não é possível compilar o módulo de estação de trabalho VMWare após a atualização do kernel?

# Sobre: Script para corrigir problemas relacionados ao Kernel pós update. <br>

## Descrição
Este script automatiza o processo de instalação e manutenção dos módulos do host VMware em sistemas Linux. Ele garante que os cabeçalhos do kernel estejam atualizados e compila os módulos necessários para a versão especificada do VMware Workstation.

<b># corrigir_erro_vmware_kernel_novo<b><br>
Linkedin: https://www.linkedin.com/in/thalles-canela/ <br>
YouTube:  https://www.youtube.com/c/aXR6CyberSecurity <br>
Facebook: https://www.facebook.com/axr6PenTest <br>
Github:   https://github.com/ThallesCanela <br>
Github:   https://github.com/aXR6 <br>
Twitter:  https://twitter.com/Axr6S <br>
Padim:    https://www.padrim.com.br/aXR6CyberSecurity <br>

## Funcionalidades
- **Atualização do Sistema**: Atualiza todos os pacotes do sistema e remove pacotes desnecessários.
- **Instalação dos Cabeçalhos do Linux**: Instala os cabeçalhos do kernel necessários para sua versão específica do kernel Linux.
- **Clonagem do Repositório VMware-Host-Modules**: Clona o repositório oficial do GitHub para obter os módulos do host VMware.
- **Compilação dos Módulos**: Compila os módulos para a versão específica do VMware Workstation fornecida pelo usuário.
- **Instalação dos Módulos Compilados**: Instala os módulos compilados no sistema.
- **Reinicialização do Serviço VMware**: Reinicia o serviço VMware para aplicar as mudanças.

## Requisitos
- Acesso à Internet para clonar o repositório do GitHub.
- Permissões de administrador (sudo) para instalação de pacotes e serviços.

## Notas
- Este script foi testado em várias distribuições Linux, mas recomenda-se testá-lo em um ambiente de desenvolvimento antes do uso em produção.
- Assegure-se de ter backups dos seus dados antes de executar o script.

## Uso
1. Execute o script em um terminal com permissões de administrador.
2. Forneça a versão do VMware Workstation quando solicitado.
3. Aguarde a conclusão do script.

# Basta apenas clonar o repositório, dar permissão e executar o script.
```
git clone https://github.com/aXR6/corrigir_erro_vmware_kernel_novo/
cd corrigir_erro_vmware_kernel_novo/
chmod 777 corrigir_vmware_kernel
./corrigir_vmware_kernel
```

## Contribuições
Contribuições para melhorar o script são bem-vindas. Por favor, crie um pull request ou uma issue no GitHub para sugerir melhorias.
