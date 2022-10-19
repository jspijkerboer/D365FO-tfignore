# D365FO-tfignore

> **Note**  
> As I'm not working anymore on Dynamics for Finance and Operations, I will no longer be maintaining this list.  
> Please feel free to continue it yourselves. 🙂

## **Getting started**
Place the .tfignore file in the root of the metadata folder. (e.g. K:\AosService\PackagesLocalDirectory\)

For every source controlled model you can add the following entries. These folders only contain artifacts which are regenerated with each compile.
```
\Model\bin
\Model\Reports
\Model\Resources
\Model\WebContent
\Model\XppMetadata
```
> Note that when third party assemblies are placed in the `\Model\bin` folder, you still need to explicitly add them to version control. This behavior won't change when the default list of excluded file types is in place and this folder is added.

If you don't have the source code for a model, you don't have to add any entries.
