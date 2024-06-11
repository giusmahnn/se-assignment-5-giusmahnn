### Settings and Preferences in VS Code

#### Accessing and Customizing Settings

1. **Opening Settings:**
   - **Graphical Interface:**
     - Click on the gear icon in the lower-left corner of the Activity Bar and select `Settings` from the menu.
     - Alternatively, use the keyboard shortcut `Ctrl+,` (Windows/Linux) or `Cmd+,` (Mac).

     ![VS Code Settings](https://code.visualstudio.com/assets/docs/getstarted/settings/settings-search.png)

   - **Settings JSON:**
     - For more advanced configurations, you can open the settings JSON file directly. Click on the gear icon, select `Settings`, and then click on the `{}` icon in the top right corner of the settings window to open the JSON file.
  
     - ![Change Theme](https://code.visualstudio.com/assets/docs/getstarted/settings/settings-json-in-editor.png)

2. **Changing the Theme:**
   - **Graphical Interface:**
     - Open the Command Palette with `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).
     - Type `Preferences: Color Theme` and select it from the list.
     - Browse and select from the available themes.

     ![Change Theme](https://code.visualstudio.com/assets/docs/getstarted/settings/more-actions-context-menu.png)

3. **Adjusting Font Size:**
   - **Graphical Interface:**
     - Open the settings using the gear icon and select `Settings`.
     - In the search bar, type `Font Size`.
     - Adjust the `Editor: Font Size` setting to your preferred size.

     ![Change Font Size](https://code.visualstudio.com/assets/docs/getstarted/settings/font-size.png)

   - **Settings JSON:**
     - Open the settings JSON file.
     - Add or modify the following entry:
       ```json
       "editor.fontSize": 14
       ```

4. **Customizing Keybindings:**
   - **Graphical Interface:**
     - Click on the gear icon in the lower-left corner and select `Keyboard Shortcuts`.
     - Alternatively, use the keyboard shortcut `Ctrl+K Ctrl+S` (Windows/Linux) or `Cmd+K Cmd+S` (Mac).
     - Search for the command you want to change, click on the pencil icon next to it, and enter the new keybinding.

     ![Change Keybindings](https://code.visualstudio.com/assets/docs/getstarted/keybinding/keyboard-shortcuts.gif)

   - **Keybindings JSON:**
     - Open the Command Palette with `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).
     - Type `Preferences: Open Keyboard Shortcuts (JSON)` and select it.
     - Add or modify keybindings using the JSON format. For example:
       ```json
       [
         {
           "key": "ctrl+alt+n",
           "command": "workbench.action.files.newUntitledFile"
         }
       ]
       ```

---

**References:**
For more detailed information, visit the official [VS Code documentation on settings](https://code.visualstudio.com/docs/getstarted/settings) and [keybindings](https://code.visualstudio.com/docs/getstarted/keybindings).