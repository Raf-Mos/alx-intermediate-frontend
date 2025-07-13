# 0x03 SASS/SCSS

This directory contains projects and exercises focused on learning SASS (Syntactically Awesome Style Sheets), a CSS preprocessor that adds features like variables, nesting, mixins, and functions to CSS.

## Learning Objectives

- Understand what SASS is and how it differs from CSS
- Learn to use SASS variables
- Master SASS nesting capabilities
- Create and use mixins for reusable code
- Use debug statements for development

## Requirements

- SASS/SCSS compiler
- Node.js (version 20.16 recommended)
- Text editor or IDE

## Installation

See `0-installation-script` for detailed installation instructions for different operating systems.

## Files

| File | Description |
|------|-------------|
| `0-installation-script` | Installation steps for SASS on different platforms |
| `0-debug_log.scss` | SASS file that outputs a debug message "Hello world" |
| `1-color_variable.scss` | Uses SASS variables to assign text color to body and p tags |
| `2-nested_tag.scss` | Demonstrates SASS nesting with body and p tag styling |
| `3-mixin_margins.scss` | Uses mixins to apply margins to body and div elements |

## Usage

To compile SASS files to CSS, use the following command:

```bash
sass input.scss output.css
```

To watch for changes and auto-compile:

```bash
sass --watch input.scss:output.css
```

To see debug output:

```bash
sass 0-debug_log.scss
```

## Examples

### Variables
```scss
$primary-color: #3D3D3D;

body {
  color: $primary-color;
}
```

### Nesting
```scss
body {
  margin: 0;
  
  p {
    margin: 10px;
  }
}
```

### Mixins
```scss
@mixin margin-horizontal($margin) {
  margin-left: $margin;
  margin-right: $margin;
}

div {
  @include margin-horizontal(15px);
}
```

## Resources

- [SASS Official Documentation](https://sass-lang.com/)
- [SASS Basics](https://sass-lang.com/guide)
- [CSS Preprocessors Guide](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor)

## Author

ALX Intermediate Frontend Development Course
