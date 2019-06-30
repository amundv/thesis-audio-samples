## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/amundv/thesis-presentation/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/amundv/thesis-presentation/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<p>These samples are reconstructions from a VQ-VAE that compresses the audio input over 64x times into discrete latent codes (see figure below). Both the VQ-VAE and latent space are trained end-to-end without relying on phonemes or information other than the waveform itself. Although the reconstructed waveforms are very different in shape from the originals, they sound very similar.</p>

<blockquote>
  <p><img src="/homepage/images/reconstruct.jpg" width="85%" height="85%" style="margin-bottom: 40px" />
Originals and reconstructions</p>
  <audio src="/homepage/audio/pt1_orig1.wav" controls="controls"></audio>
  <audio src="/homepage/audio/pt1_recon1.wav" controls="controls"></audio>
  <p> </p>
  <audio src="/homepage/audio/pt1_orig2.wav" controls="controls"></audio>
  <audio src="/homepage/audio/pt1_recon2.wav" controls="controls"></audio>
  <p> </p>
  <audio src="/homepage/audio/pt1_orig3.wav" controls="controls"></audio>
  <audio src="/homepage/audio/pt1_recon3.wav" controls="controls"></audio>
</blockquote>

