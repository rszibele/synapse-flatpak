# Synapse Flatpak

Ever wanted to run your own matrix server with flatpak?

This is the repository *just for you*.

## Requirements

You require a domain name and a tls certificate for matrix federation.
For instruction on how to create a letsencrypt certificate visit: https://certbot.eff.org/instructions

Make sure you have your `fullchain.pem` and `privkey.pem` ready when installing, you will be prompted to copy it to a directory.

## Installation

To install the Synapse Flatpak, run the following commands:

```bash
wget TODO
flatpak install TODO
```

During the first run of Synapse you will be guided through the setup with the wizard script.

## Usage

Run Synapse: `flatpak run org.matrix.synapse start`

Stop Synapse: just send the python process a SIGTERM signal

## TODO

* create a simple gui to start and stop it, preferably one with a notification tray icon
