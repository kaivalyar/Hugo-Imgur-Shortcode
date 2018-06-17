# Hugo-Imgur-Shortcode

Embed Imgur Images into Hugo blog posts Automagically

## Synopsis

[Shortcodes](https://gohugo.io/content-management/shortcodes/) provide a way to maintain the simplicity of your Hugo blog posts in Markdown, while allowing you to insert ugly-but-necessary HTML snippets into your pages. While there are many shortcodes already available in Hugo by default, there are none to embed Imgur posts.

## Example

1. Copy the `imgur.html` file into your `/layouts/shortcodes` folder (create this, if you don't already have it).
2. In your Markdown post, simply insert `{{< imgur id=" ... " >}}`.
3. In your favourite browser, navigate to the Imgur post you want to embed, and find its ID (the code at the end of the URL). As you can see in the [demo](https://github.com/kaivalyar/Hugo-Imgur-Shortcode/blob/master/example/content/posts/Demo.md), for [https://imgur.com/a/vRbDiHJ](https://imgur.com/a/vRbDiHJ), this ID is `vRbDiHJ`.
4. Replace ` ... ` in step 2 with this ID.

## Issues

Please submit an Issue via GitHub if you encounter any errors using this shortcode. Additionally, you may fork the project and submit a Pull Request too. 

## License

**This project is protected by the MIT License.**
