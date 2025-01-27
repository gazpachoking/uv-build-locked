uv-build-locked: Publish locked dependencies
#############################################

My original intention was to port the hatchling plugin to use the uv lock file, but I ended up
making it more specific to our use case. Might come back to this and generalize, but if anyone
is looking for the technique, it's here:
https://github.com/Flexget/Flexget/blob/fffd347c5cede77bee89e0fdb39c901ca7dc7bb3/build_locked_extras.py