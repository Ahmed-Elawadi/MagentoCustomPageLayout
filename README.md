# Magento Custom Page Layout
Adding additional layout template options to the CMS section that can be chosen when creating or editing a page in the admin interface.

# How To Use
1- Update config.xml with your new page
<br />
```xml
<!-- New Template -->
<new_template module="page" translate="label">
  	<label>New Template</label>
  	<template>page/new-template.phtml</template>
  	<layout_handle>new_template</layout_handle>
</new_template>
```
2- upload your new template file into app/design/frontend/default/default/template/page
<br />
or to your custom template

