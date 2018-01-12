<p align="center">
  <img src="https://d26dzxoao6i3hh.cloudfront.net/items/0M0W110L142j0t2H0W2X/manta-logo.svg" alt="Manta App Logo" width="180" height="auto"/>
</p>

<h2>
  Manta
  <a href="https://travis-ci.org/hql287/Manta">
    <img src="https://travis-ci.org/hql287/Manta.svg?branch=dev" alt="Build Status">
  </a>
  <a href="https://github.com/hql287/Manta/releases/tag/v1.1.0">
    <img src="https://img.shields.io/badge/version-1.1.0-green.svg" alt="v1.1.0">
  </a>
  <a href="./LICENSE.md">
    <img src="https://img.shields.io/badge/license-GPL--3.0-blue.svg">
  </a>
</h2>

A desktop application for creating invoices with beautiful and customizable templates.

<a href="#screenshots">Screenshots</a> •
<a href="#features">Features</a> •
<a href="#downloads">Downloads</a> •
<a href="#technologies">Technologies</a> •
<a href="#why">Why?</a> •
<a href="#goals">Goals</a> •
<a href="#development">Development</a> •
<a href="#faq">FAQ</a>

### Screenshots

Here's a few screenshots:

![Example Invoice 1](https://d2ffutrenqvap3.cloudfront.net/items/2P1D0S412j0U2G0j443P/Sample%20Invoice%201.jpg?v=caa43ec7)

![Example Invoice 2](https://d2ffutrenqvap3.cloudfront.net/items/2X2s1z171A0w2j3Z2C0C/Sample%20Invoice%202.jpg?v=6e4e5945)

![Form](https://d2ffutrenqvap3.cloudfront.net/items/2z1m1t2f0E271p3T2w2v/Form%20UI.jpg?v=00bac22e)

![Invoices](https://d26dzxoao6i3hh.cloudfront.net/items/1u0O110V1R0V3W3f1a1k/screenshots3.jpg?v=8a5b5487)

### Features
* 🎚 Flexible form. You can turn on/off field and save as default setting.
* 🏗 Drag & drop for reordering items. This makes editing easier.
* 📐 Use SVGs for logo for better printing.
* 🎨  Custom designed & highly customizable templates.
* 🏷 Custom statuses for invoices.
* 📊 Export PDF for print or email.
* 🔒Complete Privacy. You financial data stays where it belongs.
* 💯 Totally Free.

### Downloads

macOS | Windows | Linux
-----------------| ---| ---|
<a href='https://github.com/hql287/Manta/releases/download/v1.1.0/Manta-1.1.0.dmg'>Download v1.1.0</a> | <a href="https://github.com/hql287/Manta/releases/download/v1.1.0/Manta.Setup.1.1.0.exe">Download v1.1.0</a> | <a href="https://github.com/hql287/Manta/releases/download/v1.1.0/Manta-1.1.0-x86_64.AppImage">Download v1.1.0</a> |

[More Download Options](https://github.com/hql287/Manta/releases)

### Technologies
* [Electron](https://github.com/electron/electron)
* [React](https://github.com/facebook/react)
* [Redux](https://github.com/reactjs/redux)
* [React-DnD](https://github.com/react-dnd/react-dnd)
* [React-Beautiful-DnD](https://github.com/atlassian/react-beautiful-dnd)
* [React-Motion](https://github.com/chenglou/react-motion)
* [Webpack](https://github.com/webpack/webpack)


### Why
The main reason I decided to build this is because I need a simple tool to create good looking invoices, estimates, and receipts but couldn't find one  that suits my needs. I don't do invoicing for a living but I do need it occasionally so an ideal invoicing app just needs to be good at one thing and one thing only, which is making invoices. I really don't need a full-fledged bookkeeping or accounting software.

I believe there are many people such as freelance designers, developers, photographers or writers... also have such need. However, most (if not all) products I found have these these problems:

**Complexity**

* Most invoicing products nowadays is web-based, which means you’ll need to maintain a new account (possible a monthly fee, too) just to create an invoice.
* Sure, there some open-source products that can be self-hosted, but that will introduce a new layer of complexity to your workflow. Who will setup the product? Who will maintain the server? Who will cover the cost? ...
* You will always need internet connection to be able to create your invoices. It can be slow sometimes.

**Privacy**

* When you use a web service, most of the time, you’re giving away your data whether you want it or not. Financial data is sensitive and I believe that no one should know about your data except yourself.


### Goals
With that in mind, I know that Manta would need to satisfy these criteria:

* 🚀 Fast!!!
* 👍 Friendly UI & UX
* 🎉 Has nice looking templates
* 🔒 Does not touch user’s data
* 💰 Free! :)

  If you think Manta delivers these, let me know by putting a star on this project 😉

### Development

It's very easy to get started with these 3 steps:

* Clone this project to your local machine.
* Open terminal and `cd` into the cloned folder, usually `cd Manta`.
* Run `yarn install` to install dependencies.
* Run `yarn dev` in one tab to start `webpack-dev-server`.
* Run `yarn start` in another tab to open the app.

This is still in beta and it's far from perfect so feedbacks, issues or PRs are greatly appreciated! :)

Note that on Linux you will need additional dependencies to provide the `icns2png` and `gm` commands.
Ubuntu/Debian users can run: `sudo apt install -y icnsutils graphicsmagick`.

### FAQ

* **Is this app built with Electron?**

Yes, it's built on top of [Electron](#). Please see the [Technologies](#technologies) section for more info.

* **What boilerplate did you use**

None. This is my attempt to integrate Electron with React from scratch. The idea was to get a better understanding of how things work together, especially Webpack.
But I do take cue from other projects.

* **What CSS/UI Framework did you use?**

I wrote all the CSS myself. I only use Bootstrap for prototyping at first. But I gradually encapsulate most of the style to the component with the help of [`styled-components`](https://www.styled-components.com/). There is some places still use Bootstrap mostly for layout purpose but I'll get rid of it eventually.

* **Where did you get the icons?**

[ionicons](http://ionicons.com/). They're great!

* **Why did you name the project Manta? It has nothing to do with invoicing.**

It's actually very common to associate an animal with your brand. There's a reason behind the Twitter bird, the famous MailChimp Freddy or the Docker whale ... It's called the Baby-Face bias. You can read more about it in the book [Designing for Emotion](https://abookapart.com/products/designing-for-emotion) by [Aaron Walter](http://aarronwalter.com/).
In my case, I was inspired by the movie [Racing Extinction](http://racingextinction.com/) and by naming this project Manta, I hope to raise people's awareness on some environmental issues mentioned in the movie. You can [read more about it here](https://manta.life/about)

* **I like Manta's logo, did you design it?**

Yes, I actually did all the illustrations as well as the templates that you see in the app.

* **Are you available for hire?**

Yes, kind of. I'm exploring new opportunities at the moment. Please let me know what you have in mind.

* **How do I contact you?**

If you find an issue, please report it here. For everything else, please drop me a line at hi@manta.life





