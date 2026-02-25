---
permalink: /
---

# 🥷 *Blade*switch

![GitHub deployments](https://img.shields.io/github/deployments/anydigital/bladeswitch/github-pages?label=Jekyll&logo=github)
![Netlify](https://img.shields.io/netlify/ec716489-5d5d-43cb-9fa1-892f8479436e?label=Eleventy&logo=netlify)
[![GitHub Repo stars](https://img.shields.io/github/stars/anydigital/bladeswitch?label=GitHub)](https://github.com/anydigital/bladeswitch)

The only backward-compatible starter for _BOTH_ Jekyll and Eleventy (at the same time) 🥷

Don't vendor-lock your website — it's easy to start, and easy to switch!

<table>
  <tr>
    <th width="50%">🥷 <em>for</em> <big>Jekyll ↓ <a href="https://anydigital.github.io/bladeswitch/" target="_blank">Preview</a></big></th>
    <th width="50%">🥷 <em>for</em> <big>Eleventy ↓ <a href="https://bladeswitch.netlify.app/" target="_blank">Preview</a></big></th>
  </tr>

  <tr><th colspan="2">Minimal Dependencies:</th></tr>
  <tr>
    <td>
      <pre><h3>1. <a href="https://github.com/github/pages-gem" target="_blank">pages-gem[-jekyll]</a></h3><sub
      >via <a href="https://github.com/anydigital/bladeswitch/blob/main/Gemfile" target="_blank">Gemfile</a></sub></pre>
    </td>
    <td>
      <pre><h3>1. <a href="https://github.com/anydigital/eleventy-bricks" target="_blank">eleventy-bricks</a></h3><sub
      >via <a href="https://github.com/anydigital/bladeswitch/blob/main/package.json" target="_blank">package.json</a></sub></pre>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <pre><h3>2. <a href="https://github.com/anydigital/bricks" target="_blank" title="reusable template and CSS `bricks`">bricks[.css]</a></h3><sub
      >as remote_theme via <a href="https://github.com/anydigital/bladeswitch/blob/main/_config.yml#L1" target="_blank">_config.yml</a
      >   |   via <a href="https://github.com/anydigital/bladeswitch/blob/main/package.json" target="_blank">package.json</a></sub>           </pre>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <pre><h3>3. pico.css</h3><sub>from CDN via <a href="https://github.com/anydigital/bladeswitch/blob/main/_data/site.yml#L3" target="_blank">_data/site.yml</a></sub></pre>
    </td>
  </tr>

  <tr><th colspan="2"><br>Deploy 🥷 <em>Blade</em>switch:</th></tr>
  <tr>
    <td style="vertical-align: top">
      <p><a href="https://github.com/new?template_name=bladeswitch&template_owner=anydigital" target="_blank" role="button">
        Using Jekyll on GitHub Pages<br>
        <small>(natively, w/o GitHub Actions!)</small>
      </a></p>
      <h6>↓ then:</h6>
      2) go to <em>Settings → Pages</em><br>
      3) find <em>Build and Deployment</em><br>
      4) set <em>Branch=main</em> and <em>Save</em>.
    </td>
    <td style="vertical-align: top">
      <p><a href="https://app.netlify.com/start/deploy?repository=https://github.com/anydigital/bladeswitch" target="_blank" role="button">
        Using Eleventy on Netlify<br>
        <small>(all preconfigured!)</small>
      </a></p>
      <h6>→ done!</h6>
      (with Netlify no more actions needed)
    </td>
  </tr>
</table>
<style>
  th, td {
    text-align: center;
  }
  th {
    font-weight: bold;
  }
  td {
    border: none;
  }
  table pre {
    margin-bottom: 0;
  }
  pre {
    padding: 1rem 1.5rem;
  }
  pre h3 {
    margin-bottom: 0;
  }
</style>
