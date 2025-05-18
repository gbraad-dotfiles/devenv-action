gbraad's Dotfiles `devenv` action
=================================

Use dotfiles' `devenv`-command to start instant development environments

### Usage

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

Have a look here for an [example workflows](https://github.com/gbraad-dotfiles/actions-test/blob/main/.github/workflows/test-devenv.yml).
