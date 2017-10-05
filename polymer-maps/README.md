Polymer Google Maps Codelab
===
See https://codelabs.developers.google.com/codelabs/polymer-maps/ for codelab instructions.

Those instructions require the use of Chrome Dev Editor to download & run the project. If you prefer to work with your own IDE, this is for you.

## Running the codelab without Chrome Dev Editor

If you're not using CDE, you'll need to install some command-line tools to manage dependencies and to run the demo.

1.  Download and install Node from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and `polymer-cli` globally:

        npm install -g bower polymer-cli

3.  Clone this repo:

        https://github.com/ComcastSamples/polymer-maps.git

4.  Change directory to your local repo and install dependencies with `bower`:

        cd polymer-maps
        bower install

5.  To preview your app, run `polymer serve` from the repo directory:

        polymer serve

    Open `http://localhost:8081` in your browser

If you're wondering what `polymer serve` does, see [Polymer CLI](https://www.polymer-project.org/2.0/docs/tools/polymer-cli) in the Polymer docs.
