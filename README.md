 <p style="color:#990099;font-size:34px;"> <b>Science | DIY <br> Music | Photography</b></p>
  

## Own life history evolution :)
<p align="justify">
Endemic from <a href= "https://www.youtube.com/watch?v=NcyXbcsTLtU">Santiago</a>, Chile. I've spent almost my whole life in Santiago. I studied Biology at the <a href = "http://biologia.uc.cl/es/">School of  Biological Sciences</a> @ <a href= "http://www.uc.cl/"> Pontifical Catholic University of Chile</a> between 2009-2013. During that time, I worked doing traditional experimental eco-physiology @ <a href ="http://labecofisiouc.wixsite.com/ecofisio"> Pancho Bozinovic's Lab</a>, and also volunteering as field technician during the summers in Southern Chile monitoring terrestrial carnivores populations. The last year of my undergrad, I went to Navarno Island for a year, I worked <a href = "http://www.labwankara.com/">@Wankara Lab</a> monitoring freshwater insect populations as indicators of Global Warming and also, monitoring the introduced population of the American mink (<i>Neovison vison</i>) in Patagonia. 
</p>

## Current interests
<p align="justify">
In March, 2016, I got back to the 'civilization', starting a PhD @ Catholic University, under the supervision of <a href = "http://biologia.uc.cl/es/cuerpo-academico/profesor/45"> Pablo Marquet</a> and <a href = "http://biologia.uc.cl/es/cuerpo-academico/profesor/40">Juan Keymer</a>, I started my PhD project aiming to understand the ecology of an invasive strategy, such as cancer, within the human ecosystem.<br>
  Other approaches that I do to get closer of natural manifestations is though photography, I enjoy trekking and nature wildlife photographs (I have a bias to animals above plants or landscapes) and also I love to mix some sounds, producing something of Experimental music.<br>
  Also, a bit closer to electronic stuffs, I'm just discovering DIY technologies, so I'll try to post my advances here, of course I belive in open access, then use/share/edit all you find here, as you wish.</p>

## Usage

To use the Minimal theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-minimal
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Minimal will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## Roadmap

See the [open issues](https://github.com/pages-themes/minimal/issues) for a list of proposed features (and known issues).

## Project philosophy

The Minimal theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Minimal? We'd love your help. Minimal is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/minimal`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
