---
title: Template Overrides

---

Template Overrides
==================
Gantry offers users the ability to override default template configurations for individual overrides. A frequent example is to have a different layout configuration on your site's front page from its subpages. Gantry makes this achievable in just a few clicks. In fact, you can configure different layouts for each of your subpages individually.

> [![](../assets/g4-overrides.jpg)](http://youtube.com/embed/8uiWjekdjfE)
>
> Discover the power of Gantry and its ability to configure any parameter based on template overrides using custom template styles. Gantry adds the power of inheritance of settings to enable easier per-override custom configurations.


Creating an Override
--------------------
There are two methods of creating a new set of assignable configurations. The first is the **Save as Copy** method which involves you editing the Gantry template at **Admin Dashboard → Theme Settings**. Configure your settings, select **Save as Copy** from the **Save** dropdown, and change the override name from **Duplicate Override** to your own.

![](assets/template-override-save-as-copy.jpg)

Alternatively, you can simply click on the **New Override** button, change the name of the newly created override and modify all of the parameters from scratch. Please note that when creating a new override, the beggining parameters are always the same as the ones set in the **Default Settings** override.


Configuring an Override
-----------------------
Once an **Override** has been created, you simply need to switch to it (if you weren't automatically) and configure. Each tab will have greyed out parameters that can be activated via the checkbox.

![](assets/template-override-assigned-params.jpg)

Configure items, then click on the **Assignments** tab. All content type items are listed here, so just check the items you want this particular Override to apply to.

![](assets/template-override-assign-menus.jpg)


Override Examples
-----------------
Below is an example of an Override. The **Layouts → MainBody Positions** setting has been overridden. Therefore, in the screenshots below, you can see that the sidebar allocation can be either left or right of the main body without being applied globally. This is the same for other settings like *Gizmos* or *Styles*, as well.

| ![][example1] | ![][example2] |
|---------------|---------------|
| ![][config1]  | ![][config2]  |


[config1]: assets/template-override-example-config1.jpg
[config2]: assets/template-override-example-config2.jpg
[example1]: assets/template-override-example1.jpg
[example2]: assets/template-override-example2.jpg
