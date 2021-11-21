This repo contains a large number of Backstage metadata files all referenced from a single `Location`.

They can be used to reproduce a timeout in the Roadie implementation of the catalog-import plugin. They can also be used to demonstrate the need for features like [this](https://github.com/backstage/backstage/issues/8165).

To re-create the metadata files, use the provided `generator.rb`.

```bash
ruby generator.rb
```
