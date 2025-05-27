# UV Project Create and Setup VS Code

## 📦 Check UV Version and Help
```
uv version
uv help
```
## 🛠️ Initialize New Project
```
uv init --package project-1
```
This command sets up a project structured for packaging, placing your code inside a `src` directory, aligning with best practices for Python project structures.
## 📂 Open the Project in VS Code
````
cd explore-uv

code .
````

Use `code .` on terminal or open the directory `project-1` in VSCode

## 🌐 Create a Virtual Environment
```
uv venv
```
## ⚙️ Activate the Virtual Environment

**On macOS/Linux:**
```
source .venv/bin/activate
```
**In Windows`:** 
```
.venv\Scripts\activate
```
Then in VSCode, select the recommended Python interpreter:
`./.venv/bin/python` or `./.venv/Scripts/python.exe`

## ▶️ Run the Project
```
uv run explore-uv
```
