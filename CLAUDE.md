## Search & File Discovery
- Always use `rg` (ripgrep) instead of `find` for searching files and content — it's faster and respects .gitignore
- Use `rg --files` to list files instead of `find . -type f`
- In git-managed repositories, prefer `git ls-files` over `rg --files` for listing files — it's even faster as it reads directly from git's index

