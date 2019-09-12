# cli-minify

CLI to minify files.

I created this library to minify files from a deployment pipeline.

## Usage

Create a script in the project's `composer.json`:

    "scripts": {
      "minify": "minify src/ dist/",
    }

From the pipeline run:

    composer run-script minify
