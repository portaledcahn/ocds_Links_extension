# Links

This extension adds a top-level object named links to include events in a contracting process (in non-OCDS format).

## Usage

A government might only publish OCDS data for new events in a contracting process. However, they would still want to have a link back to any earlier events (in non-OCDS format).

To satisfy such use cases, the `release/links` field should be used.

## Example

```json
{
  "links": [
    {
      "rel": "self",
      "href": "https//..."
    }
  ]
}
```

## Changelog

This extension was originally discussed in <https://github.com/open-contracting/standard/issues/928>.


## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.