### Quick Instructions to Use the Download Script with wget on Windows

1. **Set the PowerShell execution policy**:
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

2. **Install Scoop**:
   ```powershell
   Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
   ```

3. **Install wget using Scoop**:
   ```powershell
   scoop install wget
   ```

4. **Open PowerShell and navigate to the directory of the script**.

5. **Run the script**:
   ```powershell
   .\download_models_wget_fast.ps1
   ```

6. **After the download is finished, copy the `checkpoints` and `gfpgan` folders to the root directory of your project**, at the same level as the `src` folder.

Following these steps, you will be able to install wget and run the download script on Windows.
