# lukdes.github.io
Luke de Souza's portfolio

Made using GitHub pages bootstrapped with the Minimal template. 

## Testing the webiste locally
_if you already have Jekyll installed, skip to step 5_

**To install Jekyll:**

1. Ensure chruby and ruby-install are on your laptop
```shell
brew install chruby ruby-install
```

2. Install the correct version of Ruby (macOS comes with an old version pre-installed that doesn't work with Jekyll)
```shell
ruby-install ruby 3.4.7
```

3. Add chruby to your `~/.zshrc` and then restart your editor.
```shell
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.4.7" >> ~/.zshrc
source ~/.zshrc
```

4. Install jekyll!
```shell
gem install jekyll
```

**To run the website locally to preview changes:**

5. Then, navigate to this project folder and install the necessary bundles
```shell
bundle install
```

6. Finally, run the website locally
```shell
bundle exec jekyll serve
```

You should then be able to preview the website on `http://localhost:4000/`

Happy editing! 

---
<details>
  <summary>Useful Resources</summary>

  * [The Markdown Guide](https://www.markdownguide.org)
  * [Markdown Linter](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
  * [Markdown Shortcut](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) should allow you to use normal docs commands for formatting (e.g. command b for **bold**, command i for *italics*)
</details>
