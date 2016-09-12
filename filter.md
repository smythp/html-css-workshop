
# Filtering

If you want to apply a style to `<strong>` tags, but only those that appear within a paragraph, you would use this syntax:

```
p strong {
	color: red;
	font-weight: bold;
}
```

The most specific rule in CSS always takes precedence. So if you also had this rule set:

```
string {
	color: green;
}
```

Then text inside a `<strong>` element would appear red inside paragraph tags and green everywhere else.
