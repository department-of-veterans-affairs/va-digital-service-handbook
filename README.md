# VA Digital Service Handbook

Helping Veterans Affairs (VA) teams design, build, and launch great digital services that meet the [Digital Service Standard](href="https://github.com/department-of-veterans-affairs/va-digital-service-handbook/digital-standard") for the [Veteran-facing Services Platform](#fn1).

Contact @ehuntdsva for any questions, comments, or feedback.


## Contributing

* **DSVA team**: See [the repo Wiki](https://github.com/department-of-veterans-affairs/va-digital-service-handbook/wiki) for
  * How this Jekyll site is organized
  * How to use Markdown for writing/editing content
  * How to update the ```modified-date``` that displays on site pages.
* See [CONTRIBUTING](CONTRIBUTING.md) for how to contribute content.


## Development

This is a Jekyll-built static site.

1. Clone/fork this repo.
2. For best results (urls work correctly), run locally at 127.0.0.1:4000/va-digital-service-handbook/

    ```
    bundle exec jekyll serve
    ```

3. Whenever you make a change to content, also change the ```modified-date``` in the yml at the top of the relevant ```.md``` file.

    * The ```modified-date``` is pulled into the ```footer.html``` include for all pages, except for the Home page.
    * For the Home page, the ```modified-date``` is pulled into the ```home.html``` layout.


## License

All content is available under the [Creative Commons Zero v1.0 Universal license](LICENSE), except where otherwise stated.


## Colophon

* Jekyll front-end code inspired by [login.gov](https://www.login.gov)

<hr>

<a name="fn1"></a>The *Veteran-facing Services Platform* is the set of technologies (and processes) that run the current [Vets.gov](https://www.vets.gov/) website. VA teams who want to release a digital service for veterans using the Veteran-facing Services Platform should use this [Handbook](http://department-of-veterans-affairs.github.io/va-digital-service-handbook/) to learn how to do that.

* In the short-term, veteran digital services built using the Veteran-facing Services Platform will be accessible through the Vets.gov domain.
* In the future, veteran digital services built using the Veteran-facing Services Platform will be accessible through the VA.gov domain.
