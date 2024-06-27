# Slidev Theme Mint

[![NPM version](https://img.shields.io/npm/v/slidev-theme-mint?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-mint) ![NPM Downloads](https://img.shields.io/npm/dm/slidev-theme-mint)


A mint theme for [Slidev](https://github.com/slidevjs/slidev).

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>mint</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides the following layouts:

<table>
  <tr>
    <th width="50%">Screenshot</th>
    <th width="50%">Description</th>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/1.png" />
    </td>
    <td>
      Layout : <code>cover</code><br/>
      Options : <br/>
      <ul>
        <li>
          <code>image</code> - optional<br>
          default: https://cover.sli.dev
        </li>
      </ul>
    </td>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/2.png" />
    </td>
    <td>
      Layout : <code>default</code><br/>
      Options : -
    </td>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/6.png" />
    </td>
    <td>
      Layout : <code>default-alt</code><br/>
      Options : -
    </td>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/4.png" />
    </td>
    <td>
      Layout : <code>image-right</code><br/>
      Options : <br/>
      <ul>
        <li>
          <code>image</code> - optional<br>
          default: https://cover.sli.dev
        </li>
        <li>
          <code>imageClass</code> - optional<br>
          default: -
        </li>
      </ul>
    </td>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/5.png" />
    </td>
    <td>
      Layout : <code>image-left</code><br/>
      Options : <br/>
      <ul>
        <li>
          <code>image</code> - optional<br>
          default: https://cover.sli.dev
        </li>
        <li>
          <code>imageClass</code> - optional<br>
          default: -
        </li>
      </ul>
    </td>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/9.png" />
    </td>
    <td>
      Layout : <code>end</code><br/>
      Options : -
    </td>
  </tr>
</table>

## Other Sample

Checkout other implementation from available layout

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/1.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/2.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/3.png" /></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/4.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/5.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/6.png" /></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/7.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/8.png" /></td>
    <td><img src="https://raw.githubusercontent.com/alfatta/slidev-theme-mint/main/screenshot/9.png" /></td>
  </tr>
</table>

## Contributing

- `pnpm install`
- `pnpm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `pnpm run export` to generate the preview PDF
- `pnpm run screenshot` to generate the preview PNG
