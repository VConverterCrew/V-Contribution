<div align="center">

# V-Contribution

**Your starting point for contributing to V-Converter.**

A community-focused website that helps new and experienced contributors learn how to support the **V-Converter** project through programming, playtesting, bug reporting, and artwork.

[Explore V-Converter](https://github.com/VConverterCrew/V-Converter) · [View This Repository](https://github.com/VConverterCrew/V-Contribution) · [Join Our Discord](https://discord.gg/gYrQvGYXCY)

</div>

---

## About

**V-Contribution** is a documentation and onboarding website for the V-Converter community. It brings contribution guides together in one accessible place, helping you understand where to begin, how to share your work, and how to collaborate with other contributors.

Whether you write code, test features, report issues, or create artwork, there is a way to get involved.

## What You'll Find

| Guide | Description |
| --- | --- |
| [Programming](documents/programming.html) | Learn the basics of contributing code and submitting pull requests. |
| [Playtesting](documents/playtesting.html) | Help test features, conversions, and platform behavior. |
| [Reporting](documents/reporting.html) | Write clear, reproducible bug reports and feature feedback. |
| [Art Contributions](documents/arting.html) | Learn how to share visual assets and design contributions. |

## Website Features

- **Multilingual interface:** English, Portuguese, and Spanish.
- **Responsive layout:** Designed for desktop and mobile browsers.
- **Blue visual theme:** A consistent look across the website and its guides.
- **Funkin font:** Uses `assets/fonts/funkin.ttf`.
- **Optional background music:** Uses `assets/music/funkin.ogg`, with playback controls.
- **Community access:** Quick links to the V-Converter project and Discord server.

## Getting Started

1. Open [`index.html`](index.html) to explore the contributor guides.
2. Choose the area you want to help with: programming, playtesting, reporting, or artwork.
3. Read the relevant guide before preparing your contribution.
4. Visit the [V-Converter repository](https://github.com/VConverterCrew/V-Converter) to review its issues, code, and existing contributions.
5. Share your proposal through the appropriate GitHub issue or pull request.

## Run the Website Locally

This website uses HTML, CSS, and JavaScript without a required build step.

```bash
git clone https://github.com/VConverterCrew/V-Contribution.git
cd V-Contribution
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

> You can also open `index.html` directly, but a local web server provides behavior closer to a hosted website.

## Project Structure

```text
V-Contribution/
├── index.html
├── documents/
│   ├── programming.html
│   ├── playtesting.html
│   ├── reporting.html
│   └── arting.html
├── assets/
│   ├── fonts/
│   │   └── funkin.ttf
│   └── music/
│       └── funkin.ogg
└── README.md
```

Styles and scripts are embedded in their respective HTML pages.

## Contributing to This Website

Contributions to **V-Contribution** are welcome, including documentation improvements, translations, accessibility fixes, visual refinements, and corrections to outdated instructions.

1. Fork this repository.
2. Create a branch for your change.
3. Make your edits and test the affected pages.
4. Open a pull request describing what changed and why.

Please keep the English, Portuguese, and Spanish versions consistent when changing visible text. Check navigation, mobile layout, and media controls before submitting.

## Community

Have a question, want to discuss an idea, or need help getting started? Join the community:

**[V-Converter Discord Server](https://discord.gg/gYrQvGYXCY)**

You can also explore the [VConverterCrew organization](https://github.com/VConverterCrew) on GitHub.

## License

See the [LICENSE](LICENSE) file in this repository for the applicable license terms.

---

<div align="center">

**Learn. Create. Test. Contribute.**

Made for the V-Converter contributor community.

</div>
