# GitHub Readme Stats (Self-Hosted)

A self-hosted deployment of GitHub Readme Stats running on Vercel.

This repository powers the GitHub profile cards displayed on my GitHub profile and helps avoid rate limits or downtime from the public deployment.

> Based on the original GitHub Readme Stats project by Anurag Hazra.

---

## Features

- 📊 GitHub Statistics Card
- 💻 Top Languages Card
- 🚀 Self-hosted on Vercel
- 🔑 Uses a GitHub Personal Access Token for improved API limits
- ⚡ Fast and reliable

---

## Live Deployment

**Base URL**

```
https://midhunmanesh01-code-github-stats.vercel.app
```

---

## Available Endpoints

### GitHub Statistics

```
/api?username=<github_username>
```

Example:

```
https://midhunmanesh01-code-github-stats.vercel.app/api?username=midhunmanesh01-code
```

---

### Top Languages

```
/api/top-langs?username=<github_username>
```

Example:

```
https://midhunmanesh01-code-github-stats.vercel.app/api/top-langs?username=midhunmanesh01-code
```

---

## Example Usage

### GitHub Stats

```html
<p align="left">
  <img src="https://midhunmanesh01-code-github-stats.vercel.app/api?username=midhunmanesh01-code&show_icons=true&theme=tokyonight&hide_border=true" />
</p>
```

### Top Languages

```html
<p align="left">
  <img src="https://midhunmanesh01-code-github-stats.vercel.app/api/top-langs/?username=midhunmanesh01-code&layout=compact&theme=tokyonight&hide_border=true" />
</p>
```

---

## Deployment

This project is deployed on Vercel using:

- GitHub
- Vercel
- GitHub Personal Access Token (PAT)

---

## Credits

Original project:
https://github.com/anuraghazra/github-readme-stats

This repository is a self-hosted deployment intended for personal use.

---

## License

This project is licensed under the MIT License.
