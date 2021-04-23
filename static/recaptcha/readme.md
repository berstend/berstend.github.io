## A collection of various reCAPTCHA deployment types, for testing purposes.

Link: https://berstend.github.io/static/recaptcha/

Contributions and new tests for edge cases are welcome:
* Copy/paste one of the existing html files as reference
* Use a meaningful file name in the pattern of the existing ones
* Update the `<pre>` tag in the html file with bullet points/references as needed

The backend currently support these reCAPTCHA types and keys:
```js
{
    "v2-checkbox": "6LcU-rUaAAAAAHG4SFI_PJfVLtYyuVRuU_DRuIXy",
    "v2-invisible": "6LfAGLYaAAAAALoLXYu2vn27KBemkjiVceMYmBUh",
    "v3": "6Lc2GbYaAAAAAO7eQ7Xs4uPdEmlz3BD3aAxf94Lw"
}
```

You can either provide e.g. `&type=v2-checkbox` or `&site_key=6LcU-rUaAAAAAHG4SFI_PJfVLtYyuVRuU_DRuIXy` to the verification backend.

## Documentation

* v2
    * checkbox: https://developers.google.com/recaptcha/docs/display
    * invisible: https://developers.google.com/recaptcha/docs/invisible
* v3
    * https://developers.google.com/recaptcha/docs/v3
* Enterprise
    * https://cloud.google.com/recaptcha-enterprise/docs/resources
