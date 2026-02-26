---
permalink: /
---

# 🥷 *Blade*switch

<div markdown="1">

![GitHub Release](https://img.shields.io/github/v/release/anydigital/bladeswitch?color=black&label=%20)
![GitHub deployments](https://img.shields.io/github/deployments/anydigital/bladeswitch/github-pages?label=Jekyll&logo=github)
![Netlify](https://img.shields.io/netlify/ec716489-5d5d-43cb-9fa1-892f8479436e?label=Eleventy&logo=netlify)
[![GitHub Repo stars](https://img.shields.io/github/stars/anydigital/bladeswitch?label=GitHub)](https://github.com/anydigital/bladeswitch)

</div>

The only starter compatible with _BOTH_ (!) Jekyll and Eleventy at the same time (so you can develop locally using 11ty w/o Ruby, but deploy natively to GitHub Pages using Jekyll w/o any GitHub Actions). Focus on the _Content_, not on the _Generator_!

---

It has only <big>3</big> direct dependencies:

<table>
  <tr>
    <th width="50%">
      &nbsp;🥷 <em>for</em> <big>Jekyll</big>&nbsp;
      <sup><a href="https://anydigital.github.io/bladeswitch/" target="_blank">PREVIEW</a></sup>
    </th>
    <th width="50%">
      &nbsp;🥷 <em>for</em> <big>Eleventy</big>&nbsp;
      <sup><a href="https://bladeswitch.netlify.app/" target="_blank">PREVIEW</a></sup>
    </th>
  </tr>
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
      <pre><h3>2. <a href="https://github.com/picocss/pico" target="_blank">pico.css</a></h3><sub>from CDN via <a href="https://github.com/anydigital/bladeswitch/blob/main/_data/site.yml#L3" target="_blank">_data/site.yml</a></sub></pre>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <pre><h3>3. <a href="https://github.com/anydigital/bricks" target="_blank">bricks[.css]</a></h3><sub
      >as remote_theme via <a href="https://github.com/anydigital/bladeswitch/blob/main/_config.yml#L1" target="_blank">_config.yml</a
      > or via <a href="https://github.com/anydigital/bladeswitch/blob/main/package.json" target="_blank">package.json</a> for 11ty</sub></pre>
    </td>
  </tr>
</table>
<!-- these styles are only for the table above, feel free to remove them -->
<style>
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

## Deploy Options

<div class="grid"><div markdown="1">

###### A. Natively, w/o GitHub Actions:

<p><a href="https://github.com/new?template_name=bladeswitch&template_owner=anydigital" target="_blank" role="button">
  Using Jekyll on GitHub Pages
</a></p>

1. Click ↑ to init your own repo.
2. Go to ⚙️ _Settings → Pages_.
3. Set _Branch = main_ and _Save_.

</div><div markdown="1">

###### B. Fully preconfigured:

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/anydigital/bladeswitch" target="_blank" role="button">
  Using Eleventy on Netlify
</a>

</div></div>

---

Repo: https://github.com/anydigital/bladeswitch

Featured in: https://any.digital/tricks/11ty/#min-starters

<!-- @TODO: via bricks.css -->
<style>
  a > i > img {
    max-height: 1.25em;
    margin-top: -0.125em;
    margin-right: 0.25rem;
  }
</style>
