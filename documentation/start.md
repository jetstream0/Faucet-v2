# Welcome!
This faucet is made to be easily configurable, letting non developers easily fork the project and run their faucet within a hour. On the other hand, experienced developers should be able to easily make tweaks, extend the faucet, and implement their own features.

As mentioned, this faucet is very easy to set up, but if you don't want to expend the effort, or are having issues, you can [hire me](https://prussia.dev).

## Quick Start
This project is fairly "light" and can be run easily on free services like Repl.it. It is written in Node.js, so most other services like Heroku, cPanel, and any VPS can also be used to host this faucet. You can even run it on your own computer, although it is not recommended to do so for uptime reasons.

It is also recommended to buy a domain name. Registrars like Porkbun or Namecheap are good options, although anything that is reputable and widely used is fine (tip: don't use GoDaddy). Also, if using Repl.it, a free pinger service like UptimeRobot is recommended.

Most likely, the only files you will need to edit are the [`.env` file](secrets.md) and [`config.json` file](config.md). 

Additionally, it is recommended you add a logo image to /files/LOGO.png (an example LOGO.png is provided, make something like that and replace it).

Only two accounts need to be made: MongoDB (database) and hCaptcha (captcha, alternatively prussia captcha could also be used). Both are free.

## Why Run a Faucet?

## Contributing

## Advanced
For more customized faucets, it is recommended you know Javascript, HTMl, and CSS, or hire someone who does ([like me, Prussia](https://prussia.dev)). Likely, your customization needs can be met by editing the relevant HTML files in /templates, and the css files in /files (images should be added to /files).