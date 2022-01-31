# brainly-ipsum-plugin-content

Repository of content for Brainly Ipsum Figma Plugin

1. [Adding texts](#adding-texts)
1. [Adding images](#adding-images)
1. [Tabs](#tabs)
1. [Groups](#groups)


## Adding texts

Add array item to `data.json` file.

`label`, `type`, `body` - properties required

Example:

```json
{
  "label": "Short question",
  "type": "text",
  "body": "How much is the fish?"
}
```

## Adding images

Upload image to `/images` and copy url. Add array item to `data.json` file with url of uploaded file.

`label`, `type`, `url` - properties required

Example:

```json
{
  "label": "Question attachment",
  "type": "image",
  "url": "https://raw.githubusercontent.com/brainly/brainly-ipsum-plugin-content/main/images/question-attachment.jpeg"
}
```

## Tabs

Add `section` property to item.

Example:

```json
{
  "section": "Q&A",
  "label": "Short question",
  "type": "text",
  "body": "How much is the fish?"
}
```

## Groups

Add `group` property to item.

Example:

```json
{
  "group": "Questions",
  "label": "Short question",
  "type": "text",
  "body": "How much is the fish?"
}
```




