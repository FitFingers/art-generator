# art-generator
A python script to generate random art.

## To run:
- From the command line, `cd` into a python-ready directory (this may not be necessary, but my jupyter kernel only connects in one directory that I set up specifically for it).
- Create an `images` and a `metadata` directory at the root-level of the project.
- Populate the `trait-layers` directory with the image layers required for random generation (for example, backgrounds, colours, accessories).
- Edit the `generate.ipytnb` script to use the files from `trait-layers`.
- Add any extra options required in the script and adjust the weights.
- Run the script from VSCode itself or from the command line with `jupyter notebook generate.ipynb`.
- The generated images should now be available in the `images` directory and each image's metadata is available as a separate file within the `metadata` folder.
