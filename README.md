# signal42-training-repository

This repository is used to share homework and exercises between workshops.

## Repository Structure

```
signal42-training-repository/
├── homework-01/          # Homework folder for workshop 1 → 2
│   ├── alice/            # Each participant uses their own name or alias
│   ├── bob/
│   └── ...
├── homework-02/          # Homework folder for workshop 2 → 3
│   ├── alice/
│   └── ...
└── ...
```

## How to Contribute

Since you don't have direct write access to this repository, contributions go through a **fork + pull request** workflow.

1. **Fork the repository** — click the **Fork** button on GitHub to create your own copy.

2. **Clone your fork**
   ```bash
   git clone https://github.com/your-github-username/signal42-training-repository.git
   cd signal42-training-repository
   ```

3. **Create your personal folder** inside the relevant homework folder, using your name or alias:
   ```bash
   mkdir -p homework-01/your-name
   ```

4. **Add your work** — put whatever you like inside your folder: code, notes, experiments, solutions.

5. **Commit and push to your fork**
   ```bash
   git add homework-01/your-name/
   git commit -m "homework-01: your-name"
   git push
   ```

6. **Open a Pull Request** — go to your fork on GitHub and click **Compare & pull request** to submit your work to the main repository.

## Guidelines

- **Your folder is yours** — feel free to commit anything you want inside it.
- **Don't touch other people's folders** — respect each participant's personal space.
- **One folder per homework session** — homework folders are named `homework-XX` and are created by the trainer before each session.
- **Any language, any tool** — there are no constraints on what you put in your folder.
