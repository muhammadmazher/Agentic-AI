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
This command sets up a project structured for packaging, placing your code inside a src directory, aligning with best practices for Python project structures.
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
Activate virtual environment:

```
source .venv/bin/activate

In Windows 
\explore-uv\.venv\Scripts\activate
```
Select Recommended Python Interpreter (./.venv/bin/python) created by virtual envirnoment in VSCode
```
uv run explore-uv
```
