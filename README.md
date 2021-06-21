# AutoGitIgnore
Automatically generate .gitignore for your repository.

# Usage
List all supported languages/IDEs:

```bash
ignore -l
```

Generate .gitignore file by specifying languages/IDE:

```bash
ignore language1 [language2 language3 ...]
```

For example, if you are working in C and Python using VSCode on a Mac, you can do:

```bash
ignore c python visualstudiocode macos
```
Note: the options are case-insensitive

*Generated file will be named generated.gitignore. You can put it in your project repository and rename it to .gitignore*