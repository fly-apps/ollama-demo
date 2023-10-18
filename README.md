# [Ollama](https://github.com/jmorganca/ollama) demo app for Fly.io

First deploy with:
```
fly apps create ollama-demo
fly deploy --vm-gpu-kind a100-pcie-40gb --volume-initial-size 100
```

From there for following deploys use:
```
fly deploy
```

Once deployed, interact with the [Rest API](https://github.com/jmorganca/ollama#rest-api) at https://ollama-demo.fly.dev/
