---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [ICopyStaticAssetsConfiguration](./heft.icopystaticassetsconfiguration.md)

## ICopyStaticAssetsConfiguration interface


<b>Signature:</b>

```typescript
export interface ICopyStaticAssetsConfiguration extends ISharedCopyStaticAssetsConfiguration 
```
<b>Extends:</b> [ISharedCopyStaticAssetsConfiguration](./heft.isharedcopystaticassetsconfiguration.md)

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [destinationFolderNames](./heft.icopystaticassetsconfiguration.destinationfoldernames.md) | string\[\] | The folder(s) to which assets should be copied. For example \["lib", "lib-cjs"\]. This defaults to \["lib"\]<!-- -->These folders are directly under the folder containing the project's package.json file |
|  [sourceFolderName](./heft.icopystaticassetsconfiguration.sourcefoldername.md) | string | The folder from which assets should be copied. For example, "src". This defaults to "src".<!-- -->This folder is directly under the folder containing the project's package.json file |

