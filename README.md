# LifeCycle Hooks Angular


#### Listar Política de execução do powershell
```
Get-ExecutionPolicy
   [[-Scope] <ExecutionPolicyScope>]
   [-List]
   [<CommonParameters>]
```
- Para exibir as políticas de execução de cada escopo em ordem de precedência, use Get-ExecutionPolicy -List. Para ver a política de execução efetiva para sua sessão do PowerShell, use Get-ExecutionPolicysem parâmetros.

- A política de execução efetiva é determinada pelas políticas de execução definidas pelas Set-ExecutionPolicyconfigurações da Política de Grupo.

- O Set-ExecutionPolicycmdlet usa o parâmetro ExecutionPolicy para especificar a política RemoteSigned .
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

#### Limpar o cache no npm

```
npm cache clean --force
npm cache verify
```

#### Usar o ng para fazer consulta na documentação

- Digite ng doc e a palavra da busca. Exemplo 'ng doc service'