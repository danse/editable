##### Versions

This was scaffolded with:

```
$ pulp --version
Pulp version 10.0.0
psc version 0.10.2 using /home/francesco/node_modules/.bin/psc
```

I downgraded some dependencies from 3 to 2 because of [this
issue](https://github.com/bodil/pulp/issues/265)

##### Run the server

    pulp server

This will serve `index.html` with compiled Purescript, see [Pulp
docs](https://github.com/bodil/pulp/#a-quick-example)