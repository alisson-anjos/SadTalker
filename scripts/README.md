### Instruções Rápidas para Utilizar o Script de Download com wget no Windows

1. **Defina a política de execução do PowerShell**:
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

2. **Instale o Scoop**:
   ```powershell
   Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
   ```

3. **Instale o wget usando Scoop**:
   ```powershell
   scoop install wget
   ```

4. **Abra o PowerShell e navegue até o diretório do script**.

5. **Execute o script**:
   ```powershell
   .\download_models_wget_fast.ps1
   ```

6. **Após o download ser concluído, copie as pastas `checkpoints` e `gfpgan` para o diretório raiz do seu projeto**, no mesmo nível da pasta `src`.

Seguindo esses passos, você conseguirá instalar o wget e executar o script de download no Windows.