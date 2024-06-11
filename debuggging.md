### Debugging in VS Code

#### Setting Up and Starting Debugging

1. **Configure the Debugger:**
   - Click on the Run and Debug icon in the Activity Bar on the side of the VS Code window.
   - Click on `create a launch.json file` link to create a debug configuration file if it’s not already present.

     ![Create launch.json](https://code.visualstudio.com/assets/docs/editor/debugging/launch-json-intellisense.png)

   - Choose the environment for your project (e.g., Node.js for JavaScript, Python for Python, etc.).

     ![Select Environment](https://code.visualstudio.com/assets/docs/editor/debugging/debugging_hero.png)

   - A `launch.json` file will be created with default configurations. Customize it as needed for your project.

     ```json
     {
       "version": "0.2.0",
       "configurations": [
         {
           "name": "Python: Current File",
           "type": "python",
           "request": "launch",
           "program": "${file}",
           "console": "integratedTerminal"
         }
       ]
     }
     ```

2. **Add Breakpoints:**
   - Set breakpoints by clicking in the gutter to the left of the line numbers in your code file.

3. **Start Debugging:**
   - Click the green play button in the Run and Debug view or press `F5` to start debugging.

     ![Start Debugging](https://code.visualstudio.com/assets/docs/editor/debugging/run.png)

#### Key Debugging Features in VS Code

1. **Breakpoints:**
   - You can set, disable, and remove breakpoints by clicking in the editor margin. Conditional breakpoints and logpoints can be used for more advanced debugging.
  
   - ![Add breakpoints](https://code.visualstudio.com/assets/docs/editor/debugging/debug-menu.png)

2. **Watch Variables:**
   - Add variables to the Watch panel to monitor their values as you step through your code.

     ![Watch Variables](https://code.visualstudio.com/assets/docs/editor/debugging/watch.png)

3. **Call Stack:**
   - View the call stack to understand the sequence of function calls that led to the current execution point.

     ![Call Stack](https://code.visualstudio.com/assets/docs/editor/debugging/debug-status.png)

4. **Step Through Code:**
   - Use the step controls to step over, step into, and step out of functions to control the execution flow.

5. **Debug Console:**
   - Use the Debug Console to evaluate expressions and execute commands in the context of the debugging session.

     ![Debug Console](https://code.visualstudio.com/assets/docs/editor/debugging/debugconsole.png)

---

**References:**
- [VS Code Debugging Documentation](https://code.visualstudio.com/docs/editor/debugging)