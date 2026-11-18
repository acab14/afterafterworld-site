# Images

Drop image files here (`.png`, `.jpg`, `.webp`, `.svg`) and reference them from
any page. Anything in this folder is published to the **public** site, so only
add art you're happy to share publicly and have the rights to.

## Reference an image in a page

```markdown
![Una, forged in her father's flame]({{ "/assets/images/una-dragon.jpg" | relative_url }})
```

The `relative_url` filter prepends the site's base path so links work both
locally and live — always use it for asset paths.

## Full-width banner at the top of a page

```markdown
![The Dragonsmoot]({{ "/assets/images/dragonsmoot-banner.jpg" | relative_url }}){: .banner }
```

## Sidebar logo

Put a logo here and uncomment the `logo:` line in `_config.yml`:

```yaml
logo: "/assets/images/logo.png"
```
