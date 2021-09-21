# Deprecated

Web Extensions Template has been superseded by **[Template](https://github.com/lukesrw/template)**

## Usage

### Clone

Use this template through the [GitHub "Use this template"](https://github.com/lukesrw/template/generate) function, or:

```
set project=my-new-project
git clone --depth=1 https://github.com/lukesrw/template.git %project%
rmdir /S /Q %project%\.git
git init %project%

```

### Setup

Once the Template has been cloned, you can type:

```
node tools/init extensions

```

This will download the Web Extensions blueprint files.
