# New Project Setup

## Copy the Repo

- `git clone --recurse-submodules https://github.com/caveman250/SparkTemplateProject`
- Update the remote url to your new git repo eg: `git remote set-url origin https://github.com/SomeUser/MyGame`
- In `app/CMakeLists.txt`, replace all instances of `TemplateProject` with your project name.
- Rename `app/src/TemplateApplication.h/.cpp` and update the name of the class to match.
- Update the application name in `app/src/main.cpp`
- Commit your changes.
- Copy the project: `git push --mirror`
- From here on out, use your git repo as normal.