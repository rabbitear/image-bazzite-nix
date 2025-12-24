# image-bazzite-nix

My attempt to have a bazzite image with Nix style packages for use on the desktop.  I include Gnome desktop, and a couple of basic cli utilities that I like.

### Added commandline utilities

tmux helix vim ripgrep duf iotop ncdu bat fzf tree

gnome-desktop group

The /nix directory should be presistent so that you can run say, DX Nix installer to install to /nix directory.

## Switch to Your Image

From your bootc system, run the following command substituting in your Github username and image name where noted.
```bash
sudo bootc switch ghcr.io/<username>/<image_name>
```
This should queue your image for the next reboot, which you can do immediately after the command finishes. You have officially set up your custom image! See the following section for an explanation of the important parts of the template for customization.

## Community Examples

These are images derived from this template (or similar enough to this template). Reference them when building your image!

- [m2Giles' OS](https://github.com/m2giles/m2os)
- [bOS](https://github.com/bsherman/bos)
- [Homer](https://github.com/bketelsen/homer/)
- [Amy OS](https://github.com/astrovm/amyos)
- [VeneOS](https://github.com/Venefilyn/veneos)

Let me know if something is not true on this page.
