### Installing the app from flathub.org

See https://flathub.org/apps/details/com.github.simplex-chat for details.

### Local build

- Use `flatpak-builder --force-clean --repo=repo --user --install build-dir com.github.simplex-chat.metainfo.yaml` command to "build & install" the app into the local `./repo` repository.
- Then use `flatpak run com.github.simplex-chat` command to start the app.
