<div align="center">

<h1 style="border-bottom: none">
    <b><a href="https://ivansaul.github.io/personal-portfolio">Personal Portfolio - Developer</a></b>
</h1>

**`Personal Portfolio`** is a fully responsive personal developer portfolio single-page website, <br/>
responsive for all devices, built using **`HTML`**, **`CSS`**, **`JavaScript`**, and **`Python`**.

![Made-with-python](https://img.shields.io/badge/Made%20with-Python-orange)
[![Jinja](https://github.com/ivansaul/personal-portfolio/actions/workflows/jinja.yml/badge.svg)](https://github.com/ivansaul/personal-portfolio/actions/workflows/jinja.yml)
![GitHub repo size](https://img.shields.io/github/repo-size/ivansaul/personal-portfolio)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![GitHub stars][github-stars]
![GitHub forks][github-forks]

<a href="https://discord.gg/tDvybtJ7y9">
    <img alt="Discord Server" height="50" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/social/discord-plural_vector.svg">
</a>

</div>

---

<div align="center">

![Demo][demo]
**`Live Demo:`** 👉🏽 [personal-portfolio.github.io][devfolio]

</div>

## **How to make it yours?**

### Step 1

Fork this project and rename the repo to `your_github_username.github.io`.

For example: `ivansaul -> ivansaul.github.io`

### Step 2

Go to the `config/` folder and replace the default data with your personal information.

```bash
config
|-- assets
|   |-- avatars
|   |-- icons
|   |-- posts
|   |-- projects
|-- about.toml
|-- blog.toml
|-- softskills.toml
|-- doing.toml
|-- projects.toml
|-- resume.toml
|-- social.toml
|-- technologies.toml
```

For example, to set your contact information, edit `config/about.toml`.

```toml
name = "Richard hanrick"
rol = "Flutter Developer"
email = "richard@example.com"
phone = "+1 (213) 352-2795"
birthday = "June 26, 1996"
location = "Sacramento, California, USA"
avatar = "./../my-avatar.png"
```

### Step 3

Create a personal access token.

`Settings(Account) > Developer settings > Personal access tokens > tokens (classic) > Generate new token > Generate new token (classic)`

- [x] Expiration: No expiration

### Step 4

Create a new secret with the name `PORTFOLIO_TOKEN` and paste your personal token there.

`Settings(Repo) > Secrets and Variables > Actions > Repository secrets > New secret`

### Step 5

Enable read and write permissions on:

`Settings(Repo) > Actions > General > Workflow permissions > Read and write permissions > save`

### Step 6

Enable GitHub Pages on:

`Settings(Repo) > Pages > Branch > Master > /(root > save`

### Step 7

Enable workflows on:

`Actions(Repo) > I understand my workflows, go ahead and enable them`

### Step 8: Enjoy 😉

Now you can visit your portfolio at `https://your_github_username.github.io`

Your personal portfolio will be built and updated automatically whenever any changes occur in the configuration files.

> [!NOTE]
> If you like my work and want to show some ❤️, please consider giving a ⭐️ to this Repository.

## Screenshots

![Desktop Demo][desktop-screenshot]
![Mobile Demo][mobile-screenshot]

## Contribute

Contributions are welcome.

## Facing any Issue?

Feel free to open an [Issue][issue] :)

## Contact

If you want to contact me you can reach me at [Discord][discord].

## Credits

This project is based on [vcard portfolio][vcard]. The main focus of this project is adding new features and make it accessible to everyone.

## License

MIT

[vcard]: https://github.com/codewithsadee/vcard-personal-portfolio
[devfolio]: https://ivansaul.github.io/personal-portfolio
[demo]: https://raw.githubusercontent.com/ivansaul/demos/master/python/personal-portfolio-demo.gif
[discord]: https://discord.com/users/744755977684779038
[issue]: https://github.com/ivansaul/personal-portfolio/issues
[github-stars]: https://img.shields.io/github/stars/ivansaul/personal-portfolio?style=social
[github-forks]: https://img.shields.io/github/forks/ivansaul/personal-portfolio?style=social
[desktop-screenshot]: https://i.imgur.com/xKkMSwR.png
[mobile-screenshot]: https://i.imgur.com/G1A1nBu.png
