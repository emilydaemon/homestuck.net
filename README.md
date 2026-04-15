# Homestuck.net mirror

This is a slightly modified copy of homestuck.net's static source, ready for mirroring.

While it is currently deployed on my server at https://homestuck.donut.eu.org/, I strongly recommend you to host it yourself if you have the means. Read further for a guide.

## Table of Contents

- [About homestuck.net](#about-homestucknet)
- [Limitations](#limitations)
- [Installation](#installation)
- [License](#license)

## About homestuck.net

Homestuck.net was a static website that served as an archive for the Homestuck fandom and overall franchise. The archive was composed of a variety of HTML pages that linked to useful materials like sheet music, art tutorials, cosplay guides, and official content that was previously scattered around the internet and hard to find.

Unfortunately, on April 13th, 2026, the main author and hosting provider of homestuck.net's content decided to make the entire website act as a redirect for a Reddit post accusing the Homestuck team of many horrible things, which I won't get into here. This meant that a huge cornerstone of the Homestuck community was now inaccessible for no good reason, and that just won't do!

However, due to homestuck.net's nature as a static bundle of html files, it is very easy to host yourself. This repository's goal is to make it even easier by removing any remaining dependence on homestuck.net and to eventually act as a replacement if necessary.

## Limitations

- As this is a fork of homestuck.net's static website source, the resource booru has not been mirrored (and if it ever is, it won't be under this repo.)
- Jester Quest and Circus Break were not in the public source for homestuck.net that was available on GitHub (despite being referenced on several pages), and thus are not mirrored here. (TODO: scrape the files off of the internet archive and copy them here)

## Installation

To deploy the mirror on your own server, follow these instructions:

1. Clone the repository: `git clone https://github.com/emilydaemon/homestuck.net.git`
1. Configure your web server to serve that repository on a (sub)domain of your choosing. I also recommend you to deny access to the `.git` folder.
1. If necessary, add the subdomain you specified earlier to your DNS configuration.
1. Restart your web server. The mirror should now be online!

## License

This project is released under the MIT license, which means you can do whatever you want with it, even create your own fandom archive under your own name. However, please note that all fan content belongs to the original authors to the extent the concept applies to derivative works.
