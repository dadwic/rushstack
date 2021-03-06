---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [ISharedTypeScriptConfiguration](./heft.isharedtypescriptconfiguration.md) &gt; [copyFromCacheMode](./heft.isharedtypescriptconfiguration.copyfromcachemode.md)

## ISharedTypeScriptConfiguration.copyFromCacheMode property

Can be set to 'copy' or 'hardlink'. If set to 'copy', copy files from cache. If set to 'hardlink', files will be hardlinked to the cache location. This option is useful when producing a tarball of build output as TAR files don't handle these hardlinks correctly. 'hardlink' is the default behavior.

<b>Signature:</b>

```typescript
copyFromCacheMode?: CopyFromCacheMode | undefined;
```
