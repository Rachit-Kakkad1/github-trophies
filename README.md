<div align="center">
  <img src=".github/logo.png" width="180" alt="GitHub Profile Trophy Logo" />
  <h1>🏆 GitHub Profile Trophy</h1>
  <p><b>Showcase your GitHub achievements with dynamic, beautifully crafted trophies.</b></p>

  <p>
    <a href="https://github.com/Rachit-Kakkad1/github-trophies/stargazers"><img src="https://img.shields.io/github/stars/Rachit-Kakkad1/github-trophies?style=for-the-badge&color=FFD700&logo=github" alt="Stars" /></a>
    <a href="https://github.com/Rachit-Kakkad1/github-trophies/network/members"><img src="https://img.shields.io/github/forks/Rachit-Kakkad1/github-trophies?style=for-the-badge&color=C0C0C0&logo=github" alt="Forks" /></a>
    <a href="https://github.com/Rachit-Kakkad1/github-trophies/blob/master/LICENSE"><img src="https://img.shields.io/github/license/Rachit-Kakkad1/github-trophies?style=for-the-badge&color=4169E1" alt="License" /></a>
  </p>
</div>

---

## 🚀 Overview

**GitHub Profile Trophy** is a high-performance Deno service that dynamically generates SVG stat trophies for your GitHub profile README. It tracks your contributions, stars, followers, and more, awarding you ranks from **C** to the legendary **SSS**.

Developed and Maintained by **Rachit Kakkad**.

---

## 🛠️ Quick Start

Elevate your profile in seconds. Copy and paste the following snippet into your `README.md`, replacing `YOUR_USERNAME` with your GitHub username.

```markdown
[![Trophies](https://github-profile-trophy.vercel.app/?username=Rachit-Kakkad1)](https://github.com/Rachit-Kakkad1/github-trophies)
```

### ✨ Live Preview
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Rachit-Kakkad1&column=7&theme=onedark&margin-w=15" alt="Rachit Kakkad's Trophies" />
</div>

---

## 🎨 Themes & Customization

Express your style with over **20+ premium themes** and deep customization options.

### Popular Themes
| **One Dark** | **Dracula** | **Gruvbox** |
| :---: | :---: | :---: |
| `theme=onedark` | `theme=dracula` | `theme=gruvbox` |
| <img src="https://github-profile-trophy.vercel.app/?username=Rachit-Kakkad1&theme=onedark&column=2&title=Stars,Followers" width="250" /> | <img src="https://github-profile-trophy.vercel.app/?username=Rachit-Kakkad1&theme=dracula&column=2&title=Stars,Followers" width="250" /> | <img src="https://github-profile-trophy.vercel.app/?username=Rachit-Kakkad1&theme=gruvbox&column=2&title=Stars,Followers" width="250" /> |

### ⚙️ Parameters
| Parameter | Description | Default |
| :--- | :--- | :--- |
| `username` | **(Required)** Your GitHub username | - |
| `theme` | Apply a predefined color palette | `default` |
| `title` | Filter trophies by specific titles (e.g., `Stars,Commits`) | All |
| `rank` | Filter by rank (e.g., `SSS,SS,S,AAA,AA,A,B,C`) | All |
| `column` | Maximum number of columns | `6` |
| `row` | Maximum number of rows | `3` |
| `no-bg` | Set background to transparent (`true`/`false`) | `false` |
| `no-frame`| Hide trophy frames (`true`/`false`) | `false` |
| `margin-w`| Horizontal spacing between trophies | `0` |
| `margin-h`| Vertical spacing between trophies | `0` |

---

## 🎖️ The Ranking System

Trophies are awarded based on your performance across various metrics.

*   **SSS, SS, S**: Elite status. The pinnacle of GitHub contribution.
*   **AAA, AA, A**: Exceptional performance.
*   **B, C**: Solid progress. Keep pushing!
*   **SECRET**: Rare, hidden trophies triggered by specific conditions. Can you find them all?

---

## 💻 Self-Hosting & Deployment

Support the project and reduce server load by deploying your own instance!

1.  **Fork** the repository to your account.
2.  Connect your fork to **Vercel**.
3.  Add your `GH_TOKEN` to Environment Variables.
4.  **Deploy!**

### Local Generation
You can also generate trophies locally using Deno:
```bash
deno run --allow-net --allow-env --allow-read --allow-write ./render_svg.ts Rachit-Kakkad1 ./output onedark
```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 💖 Support the Project

If you find this project useful, consider giving it a ⭐ or sponsoring the developer.

<div align="center">
  <a href="https://github.com/sponsors/Rachit-Kakkad1">
    <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4&style=for-the-badge" alt="Sponsor Rachit Kakkad" />
  </a>
</div>

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Built with ❤️ by <a href="https://github.com/Rachit-Kakkad1">Rachit Kakkad</a>
</p>
