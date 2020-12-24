# pal-mette [TODO]

"palmette" is an anagram of template.  It wraps a template element, and allows adding "ornaments" to the template on "blossoming" into the DOM.

```html
<pal-mette -model +template-cloned ft="time-to-bloom" -in-shadow -adjacent>
    <template>
    </template>
</pal-mette>
```

Nothing happens until attribute "time-to-bloom" (in this case) is set.  ft stands for "flowering trigger."  Event "template-cloned" is fired, allowing for modification to the template