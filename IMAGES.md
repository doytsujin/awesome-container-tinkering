# Tools To Deal With Container Images

## Image Build Tools

### ⭐ BuildKit

<a href="https://github.com/moby/buildkit">BuildKit</a> - "concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit."

### ⭐ Docker buildx plugin

<a href="https://github.com/docker/buildx">buildx</a> - "Docker CLI plugin for extended build capabilities with BuildKit." The plugin provides the familiar `docker build`-like UX but on top of a more powerful build engine (BuildKit). It also includes a tool called <a href="https://github.com/docker/buildx/blob/master/docs/reference/buildx_bake.md">bake</a> that allows building all the images in an application together and let the users define project specific reusable build flows. In other words, _bake_ is a container-aware _make_.

### Buildah

<a href="https://github.com/containers/buildah">Buildah</a> - "A tool that facilitates building OCI images."

### kaniko

<a href="https://github.com/GoogleContainerTools/kaniko">kaniko</a> - "Build Container Images In Kubernetes."

### 🪦 makisu

<a href="https://github.com/uber-archive/makisu">makisu</a> - [discontinued] "Fast and flexible Docker image building tool, works in unprivileged containerized environments like Mesos and Kubernetes."

### ko

<a href="https://github.com/ko-build/ko">ko</a> - "Build and deploy Go applications on Kubernetes."

### Jib

<a href="https://github.com/GoogleContainerTools/jib">Jib</a> - "Build container images for your Java applications."

### Packer

<a href="https://github.com/hashicorp/packer">Packer</a> - "A tool for creating identical machine images for multiple platforms from a single source configuration." Packer is primarily focused on producing virtual machine images but it also allows building Docker, LXC, and LXD images using a similar to VM-provisioning procedure (read, by putting shell commands into a HCL file).

### apko

<a href="https://github.com/chainguard-dev/apko">apko</a> - "Build OCI images using APK directly without Dockerfile."

### melange

<a href="https://github.com/chainguard-dev/melange">melange</a> - "Build APKs from source code". A complimentary tool for apko.

### Nixery

<a href="https://github.com/tazjin/nixery"></a> - "Docker images on the fly with Nix". A Docker-compatible container registry that transparently builds images using the Nix package manager.

### buildg

<a href="https://github.com/ktock/buildg">buildg</a> - "Interactive debugger for Dockerfile, with support for IDEs (VS Code, Emacs, Neovim, etc)."


## Image Edit & Copy

### skopeo

<a href="https://github.com/containers/skopeo">skopeo</a> - "Work with remote images registries - retrieving information, images, signing content."

### umoci

<a href="https://github.com/opencontainers/umoci">umoci</a> - "umoci modifies Open Container images."

### go-containerregistry/crane

<a href="https://github.com/google/go-containerregistry/blob/main/cmd/crane/README.md">crane</a> - "A tool for interacting with remote images and registries."

### go-containerregistry/krane

<a href="https://github.com/google/go-containerregistry/blob/main/cmd/krane/README.md">krane</a> - "A drop-in replacement for crane that supports common Kubernetes-based workload identity mechanisms."


## Image Inspection Tools

### dive

<a href="https://github.com/wagoodman/dive">dive</a> - "A tool for exploring each layer in a docker image."

### container-diff

<a href="https://github.com/GoogleContainerTools/container-diff">container-diff</a> - "Diff your Docker containers."


## Image Optimization

### DockerSlim

<a href="https://github.com/docker-slim/docker-slim">DockerSlim</a> - "Don't change anything in your Docker container image and minify it by up to 30x (and for compiled languages even more)."


## Libraries

### go-containerregistry

<a href="https://github.com/google/go-containerregistry">go-containerregistry</a> - "Go library for working with container registries."

### image

<a href="https://github.com/containers/image">image</a> - "A set of Go libraries aimed at working in various way with containers' images and container image registries (pull, push, inspect w/o pulling, translate from one image format to another)." skopeo is backed by this library.

### storage

<a href="https://github.com/containers/storage">storage</a> - "A Go library which aims to provide methods for storing filesystem layers, container images, and containers" (with a CLI included).