dotfiles devenv action
======================

Use dotfiles' `devenv`-command to start instant development environments

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Run devenv command
        uses: gbraad-dotfiles/devenv-action@main
        with:
          prefix: dotfedora
          command: shell
          args: cat /etc/os-release
```
       