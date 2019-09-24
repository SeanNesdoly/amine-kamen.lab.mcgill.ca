# amine-kamen.lab.mcgill.ca

This repository contains Prof. Amine Kamen's [Viral Vectors and Vaccines
Bioprocessing Group website](http://amine-kamen.lab.mcgill.ca/).

[Sean Nesdoly](https://github.com/SeanNesdoly) developed and currently maintains
the site. Send an email to srnesdoly@gmail.com for requests to update content or
contribute to the repository. For lab members, refer to the file
`website/kamen-website-instructions` contained within the google drive.

The website was built using the [Academic theme for
Hugo](https://themes.gohugo.io/academic/), an open-source framework for building
static websites. The repository was originally forked from
[academic-kickstart](https://github.com/sourcethemes/academic-kickstart); refer
to their README for prerequisites and details on setting up your own website.

## Steps for Contributing Content

1. [Download and install Git](https://git-scm.com/downloads)
2. [Download and install Hugo](https://gohugo.io/getting-started/installing/#quick-install)
3. Clone the repository onto your local machine:
    ```
    git clone https://github.com/SeanNesdoly/amine-kamen.lab.mcgill.ca.git
    ```
4. Initialize the git submodule for the Hugo academic theme, stored at `themes/academic`:
    ```
    cd PATH/TO/amine-kamen.lab.mcgill.ca
    git submodule update --init --recursive
    ```
5. Compile and view the local website:
    - `hugo server` -- run this from the root of the project
    - Navigate to [localhost:1313](http://localhost:1313) and view the generated
      webiste. Real-time changes made to local files are reflected here.
6. Read the [Quick Start Guide](https://sourcethemes.com/academic/docs/) to
   learn how to add markdown content and customize the site.
7. Make your changes to the website. Contact srnesdoly@gmail.com to be added as
   a contributor on the repository.

## Resources

The links below contain documentation and guides for setting up, building, and
deploying a **Hugo** website using the **academic** theme:

1. [Hugo framework for building websites](https://gohugo.io/)
2. [Academic theme homepage](https://sourcethemes.com/academic/)
3. [hugo-academic github repository](https://github.com/gcushen/hugo-academic/)

## License

Copyright 2017 [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.
