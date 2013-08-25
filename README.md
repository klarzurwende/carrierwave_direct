This is a fork of: https://github.com/dwilkie/carrierwave_direct made for personal use.

carrierwave_direct is great, but unique filenames broke my paths and filenames.

(see https://github.com/dwilkie/carrierwave_direct/issues/98)

This version preserves CarrierWave's defaults, by not overriding the filename and full_filename methods.

**TODO:**

Time permitting, my plan is to make this a configuration option, test it, then submit a pull request back to the original CarrierWaveDirect.
