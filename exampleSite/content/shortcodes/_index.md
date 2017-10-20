+++
title = "Shortcodes"
+++

# Shortcodes

Vireframe provides a few shortcodes to work with Bulma CSS styles. You can use them freely inside any content page sources (commonly `.md` and `.html` files).

## message

Renders a message box. You can specify a color and/or a title.

### code

```
{{%/* message class="is-info" title="Hello" */%}}
You've got a information.
{{%/* /message */%}}
```

### result

{{% sample column="true" %}}
{{% message class="is-info" title="Hello" %}}
You've got a information.
{{% /message %}}
{{% /sample %}}

---

## notification

Render a simple notification.

### code

```
{{</* notification class="is-warning" */>}}
  <p>A whethered book is on the desk...</p>
{{</* /notification */>}}
```

### result

{{< sample column="true" >}}
{{< notification class="is-warning" >}}
  <p>A whethered book is on the desk...</p>
{{< /notification >}}
{{< /sample >}}