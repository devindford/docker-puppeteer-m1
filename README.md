
# Docker Puppeteer for M1 macs

This container is set up to be able to run on M1 macs, but will also work on intel. The Dockerfile contians the env to pull the firefox product due to
the headless chrome casuing issues with Puppeteer it's self once it's spun up. I've kept the fonts in place in case they ever cause an issue since they are super small dependencies.

## Things to note
When writing your puppeteer js file, be sure to included `executablePath: firefox-esr` in your `browser.launch` arguments.

### Questions?
Feel free to reach out to me on Twitter [@DevinDFord](https://twitter.com/devindford)


