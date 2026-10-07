# Developer Toolkit 🛠️

A curated collection of developer utilities, quick reference guides, productivity tips, and workflow automations.

## 📌 Contents
- [Git Productivity & Workflow](#git-productivity--workflow)
- [Shell & Terminal Shortcuts](#shell--terminal-shortcuts)
- [Python & Node Quickstarts](#python--node-quickstarts)
- [Contributing](#contributing)

---

## ⚡ Git Productivity & Workflow
Useful everyday Git commands:
```bash
# Pretty log with branch graphs
git log --graph --oneline --decorate --all

# Undo last commit keeping changes staged
git reset --soft HEAD~1

# Stash untracked files as well
git stash -u
```

## 🚀 Shell & Terminal Shortcuts
- `Ctrl + R`: Reverse history search
- `Ctrl + L`: Clear screen
- `!!`: Rerun previous command

## 🐍 Python & Node Quickstarts
```python
# Quick HTTP server for testing
python -m http.server 8000
```
```bash
# Measure command execution time
time npm test
```

## 🐳 Docker & Container Shortcuts
Useful commands for daily container debugging:
```bash
# Prune all stopped containers, unused networks, and dangling images
docker system prune -f

# Follow logs with timestamps
docker logs -f --tail 100 --timestamps <container_name>

# Inspect environment variables inside a running container
docker exec -it <container_name> env
```

## 🤝 Contributing
Contributions, additions, and suggestions are welcome! Feel free to open an issue or pull request.