# cotr-static-viz
Mock ups for COTR static text visualisations

## Sass: compile and compress

### Requirements

* Ruby Sass v3.7.3 (or above)

    Install with Homebrew `brew install sass`

### Run locally

When working on the project, run `sass` locally to compile and compress css.

```
sass --watch main.scss:main.min.css --style compressed
```

The line above will take a `main.css` file and output a `main.min.css` one in the same folder.
