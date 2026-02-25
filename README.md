---
permalink: /
---

# 🥷 *Blade*switch

The only backward-compatible starter for _BOTH_ Jekyll and Eleventy (at the same time) 🥷

Don't vendor-lock your website — it's easy to start, and easy to switch!

<table>
  <tr>
    <th width="50%"><big>Jekyll ↓ <a href="https://anydigital.github.io/bladeswitch/" target="_blank">Preview</a></big></th>
    <th width="50%"><big>Eleventy ↓ <a href="https://bladeswitch.netlify.app/" target="_blank">Preview</a></big></th>
  </tr>

  <tr><th colspan="2">Minimal Dependencies:</th></tr>
  <tr>
    <td colspan="2">
      <pre><h3>1. pico.css</h3><sub>from CDN via <a href="https://github.com/anydigital/bladeswitch/blob/main/_data/site.yml#L3" target="_blank">_data/site.yml</a></sub></pre>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <pre><h3>2. <a href="https://github.com/anydigital/bricks" target="_blank" title="reusable template and CSS `bricks`">bricks[.css]</a></h3><sub
      >as remote_theme via <a href="https://github.com/anydigital/bladeswitch/blob/main/_config.yml#L1" target="_blank">_config.yml</a
      >    |    via <a href="https://github.com/anydigital/bladeswitch/blob/main/package.json" target="_blank">package.json</a></sub></pre>
    </td>
  </tr>
  <tr>
    <td>
      <pre><h3>3. github-pages<br>   [jekyll gem]</h3><sub>via <a href="https://github.com/anydigital/bladeswitch/blob/main/Gemfile" target="_blank">Gemfile</a></sub></pre>
    </td>
    <td>
      <pre><h3 style="text-align: left">3. eleventy<br>4. <a href="https://github.com/anydigital/eleventy-bricks" target="_blank">eleventy-bricks</a></h3><sub
      >via <a href="https://github.com/anydigital/bladeswitch/blob/main/package.json" target="_blank">package.json</a></sub></pre>
    </td>
  </tr>

  <tr><th colspan="2">Deploy 🥷 <em>Blade</em>switch:</th></tr>
  <tr>
    <td style="vertical-align: top">
      <p><a href="https://github.com/new?template_name=bladeswitch&template_owner=anydigital" target="_blank" role="button">
        Using Jekyll on GitHub Pages<br>
        <small>(natively, w/o GH Actions!)</small>
      </a></p>
      <h6>↓ then:</h6>
      2) Go to <em>Settings → Pages</em><br>
      3) Find <em>Build & Deployment → Branch</em><br>
      4) Select `main` and Save.<br>
    </td>
    <td style="vertical-align: top">
      <p><a href="https://app.netlify.com/start/deploy?repository=https://github.com/anydigital/bladeswitch" target="_blank" role="button">
        Using Eleventy on Netlify<br>
        <small>(preconfigured!)</small>
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
