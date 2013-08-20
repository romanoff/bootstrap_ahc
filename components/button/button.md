Button
======
Options
-------
Use any of the available button classes to quickly create a styled button.

```ahcx
<bootstrap.Button name="Default" />
<bootstrap.Button name="Primary" type="primary" />
<bootstrap.Button name="Success" type="success" />
<bootstrap.Button name="Info" type="info" />
<bootstrap.Button name="Warning" type="warning" />
<bootstrap.Button name="Danger" type="danger" />
<bootstrap.Button name="Link" type="link" />
```

Sizes
-----
Fancy larger or smaller buttons? Add `.btn-lg`, `.btn-sm`, or `.btn-xs` for additional sizes.

```ahcx
<bootstrap.Button name="Large Button" size="large"/>
<bootstrap.Button name="Large Button" type="primary" size="large"/>
```

```ahcx
<bootstrap.Button name="Default Button" />
<bootstrap.Button name="Default Button" type="primary" />
```

```ahcx
<bootstrap.Button name="Small Button" size="small" />
<bootstrap.Button name="Small Button" type="primary" size="small" />
```

```ahcx
<bootstrap.Button name="Extra Small Button" size="xsmall" />
<bootstrap.Button name="Extra Small Button" type="primary" size="xsmall" />
```

Create block level buttons—those that span the full width of a parent— by adding `.btn-block`.

```ahcx
<bootstrap.Button name="Block level button" size="large" block="true"/>
<bootstrap.Button name="Block level button" type="primary" size="large" block="true"/>
```

Disabled state
--------------

Make buttons look unclickable by fading them back 50%.

Button element
--------------

Add the `disabled` attribute to `<button>` buttons.

```ahcx
<bootstrap.Button name="Primary button" type="primary" size="large" disabled="true"/>
<bootstrap.Button name="Button" size="large" disabled="true"/>
```

> Cross-browser compatibility
> ---------------------------

> If you add the `disabled` attribute to a `<button>`, Internet Explorer 9 and below will render text gray with a nasty text-shadow that we cannot fix.

We use `.disabled` as a utility class here, similar to the common `.active` class, so no prefix is required.

> Link functionality not impacted

> This class will only change the `<a>`'s appearance, not its functionality. Use custom JavaScript to disable links here.
