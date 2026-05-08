# SALtruc GitHub Profile Setup

## 1. Create the profile repository

Create a public repository named exactly:

```text
SALtruc/SALtruc
```

GitHub only shows the profile README if the repository name matches your username.

## 2. Add these files

Copy files into the repo like this:

```text
SALtruc/
├── README.md
└── .github/
    └── workflows/
        ├── snake.yml
        └── profile-3d.yml
```

## 3. Enable workflow write permission

Go to:

```text
Settings → Actions → General → Workflow permissions
```

Choose:

```text
Read and write permissions
```

Then save.

## 4. Run workflows once

Go to the Actions tab and manually run:

1. Generate Snake
2. GitHub Profile 3D Contrib

Wait a few minutes, then refresh the README.

## 5. If some images look broken

This is usually normal because GitHub caches external SVGs.

Try:
- wait 10–60 minutes
- refresh the page
- check that the `output` branch exists for snake
- check that `profile-3d-contrib/` exists for the 3D calendar
