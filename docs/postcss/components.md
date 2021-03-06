#Components

Components refer to custom modules that are developed during production.

##Buttons

Buttons are styled all at once at first and then extended using simple class modifiers. Focus and hover states are also combined to ensure proper keyboard and mouse focus. Disabled styles are also provided to prevent any sort of confusion during interaction.

```postcss
.button {
  /* styles */

  &-hollow {}

  &-condensed {}

}
```

##Logo

The logo component is your site's logo combined with a link. The default setup includes the logo as a svg symbol. It can also be used in conjunction with an img element or a background image. The following example creates a flexible background based logo given a max-width and height.

**Background Based Logo**

```postcss
.site-logo {
  height: em(80);
  max-width: em(380);
  width: 100%;
  background: url("../images/logo.svg") no-repeat 0 50%;
  background-size: contain;
}
```

##Search

The search component contains selectors for the default pug search partial that isn't integrated into any particular search platform.
