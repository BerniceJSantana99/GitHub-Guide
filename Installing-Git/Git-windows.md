# Install Git on Windows

1. Go to [Git for Windows](https://git-scm.com/install/windows).
2. Download and open the installer.
3. Use the default options, then finish the installation.
4. Open **PowerShell** and run:

   ```powershell
   git --version
   ```

If you see a version number, Git is installed.

You can also install it from PowerShell with:

```powershell
winget install --id Git.Git -e --source winget
```
