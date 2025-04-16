# Jekyll template: Gallery

The template is built using [Jekyll](https://jekyllrb.com/), a static site generator. You can use it to create your own gallery easily.

This template uses [wsrv.nl](https://wsrv.nl) for image processing as well as CDN and caching services.

This is a modified version of the [original project](https://github.com/PatrickJnr/vp) by [Patrick Jr](https://github.com/PatrickJnr). Thank him very much!

---
## Demo
[This link](https://gallery-template.wzwtt.eu.org)

## How to use

1. Use this template.
2. Edit information about your own website, especially the information in [`_config.yml`](_config.yml).
3. Deploy to Github Pages or other platform, remember to change or delete the existing CNAME information.


## How to post a new gallery

Just create a new markdown file in `_posts` folder and name it like the [existing file](_posts/2025-04-14-Hello-World.md).

You can store your images in your object storage server, but don't store them directly in your website project because we don't design it that way and it's a bad practice.

Note that if your images are stored on [Imgur](https://imgur.com), wsrv.nl cannot directly fetch the images due to [access restrictions](https://github.com/weserv/images/issues/319#issuecomment-962594280), so you should use a proxy. The following is an example, but it may not be available, and you need to identify the possible privacy risks. You can use this proxy service, or change to another one.

```
https://img.noobzone.ru/getimg.php?url=https://i.imgur.com/zIcnrJH.png
```

## License

Just like the original project, the code for this template is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

The copyright of all sample images belongs to the original rights holders.