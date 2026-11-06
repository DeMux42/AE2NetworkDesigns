<a id="readme-top"></a>

<!-- Structure adapted from othneildrew/Best-README-Template, credited in Acknowledgments. -->

[![Contributors][contributors-shield]][contributors-url]
[![Stars][stars-shield]][stars-url]
[![draw.io][drawio-shield]][drawio-url]
[![License][license-shield]][license-url]

<br />
<div align="center">
  <h3 align="center">AE2 Network Designs</h3>

  <p align="center">
    A community collection of draw.io diagrams showing how players lay out their AE2 networks.
    <br />
    <a href="AE2NetworkDesignExamples/"><strong>Browse the designs</strong></a>
    <br />
    <br />
    <a href="https://github.com/DeMux42/AE2NetworkDesigns/issues/new?labels=bug">Report a bug</a>
    &middot;
    <a href="https://github.com/DeMux42/AE2NetworkDesigns/issues/new?labels=enhancement">Request a feature</a>
  </p>
</div>

<details>
  <summary>Table of contents</summary>
  <ol>
    <li><a href="#about-the-project">About the project</a>
      <ul>
        <li><a href="#built-with">Built with</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#the-designs">The designs</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a>
      <ul>
        <li><a href="#step-1-create-and-save-your-diagram">Step 1. Create and save your diagram</a></li>
        <li><a href="#step-2-upload-your-diagram">Step 2. Upload your diagram</a></li>
        <li><a href="#contribute-custom-drawio-shapes">Contribute custom draw.io shapes</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About the project

This repository is a community collection of network diagrams for Applied Energistics 2 (AE2), for modded Minecraft players. It gives players a shared place to show how they like to set up their AE2 networks, learn from each other, and improve their own designs.

<p align="center">
  <img src="AE2NetworkDesignExamples/DeMux%27s%20AE2%20Network%20Design.svg" width="800" alt="DeMux's AE2 network design, drawn in draw.io. Its labels include Controller, Terminal, Wireless Transmitter, Drawers, Dimensional Chests and Tanks with priorities, a Trash Can, and Many Many Assemblers, plus the Importer, Exporter, Interface, Storage Bus and ME P2P shapes.">
</p>

The collection aims to:

- Teach beginners the strategy, nuance and implications of ME network design decisions.
- Share and exchange AE2 network designs.
- Give players a visual resource for improving their own setups, or for ideas.

Each design comes as a `.drawio` file for editing and an `.svg` file for viewing. The [AE2 Designs folder](AE2NetworkDesignExamples/) holds every contributed design, and the template to make your own.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built with

- [draw.io](https://www.drawio.com/), in the browser at [app.diagrams.net](https://app.diagrams.net/) or as the desktop app. Both designs so far were saved from draw.io 24.7.
- Custom draw.io shapes for AE2 parts, in [Draw.io Custom Shapes.md](Draw.io%20Custom%20Shapes.md).
- SVG exports, so GitHub shows each diagram inline.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting started

### Prerequisites

- A web browser, to view the designs here and to edit them at [app.diagrams.net](https://app.diagrams.net/). The draw.io desktop app works too.
- A GitHub account and Git, only if you want to add a design.

### Installation

There's nothing to install. To browse, open the [AE2 Designs folder](AE2NetworkDesignExamples/). To work on the files locally, clone the repository:

```bash
git clone https://github.com/DeMux42/AE2NetworkDesigns.git
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

- **View a design.** [The designs folder's README](AE2NetworkDesignExamples/README.md) shows each one as an inline SVG.
- **Open a design in draw.io.** Each design's **Edit** link opens its `.drawio` file in app.diagrams.net, read straight from this repository.
- **Start your own.** [Open the Design Template](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDeMux42%2FAE2NetworkDesigns%2Fmain%2FAE2NetworkDesignExamples%2FTemplate-AwesomeMinecrafter%27s%20AE2%20Network%20Design.drawio) as a new draw.io diagram.
- **Use the AE2 shapes.** In draw.io, go to **Arrange**, then **Insert**, then **Shape**, and paste a shape's code from [Draw.io Custom Shapes.md](Draw.io%20Custom%20Shapes.md). It has an Importer, Exporter, Interface, Storage Bus and ME P2P.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## The designs

| Design               | Edit in draw.io                                                                                                                                                                                         | View                                                                         |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| DeMux's AE2 Network  | [DeMux's AE2 Network Design.drawio](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDeMux42%2FAE2NetworkDesigns%2Fmain%2FAE2NetworkDesignExamples%2FDeMux%27s%20AE2%20Network%20Design.drawio) | [SVG](AE2NetworkDesignExamples/DeMux%27s%20AE2%20Network%20Design.svg)       |
| Z810's AE2 Network   | [Z810's AE2 Network Design.drawio](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDeMux42%2FAE2NetworkDesigns%2Fmain%2FAE2NetworkDesignExamples%2FZ810%27s%20AE2%20Network%20Design.drawio)    | [SVG](AE2NetworkDesignExamples/Z810%27s%20AE2%20Network%20Design.svg)        |
| The template         | [Template-AwesomeMinecrafter's AE2 Network Design.drawio](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDeMux42%2FAE2NetworkDesigns%2Fmain%2FAE2NetworkDesignExamples%2FTemplate-AwesomeMinecrafter%27s%20AE2%20Network%20Design.drawio) | No SVG                                                                       |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

Two designs are in, both added in September 2024, and nothing has been committed since. The collection grows when someone opens a pull request.

- [x] A draw.io template for new designs
- [x] Custom shapes for the Importer, Exporter, Interface, Storage Bus and ME P2P
- [x] DeMux's design, updated to show assemblers
- [x] Z810's design
- [ ] Better versions of the existing shapes, including colour
- [ ] Shapes for other AE2 and third-party components

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

The collection needs your designs. Follow these steps to add your AE2 network diagram.

### Step 1. Create and save your diagram

1. **Start with the template.** [Click here](https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDeMux42%2FAE2NetworkDesigns%2Fmain%2FAE2NetworkDesignExamples%2FTemplate-AwesomeMinecrafter%27s%20AE2%20Network%20Design.drawio) to open a new draw.io diagram from the Design Template.
2. **Edit your diagram.** Change the template in draw.io to show your preferred AE2 architecture.
3. **Save your work.** After editing, download both the `.drawio` file, for future editing, and an `.svg` file, for viewing. Remove "Template-" from the filenames, and put your name in place of "AwesomeMinecrafter".

### Step 2. Upload your diagram

1. **Fork the repository.** Click **Fork** at the top right of this page to create a copy of this repository under your GitHub account.
2. **Clone your fork locally.** Clone your forked repository to your computer with this command:

   ```bash
   git clone https://github.com/your-username/AE2NetworkDesigns.git
   ```

   Replace `your-username` with your GitHub username.
3. **Add your diagram files.**
   - Put your `.drawio` and `.svg` files in the `AE2NetworkDesignExamples` folder.
   - Update the `README.md` in the `AE2NetworkDesignExamples` folder to include:
     - a link to your `.drawio` file;
     - an inline render of your `.svg` file.
   - Commit your changes with a meaningful message, such as `Added Hobo Bo's preferred AE2 network design`.
4. **Check the filename formatting.** If a filename contains spaces or special characters, URL-encode it in your links, for example `%20` for a space and `%27` for an apostrophe.
5. **Submit a pull request.** After you commit and push your changes to your fork, open a pull request to this repository. Include a short description of your changes and your contribution.

### Contribute custom draw.io shapes

[Draw.io Custom Shapes.md](Draw.io%20Custom%20Shapes.md) holds custom draw.io shapes for AE2 network components, with the steps to import them. These shapes are basic and are meant as a starting point. Improvements to the existing shapes, such as colouring, and shapes for any other AE2 or third-party components are welcome.

To add or change a shape, fork this repository, make your changes, and submit a pull request. DeMux reviews every contribution. Shapes that meet the quality bar are merged into the main branch and credited, and the default template is updated to use them.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

MIT. See [`LICENSE`](LICENSE).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

DeMux - [@DeMux42](https://github.com/DeMux42)

Project link: [https://github.com/DeMux42/AE2NetworkDesigns](https://github.com/DeMux42/AE2NetworkDesigns)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- Z810 ([@z810d](https://github.com/z810d)), for the second design, added in [#1](https://github.com/DeMux42/AE2NetworkDesigns/pull/1).
- [Applied Energistics 2](https://github.com/AppliedEnergistics/Applied-Energistics-2), the mod these networks are built in.
- [draw.io](https://www.drawio.com/) and its [custom shapes documentation](https://www.drawio.com/doc/faq/shape-complex-create-edit).
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template) by othneildrew, for this README's structure.
- [Shields.io](https://shields.io) for the badges.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/DeMux42/AE2NetworkDesigns?style=for-the-badge
[contributors-url]: https://github.com/DeMux42/AE2NetworkDesigns/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/DeMux42/AE2NetworkDesigns?style=for-the-badge
[stars-url]: https://github.com/DeMux42/AE2NetworkDesigns/stargazers
[drawio-shield]: https://img.shields.io/badge/draw.io-diagrams-F08705?style=for-the-badge&logo=diagramsdotnet&logoColor=white
[drawio-url]: https://www.drawio.com/
[license-shield]: https://img.shields.io/badge/license-MIT-green?style=for-the-badge
[license-url]: LICENSE
