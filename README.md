# Case Study of Browser DOM Vulnerabilities

> Inspired by [js-vuln-db](https://github.com/tunz/js-vuln-db)

## Firefox

CVE Number | Module | Label | Credit
---------- | ------ | ----- | ------
[CVE-2017-5447](./Firefox/CVE-2017-5447.md) | gfxTextRun | OOB Read | ifratric

## Edge

CVE Number | Module | Label | Credit
---------- | ------ | ----- | ------
[CVE-2016-0003](./Edge/CVE-2016-0003.md) | CDOMTextNode | Type Confusion | unknown
[CVE-2017-0037](./Edge/CVE-2017-0037.md) | CssParser | Type Confusion | ifratric
[CVE-2017-8496](./Edge/CVE-2017-8496.md) | CssParser | Type Confusion | ifratric

## Webkit

CVE Number | Module | Label | Credit
---------- | ------ | ----- | ------
[CVE-2018-4197](./Webkit/CVE-2018-4197.md) | RenderTreeBuilder | UAF | ifratric
[CVE-2018-4306](./Webkit/CVE-2018-4306.md) | Node | UAF | ifratric
[CVE-2018-4312](./Webkit/CVE-2018-4312.md) | AXObjectCache | UAF | ifratric
[CVE-2018-4315](./Webkit/CVE-2018-4315.md) | SVGTRefElement | UAF, SVG | ifratric
[CVE-2018-4317](./Webkit/CVE-2018-4317.md) | RenderLayer | UAF | ifratric
[CVE-2018-4318](./Webkit/CVE-2018-4318.md) | SVGTextLayoutAttributes | UAF, SVG | ifratric
[CVE-2018-4323](./Webkit/CVE-2018-4323.md) | RenderMultiColumnSet | UAF | ifratric
[CVE-2018-4328](./Webkit/CVE-2018-4328.md) | InlineTextBox | OOB Read | ifratric

## IE

CVE Number | Module | Label | Credit
---------- | ------ | ----- | ------
[CVE-2012-4792](./IE/CVE-2012-4792.md) | CButton | UAF | unknown
[CVE-2015-6152](./IE/CVE-2015-6152.md) | CObjectElement | UAF | unknown
