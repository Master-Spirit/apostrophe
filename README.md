
[![CircleCI](https://circleci.com/gh/apostrophecms/apostrophe/tree/master.svg?style=svg)](https://circleci.com/gh/apostrophecms/apostrophe/tree/master)
[<img src="./badges/npm-audit-badge.png" title="npm audit" />](https://docs.npmjs.com/cli/audit)
[![Chat on Discord](https://img.shields.io/discord/517772094482677790.svg)](https://chat.apostrophecms.org)

<p align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">ApostropheCMS</h3>

  <p align="center">
    ApostropheCMS is a full-featured, open source CMS built with Node.js that seeks to empower organizations by combining in-context editing and headless archicture in a full-stack JS environment.
    <br />
    <a href="https://docs.apostrophecms.org/"><strong>Documentation »</strong></a>
    <br />
    <br />
    <a href="http://dashboard.apostrophecmsdemo.org/">View Demo</a>
    ·
    <a href="https://github.com/apostrophecms/apostrophe/issues/new?assignees=&labels=bug&template=bug_report.md&title=">Report Bug</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#about-apostrophecms">About ApostropheCMS</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#extensions-and-integrations">Extensions and Integrations</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



## About ApostropheCMS

ApostropheCMS is content software for everyone in an organization. It helps teams of all sizes create dynamic digital experiences with elegance and efficiency by blending powerful features, developer happiness, and a low learning curve for content creators. Apostrophe has powered websites and web apps for organizations large and small for over a decade.

#### Built With

* [Node](https://nodejs.org/en/)
* [MongoDB](https://www.mongodb.com/)
* [Nunjucks](https://mozilla.github.io/nunjucks/)

## Getting Started

To get started with ApostropheCMS, follow these steps to set up a local development environment. For more detail, refer to the [Getting Started tutorial](https://docs.apostrophecms.org/getting-started/creating-your-first-project.html) in the documentation.

#### Prerequisites

We recommend installing the following with [Homebrew](https://brew.sh/) on macOS. If you're on Linux, you should use your package manager (apt or yum). If you're on Windows, we recommend the Windows Subsystem for Linux.

| Software | Minimum Version | Notes
| ------------- | ------------- | -----
| Xcode  | Current | Only needed on macOS
| Node.js | 8.x | Or better
| npm  | 6.x  | Or better
| MongoDB  | 3.6  | Or better
| Imagemagick (optional)  | Any | GIF support, faster image uploads


#### Installation
Our recomended way to start a new project with ApostropheCMS is to use the [Apostrophe CLI](https://github.com/apostrophecms/apostrophe-cli).

##### Install the Apostrophe CLI
 ```sh
  npm install -g apostrophe-cli
 ```
##### Create a project
```sh
apos create-project wonderful-project
```

##### Install dependencies
```sh
cd wonderful-project && npm install
```
##### Create an admin user add them to the admin group
```sh
node app.js apostrophe-users:add myUser admin
```
##### Run
```sh
node app.js
```

Navigate to `localhost:3000/login` to login with the admin credentials you created.
#### Next Steps
Check out our [Getting Started tutorial](https://docs.apostrophecms.org/getting-started/creating-your-first-project.html#working-with-areas) in the documentation to start adding content. Be sure to reference our [glossary of terms](https://docs.apostrophecms.org/reference/glossary.html) to get acquainted with the reference materials.

## Extensions and Integrations

You can find a complete list of [extensions](https://apostrophecms.com/extensions) on our website, but here are a few highlights:

#### Extend ApostropheCMS

- [apostrophe-headless](https://github.com/apostrophecms/apostrophe-headless) - Add REST APIs and power your React / Vue Native / etc. apps with a headless CMS.
- [apostrophe-blog](https://github.com/apostrophecms/apostrophe-blog) - Everything you need to put a blog on your site.
- [apostrophe-events](https://github.com/apostrophecms/apostrophe-events) - Manage upcoming events.
- [apostrophe-workflow](https://github.com/apostrophecms/apostrophe-workflow) - Add powerful localization capabilities to your project.
- [apostrophe-passport](https://github.com/apostrophecms/apostrophe-passport) - Authenticate via Twitter, Facebook, Github and more.
- [apostrophe-saml](https://github.com/apostrophecms/apostrophe-saml) - Authenticate via Shibboleth, as well as corporate SAML environments like Salesforce.
- [apostrophe-places](https://github.com/apostrophecms/apostrophe-places) - Manage geotagged content and display it on a map.
- [apostrophe-redirects](https://github.com/apostrophecms/apostrophe-redirects) - An easy redirects module.

#### Editor Extensions
- [Atom Snippets](https://github.com/apostrophecms/apostrophe-atom)
- [VS Snippets](https://marketplace.visualstudio.com/items?itemName=punkave.apostrophecms-vs-snippets)

## Contributing

We eagerly welcome open source contributions. Before submitting a PR, please read through our [Contribution Guide](https://github.com/apostrophecms/apostrophe/blob/main/CODE_OF_CONDUCT.md)

1. Fork the Project
2. Create a Feature Branch (`git checkout -b feature/LovelyFeature`)
3. Commit your Changes (`git commit -m 'Add some LovelyFeature'`)
4. Push to the Branch (`git push origin feature/LovelyFeature`)
5. Open a Pull Request



## License

ApostropheCMS is released under the [ MIT License](https://github.com/apostrophecms/apostrophe/blob/main/LICENSE.md).



## Contact

[Discord](https://discord.com/invite/XkbRNq7) - [Twitter](https://twitter.com/apostrophecms) - [Discussions](https://github.com/apostrophecms/apostrophe/discussions)
