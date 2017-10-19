+++
title = "Shortcodes"
+++

# Shortcodes

## message

```
{{%/* message class="is-info" title="Sample message" */%}}
You've got a information.
{{%/* /message */%}}
```

{{% sample column="true" lang="html" %}}
{{% message class="is-info" title="Sample message" %}}
You've got a information.
{{% /message %}}
{{% /sample %}}

---

## notification

{{< sample column="true" lang="html" >}}
  {{< notification class="is-warning" >}}
    <p>A whethered book is on the desk...</p>
  {{< /notification >}}
{{< /sample >}}