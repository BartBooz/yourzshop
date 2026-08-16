# yourzshop

Placeholder site for [yourzshop.com](https://yourzshop.com) — on its way.

## Stack

Static HTML served by Caddy, deployed on Railway from this GitHub repository.

## Local

```bash
docker build -t yourzshop .
docker run --rm -p 8080:8080 -e PORT=8080 yourzshop
```

Then open [http://localhost:8080](http://localhost:8080).
