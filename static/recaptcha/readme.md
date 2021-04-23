A collection of various reCAPTCHA deployment types, for testing purposes.

Contributions and new tests for edge cases are welcome.

Just copy/paste one of the existing html files as reference (and use a meaningful file name).

The backend currently support these reCAPTCHA types and keys:
```js
{
    "v2-checkbox": "6LcU-rUaAAAAAHG4SFI_PJfVLtYyuVRuU_DRuIXy",
    "v2-invisible": "6LfAGLYaAAAAALoLXYu2vn27KBemkjiVceMYmBUh",
    "v3": "6Lc2GbYaAAAAAO7eQ7Xs4uPdEmlz3BD3aAxf94Lw"
}
```

You can either provide e.g. `&type=v2-checkbox` or `&site_key=6LcU-rUaAAAAAHG4SFI_PJfVLtYyuVRuU_DRuIXy` to the verification backend.

