<div align="center">
    <img width="64" alt="drawdb logo" src="./src/assets/icon-dark.png">
    <h1>Open Executor</h1>
</div>

<h3 align="center">Free, simple, Roblox executor (Open-Source UI).</h3>

<div align="center" style="margin-bottom:12px;">
    <a href="https://drawdb.app/" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/badge/Start%20building-grey" alt="drawDB"/>
    </a>
    <a href="https://discord.gg/gCWBfGRRNZ" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/discord/1196658537208758412.svg?label=Join%20the%20Discord&logo=discord" alt="Discord"/>
    </a>
    <a href="https://x.com" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/badge/Follow%20us%20on%20X-blue?logo=X" alt="Follow us on X"/>
    </a>
    <a href="https://buymeacoffee.com" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/badge/Support%20us-grey?logo=buymeacoffee" alt="Support us"/>
    </a>
</div>

<h3 align="center"><img width="700" style="border-radius:5px;" alt="demo" src="drawdb.png"></h3>

Open Source Softworks provides a robust Executor UI with a open source code, meaning you can fork it, or use it on your own server. Or even you can use it for personal use! Open Exexutor has a built in scriptHub powered by RoScripts. A awesome and modern home tab, and a sleek monaco.

## Getting Started

### Local Development

```bash
git clone https://github.com/drawdb-io/drawdb
cd drawdb
npm install
npm run dev
```

### Build

```bash
git clone https://github.com/drawdb-io/drawdb
cd drawdb
npm install
npm run build
```

### Docker Build

```bash
docker build -t drawdb .
docker run -p 3000:80 drawdb
```

Set up the [server](https://github.com/drawdb-io/drawdb-server) and environment variables according to `.env.sample` for the survey and bug report forms.
