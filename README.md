# Unity Package Template
This is a stripped back unity template intended to be used to develop and publish unity packages.

# To Do
Integrate git release publishing (see notes)

# Resources
https://nagachiang.github.io/tutorial-working-with-custom-package-in-unity-2019-2/#
https://neogeek.dev/creating-custom-packages-for-unity-2018.3/
https://blog.gemserk.com/2019/03/25/sharing-code-between-unity-projects/

# Notes
- The following command will create a release branch only containing contents of the package (PACKAGE_FOLDER_PATH change to e.g Packages/my-target-package) 
git subtree push --prefix PACKAGE_FOLDER_PATH origin upm

- Need to switch default branch of repo to be the /upm branch