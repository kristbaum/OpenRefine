# OpenRefine

<p>
<a href="https://snapcraft.io/openrefine"><img src="https://snapcraft.io/openrefine/badge.svg" alt="Snap Status"></a>
</p>

Snap version of [OpenRefine](https://openrefine.org).

## Try it locally

Build the snap locally and install it for a quick smoke test:

```bash
snapcraft
sudo snap install --dangerous openrefine_*.snap
snap run openrefine
```

After testing, remove the snap and clean the build assets:

```bash
sudo snap remove openrefine
snapcraft clean
```
