Email testing: Email on Acid is recommended, but Litmus is another option. 

600px max-width is considered the safest max width for emails

Each table should have `role="presentation"` for accessibility purposes

Preferred doctype for html emails for best rendering across email clients:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

If using a email client, remove comments from html, comments can get your email sent to spam (and increase file size)

When adding margin, use a capital M (for outlook)

[Outlook Conditional CSS]("https://stackoverflow.design/email/base/mso/")

The center tag is no longer valid in HTML5, but is still valid in email html

```html
<center></center>
```

For background images with text and content on top of it, we always want the image to be the exact dimensions of the container. To solve the problem of background images in window clients, we need `Vector Markup Language`

Buttons and Borders for Outlook:

- add a border to the link of 1px with the same background color
- add a background color to the table data tag using the `bgcolor` attr instead of in the style tag
- add `display: inline-block` to the a tag
- the border radius won't work in outlook clients but we will get a box button using above tips
