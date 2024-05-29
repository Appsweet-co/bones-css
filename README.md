<p align="center">
  <img src="assets/readme/logo.png" alt="Logo" width="150" height="auto" />
</p>

<h1 align="center">@appsweet-co/bones-css</h1>

<p align="center">
  <b>A lightweight utility for working with skeleton text and images</b></br>
</p>

<br />

## Quick Start

### Install

```zsh
npm i @appsweet-co/bones-css
```

Add the CSS file to your HTML as needed.

```html
<link rel="stylesheet" href="./node_modules/@appsweet-co/bones-css/dist/bones.min.css">
```

You can also import Spock CSS directly from a CDN.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@appsweet-co/bones-css@latest/dist/bones.min.css">
  
<!-- OR -->
  
<link rel="stylesheet" href="https://unpkg.com/@appsweet-co/bones-css@latest/dist/bones.min.css">
```

Remember to replace `latest` with a specifc version number when using the CDN. See [Unpkg](https://unpkg.com/) and [jsDelivr](https://www.jsdelivr.com/) for details.

### Usage

Add the `bones` class to any element.

```html
<h1 class="bones" style="--bones-inline-size: 65%;">Hidden Text Here</h1>
<p class="bones">Also hidden here</p>
<p class="bones">And here</p>
```

Include the `animated` class to animate the elements.

```html
<h1 class="bones animated" style="--bones-inline-size: 65%;">Hidden Text Here</h1>
<p class="bones animated">Also hidden here</p>
<p class="bones animated">And here</p>
```

You can also add custom CSS as needed.
