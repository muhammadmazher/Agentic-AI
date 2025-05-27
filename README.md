 # 🚀 Python UV 
 **The Fastest Python Package Manager**

## 📚 Learning Resources

- 📘 [Python UV: The Ultimate Guide to the Fastest Python Package Manager](https://www.datacamp.com/tutorial/python-uv)  
- 📖 [Official UV Docs](https://docs.astral.sh/uv/)
- 🏃 [Running Scripts with UV](https://docs.astral.sh/uv/guides/scripts/)
- 🧩 [Working on Projects](https://docs.astral.sh/uv/guides/projects/)
- 🧾 [CLI Reference](https://docs.astral.sh/uv/reference/cli/)
- 🎥 [Watch: Python Setup, Simplified: A Complete "uv" Tutorial!](https://www.youtube.com/watch?v=-J5SnWR4UXw)


## 🧠 Cursor Rules (Best Practices)

When working in Python always use UV as package manager.

Instead of writing code you can use cli to run commands where it's efficient like when prompted to create new project using uv use:

Packaged applications Many use-cases require a package. For example, if you are creating a command-line interface that will be published to PyPI or if you want to define tests in a dedicated directory.

### ✅ Why Use UV?

- Super fast and modern
- Clean project management
- Simplifies scripts and dependencies


## 🧪 Packaged Applications with UV

> Many use-cases require a package — especially if:
> - You're creating a **CLI tool** (to be published on PyPI)
> - You want to organize **tests** in a dedicated directory

Use the `--package` flag to create a project as a proper Python package:

```
uv init --package example-pkg
```
## 📦 Installing Packages in Your Project
To add a new dependency inside your UV-managed project:
```
uv add package-name
```
Example:
```
uv add fastapi
```
UV will handle dependency resolution, lockfiles, and installation efficiently.

✨ Stay modern, stay fast — use uv!
