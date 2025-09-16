# Portfolio (Just the Docs)ßß

## Local preview

```bash
# Ruby 3.2+ recommended
gem install bundler
bundle install
bundle exec jekyll serve
```

Open [http://127.0.0.1:4000](http://127.0.0.1:4000)

## Deploy on GitHub Pages

1. Push this repo to GitHub as `portfolio-jtd` (or any name).
2. Ensure default branch is `main`.
3. The provided GitHub Actions workflow builds and deploys to Pages automatically.
4. In **Settings → Pages**, confirm "Build and deployment" is set to **GitHub Actions**.

## Customize

* `_config.yml`: title, description, aux_links (LinkedIn, Email, GitHub).
* Page content: edit the `.md` files.
* Styling: tweak `assets/css/custom.scss`.

## References

* Just the Docs: [https://just-the-docs.github.io/just-the-docs/](https://just-the-docs.github.io/just-the-docs/)
* Jekyll: [https://jekyllrb.com/docs/](https://jekyllrb.com/docs/)
