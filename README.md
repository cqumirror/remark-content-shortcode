## remark plugin shortcode
This plugin support shortcode in `Hugo` style. 

### Example
An example is as follows:
```markdown
{{% notice note %}}
this is a note
{{% /notice %}}
```

All the available shortcodes are:
```markdown
{{% notice note %}}
this is a note
{{% /notice %}}

{{% notice info %}}
this is an info
{{% /notice %}}

{{% notice warn %}}
this is a warnning
{{% /notice %}}

{{% notice error %}}
this is an error
{{% /notice %}}
```

Don't forget to add a line blank behind and before each shortcode block. It's better to add a `<br>` behind each block.

### LICENSE
MIT
