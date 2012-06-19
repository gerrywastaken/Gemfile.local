A local Gemfile where you can add gems that you don't want to add to the repository

# Install

Copy Gemfile.local into project root and add the following to your .gitignore:

	/Gemfile.local
	/Gemfile.local.lock

To use Gemfile.local run:

	bundle --gemfile Gemfile.local

Note: This should store a config in the .bundle/config file and then read from that, however I couldn't get this to work for the BUNDLE_GEMFILE config no matter what I tried. There is a bug request to add this as standard functionality to Bundler, however it appears there is nobody around to work on it:
https://github.com/carlhuda/bundler/issues/183#issuecomment-595008 