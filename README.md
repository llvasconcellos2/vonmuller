<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/vonmuller">
    <img src="assets/logos/logo.png" alt="Logo" height="80" />
  </a>

  <h1 align="center">VonMuller Estúdio Fotográfico</h1>

  <p align="center">A custom WordPress theme and site for VonMuller Estúdio Fotográfico, a wedding and event photography studio in Joinville, Brazil operating since 2004.</p>

  <p align="center">// wedding & event photography · Joinville, Brazil</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/vonmuller"
    ><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/vonmuller)

<!-- PROJECT INTRO: 260 chars max -->

A custom WordPress build for a Joinville, Brazil wedding and event photography studio active since 2004 — bespoke theme, lightbox galleries, photo watermarking, and security hardening for a small-business site exposed to real-world WordPress attacks.

<!-- END INTRO -->

VonMuller Estúdio Fotográfico is a wedding and event photography studio based in Joinville, Santa Catarina, Brazil, run by photographer Wander Von Muller and active since 2004. The site showcases the studio's portfolio across weddings, corporate events, invitations and posters, and behind-the-scenes "making of" video and location work, alongside a company profile and direct contact channel for booking.

The project is a fully custom WordPress build: a bespoke theme (`VonMuller`, v2.0.1) rather than an off-the-shelf template, with Highslide-powered lightbox galleries for browsing event photography, Cufon web-font rendering for the era's custom typography needs, and an image-watermarking plugin to protect the studio's photos from unauthorized use. The codebase in this archive also reflects ongoing maintenance: a 2016 upgrade to WordPress 4.6.1 and the removal of the `timthumb.php` script after it was identified as a common attack vector across WordPress sites of that period, paired with the Better WP Security plugin for ongoing hardening.

This repository preserves the site as archived via `wget` (see `rip/`), along with the original WordPress installation (`www/`), database export (`db/vonmuller.sql`), and brand assets (`assets/`).

**Key features:**

- Built a fully custom WordPress theme from scratch (no page builder) — bespoke navigation, lightbox galleries (Highslide), and a Cufon-based typography system — giving the studio a distinctive, on-brand presence instead of a generic template look that competitors were using.
- Integrated an image-watermarking plugin across the portfolio galleries, protecting the studio's wedding and event photography from unauthorized reuse — a real concern for photographers whose finished work is their product.
- Hardened the WordPress install (Better WP Security, removal of the vulnerable `timthumb.php` script) and kept the platform on a current core version, reducing the studio's exposure to the mass WordPress exploit campaigns that targeted exactly this kind of small-business site in the mid-2010s.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->
## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Contato.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Contato.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Eventos (1).png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Eventos (1).png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Eventos.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Eventos.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Making Of Externo.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Making Of Externo.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Produtos.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Produtos.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Serviços.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Serviços.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Vídeo clipe..png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Vídeo clipe..png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Wander Von Muller.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico   Wander Von Muller.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico.png"><img src="screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With

<!-- LANGUAGES -->

**Languages**

|                                                                                                          | Language   | Version |
| -------------------------------------------------------------------------------------------------------- | ---------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />         | PHP        | 5.x     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" /> | JavaScript | —       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />     | HTML5      | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />        | CSS3       | 3       |

<!-- FRAMEWORKS & LIBRARIES -->

**Frameworks & Libraries**

|                                                                                                            | Framework  | Version |
| ----------------------------------------------------------------------------------------------------------- | ---------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-plain.svg" width="20" />  | WordPress  | 4.6.1   |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" width="20" />     | jQuery     | 1.6.1   |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/llvasconcellos2/vonmuller/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/vonmuller" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[Leonardo Vasconcellos - Website](https://leonardo-vasconcellos.vercel.app/) — [LinkedIn](https://www.linkedin.com/in/llvasconcellos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/vonmuller.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/vonmuller/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/vonmuller.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/vonmuller/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/vonmuller.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/vonmuller/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2012-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/Fotógrafo Joinville   VonMuller Estúdio Fotográfico.png
