A local Gemfile where you can add gems that you don't want to add to the repository

# Install

To start using Gemfile.local copy the file into project root and run:

	bundle --gemfile Gemfile.local

Add the following to your .gitignore:

	/Gemfile.local
	/Gemfile.local.lock