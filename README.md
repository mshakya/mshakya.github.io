# cvless theme

A Jekyll theme from https://github.com/piazzai/cvless

# Setting up the **cvless** Jekyll theme with Mamba, Ruby 2.7, and Bundler 2.1.2

These instructions assume **macOS (Apple Silicon or Intel)** and **Miniforge/Miniconda + Mamba** are already installed.  
No Homebrew or `sudo` privileges are required.

---

# 1 · Create and activate the Mamba environment
```bash
mamba create -n cvless-env \
  ruby=2.7 libyaml libffi zlib clang llvm make -c conda-forge
```

# 2 activate  (use conda if `mamba init` isn’t enabled)
conda activate cvless-env


# 3 · Install Bundler 2.1.2 and Jekyll

```bash
gem install bundler -v 2.1.2
gem install jekyll
```

---


# 4 · Create the project folder

```bash
mkdir ~/cvless-site
cd    ~/cvless-site
```

---



# 5 · clone the cvless repo

