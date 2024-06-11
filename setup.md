### First-time Setup for Visual Studio Code

After installing Visual Studio Code, there are several initial configurations and settings you should adjust to create an optimal coding environment. Below are the recommended steps:

#### 1. **Interface Customization**
- **Theme:**
  - Go to `File` > `Preferences` > `Color Theme` (or press `Ctrl+K Ctrl+T`) to select a theme that suits your preferences.
- **Icon Theme:**
  - Go to `File` > `Preferences` > `File Icon Theme` to choose an icon set that you like.

#### 2. **Keybindings**
- **Custom Keybindings:**
  - Go to `File` > `Preferences` > `Keyboard Shortcuts` (or press `Ctrl+K Ctrl+S`) to customize shortcuts according to your workflow.

#### 3. **Settings Configuration**
- **Settings Sync:**
  - Enable Settings Sync to synchronize settings across devices. Go to `File` > `Preferences` > `Settings Sync` and follow the prompts to sign in with your GitHub or Microsoft account.
- **Common Settings:**
  - Go to `File` > `Preferences` > `Settings` (or press `Ctrl+,`) and adjust the following:
    - **Editor:**
      - `"editor.tabSize": 4` (or adjust as needed)
      - `"editor.wordWrap": "on"`
      - `"editor.minimap.enabled": false` (optional, to disable minimap)
    - **Auto Save:**
      - `"files.autoSave": "afterDelay"`
    - **Line Numbers:**
      - `"editor.lineNumbers": "on"`

#### 4. **Install Essential Extensions**
- **Python:**
  - Install the Python extension for Python development.
- **Prettier - Code formatter:**
  - For automatic code formatting.
- **ESLint:**
  - To integrate ESLint for JavaScript/TypeScript.
- **GitLens:**
  - Enhances Git capabilities.
- **Live Server:**
  - For a live-reloading development server.
- **Docker:**
  - Adds support for Docker and Docker Compose.
- **Bracket Pair Colorizer:**
  - Highlights matching brackets.

#### 5. **Workspace Settings**
- **Create a Workspace:**
  - Go to `File` > `Add Folder to Workspace` and add your project folders. Then, go to `File` > `Save Workspace As` to save your workspace configuration.

#### 6. **Version Control Integration**
- **Git Configuration:**
  - Ensure Git is installed and configured. Go to `Source Control` on the sidebar, and you may be prompted to install additional Git-related extensions.

#### 7. **Terminal Configuration**
- **Integrated Terminal:**
  - Customize the integrated terminal by going to `File` > `Preferences` > `Settings` and searching for `terminal`. Adjust settings like `terminal.integrated.fontSize` and `terminal.integrated.shell.windows` if using a specific shell like Git Bash.

#### 8. **Snippet and Emmet Configuration**
- **User Snippets:**
  - Go to `File` > `Preferences` > `User Snippets` to create custom code snippets for repetitive tasks.
- **Emmet Abbreviations:**
  - Ensure Emmet is enabled for HTML and CSS by going to `File` > `Preferences` > `Settings` and searching for `emmet`.

#### 9. **Language-specific Settings**
- **JavaScript/TypeScript:**
  - Install additional extensions like `JavaScript (ES6) code snippets` and `TypeScript Hero`.
- **Python:**
  - Configure the Python extension by selecting the Python interpreter (`Ctrl+Shift+P`, then type and select `Python: Select Interpreter`).
