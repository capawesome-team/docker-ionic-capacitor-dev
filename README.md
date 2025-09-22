# docker-ionic-capacitor-dev

🐳 Docker image for use as [VSCode Code Remote - Container](https://code.visualstudio.com/docs/remote/containers) in [Capacitor](https://capacitorjs.com/) projects.

<div class="capawesome-z29o10a">
  <a href="https://cloud.capawesome.io/" target="_blank">
    <img alt="Deliver Live Updates to your Capacitor app with Capawesome Cloud" src="https://cloud.capawesome.io/assets/banners/cloud-deploy-real-time-app-updates.png?t=1" />
  </a>
</div>

## Usage

### Pull image

Pull from GitHub Container Registry:  

```
docker pull ghcr.io/capawesome-team/docker-ionic-capacitor-dev:latest
```

### Build image

Build locally:  

```
docker build -t capawesome-team/ionic-capacitor-dev .
```

Build from GitHub:  

```
docker build -t capawesome-team/ionic-capacitor-dev https://github.com/capawesome-team/docker-ionic-capacitor-dev.git#main
```

Available build arguments:  

- JAVA_VERSION (Default: `17`)
- NODEJS_VERSION (Default: `20`)
- ANDROID_SDK_VERSION (Default: `11076708`)
- ANDROID_BUILD_TOOLS_VERSION (Default: `34.0.0`)
- ANDROID_PLATFORMS_VERSION (Default: `34`)
- GRADLE_VERSION (Default: `8.2.1`)
- IONIC_VERSION (Default: `7.2.0`)
- CAPACITOR_VERSION (Default: `6.0.0`)
- RUBY_VERSION (Default: `3.2.2`)
- CHROME_VERSION (Default: `114.0.5735.99`)

### Run image

Run the docker image:  

```
docker run -it capawesome-team/ionic-capacitor-dev bash
```
