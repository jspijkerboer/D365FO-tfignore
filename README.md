# D365FO-tfignore

## **Getting started**
Place the .tfignore file in the root of the metadata folder. (e.g. K:\AosService\PackagesLocalDirectory\)

For every source controlled model you can add the following entries. These folders only contain artifacts which are regenerated with each compile.
```
\Model\Reports
\Model\Resources
\Model\WebContent
\Model\XppMetadata
```

If you don't have the source code for a model, you don't have to add any entries.