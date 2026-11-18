#### Install Podman

Open a terminal and run:

```bash
sudo apt update
sudo apt upgrade -y
```


With your system up‑to‑date, install Podman directly from Ubuntu’s official repositories:

```bash
sudo apt install -y podman
```


Check that Podman installed correctly by querying its version:

```bash
podman --version
```


Finally, test Podman by running a simple OCI container:

```bash
podman run --rm docker.io/library/ubuntu:24.04 echo "Hello from Podman!"
```


______________________

> CISO | oswaldo.diaz@inegi.org.mx 