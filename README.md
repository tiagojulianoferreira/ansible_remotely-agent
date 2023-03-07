# remotely-agent
Instala e configura o agente da solução de acesso remoto [Remotely](https://github.com/immense/Remotely)

# Váriaveis
As seguintes variáveis serão utilizadas na instalação do agente(via win_shell).

- **SERVER** - URL do servidor Remotely.(obrigatória)
- **ORGANIZATION_ID** - disponível no web console do Remotely no menu Organization. (obrigatória)
- **DEVICE_GROUP** -  registra automaticamente o host em um grupo de dispositivos.(opcional, default=None)

# Desinstalar o agente
Este projeto inclui uma role especial que faz a remoção do agente Remotely. Para ativar, descomente a linha ```remove-remotely```.

```yml
roles:
     - remove-remotely
```
> Use com cuidado

# Referência
[https://github.com/immense/Remotely](https://github.com/immense/Remotely)

