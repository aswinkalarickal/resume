[![Build LaTeX document](https://github.com/aswinkalarickal/resume/actions/workflows/main.yml/badge.svg)](https://github.com/aswinkalarickal/resume/actions/workflows/main.yml)

# Resume ([`LaTeX`](https://www.latex-project.org/) + [`moderncv`](https://ctan.org/pkg/moderncv))

This repository contains my resume written in LaTeX using the moderncv class. It provides a clean and professional layout suitable for job applications and academic use.

## 🛠 Requirements

- A LaTeX distribution (e.g., [MacTeX](https://tug.org/mactex/) or [TeX Live](https://tug.org/texlive/))
- The `moderncv` package (included in most full LaTeX distributions)

### Install via Homebrew (macOS):

```bash
# Install using brew
brew install --cask mactex

# Add to PATH
echo 'export PATH="/Library/TeX/texbin:$PATH"' >> ~/.zshrc

# Install moderncv
sudo tlmgr update --self
sudo tlmgr install moderncv
```
