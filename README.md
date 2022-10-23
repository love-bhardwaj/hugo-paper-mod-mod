# Paper Mod Mod (Hugo Theme)

Hugo Paper Mod Mod is a Hugo theme based on [HugoPaperMod](https://adityatelange.github.io/hugo-PaperMod/) which is a theme based on [hugo-paper](https://github.com/nanxiaobei/hugo-paper).

## Updates

A few of the updates made are highlighted below:

1. Subtle scaling transformation to list items (magnify) when the mouse hovers over them<br>
   https://user-images.githubusercontent.com/69479854/197366805-0c391919-67db-44e2-91e6-4f572a7e2cd4.mov

2. Tags are now buttons<br>
   <img width="850" alt="Tags are now buttons" src="https://user-images.githubusercontent.com/69479854/197366868-3a65847a-5749-43b5-a628-57eb532943dd.png">

3. Color enhancements to the bottom of post tags, nav buttons, share icons, etc<br>
   <img width="1016" alt="Bottom of post in light mode" src="https://user-images.githubusercontent.com/69479854/197366886-07e04690-e61d-441d-a185-f018ac152abb.png">

4. Table for content in light mode<br>
   <img width="933" alt="Table of content in light mode" src="https://user-images.githubusercontent.com/69479854/197366887-365d1eec-3ba4-463d-85ef-b76b7a458c73.png">

## Installation

1. Clone it to the `themes` directory for your Hugo website directly:

```sh
git clone git clone https://github.com/adityatelange/hugo-PaperMod themes/hugo-paper-mod-mod --depth=1 themes/hugo-paper-mod-mod --depth=1
```

2. Use `git submodule` to add the repo directly to your Hugo website:

```sh
git submodule add --depth=1 https://github.com/love-bhardwaj/hugo-paper-mod-mod.git themes/PaperMod
git submodule update --init --recursive # required when you clone your repo (submodules may not get cloned automatically)
```

3. [Download](https://github.com/love-bhardwaj/hugo-paper-mod-mod/archive/refs/heads/main.zip) zip files and place
   the extracted files in the themes repo.

The theme name is `hugo-paper-mod-mod` add it to your `config.yaml` or whichever format your Hugo config file is in.
