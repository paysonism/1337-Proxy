# 1337 Proxy

This is an advanced web proxy and website unblocker. You can choose from select games or
visit any website you want!

## Features

- about:blank Cloaking (hides from search history)
- Tab Cloaking
- Wide collection of apps & games
- Clean, Easy to use UI
- Inspect Element
- Various Themes
- Password Protection (Optional)
- Built-in Tab System
- Now.gg Support
- Fast Speeds
- Geforce NOW Support

## Deployment

> [!IMPORTANT]
> You **cannot** deploy to static web hosts, including Netlify, Cloudflare Pages, and GitHub Pages.

### Setup and Usage

To setup and use this project locally, just download the source and run these commands in cmd in that folder.

Install [Node.JS](https://nodejs.org/)

`npm install`  
`npm start`

### GitHub Codespaces

1. Create a GitHub account if you haven't already.
2. Click "Code" (green button) and then "Create Codespace on main."
3. In the terminal at the bottom, paste `pnpm i && pnpm start`.
4. Respond to the application popup by clicking "Make public."
   > [!IMPORTANT]
   > Make sure you click the "Make public." button, or the proxy won't function properly.
5. Access the deployed website from the ports tab.
6. For subsequent uses in the same codespace, just run `pnpm start`

### Solution for if there is no popup.

1. Run `pnpm i`, and before `pnpm start`, prepend `PORT=8080`, replacing 8080 with another port. For example, `PORT=6969 pnpm start`.
2. If this does not work then you can prepend `$env:PORT=8080;`, replacing 8080 with another port. For example, `$env:PORT=6969; pnpm start`
3. Go to the ports tab, Click Forward A Port, And type the port number.
4. Right-click Visibility and set Port Visibility to Public.

## Report Issues

If you have any issues or encounter any errors please open an issue [here](https://github.com/paysonism/1337-Proxy/issues)

# Credits

Made By [Payson](https://github.com/paysonism) and [Interstellar](https://github.com/InterstellarNetwork/Interstellar/graphs/contributors)
