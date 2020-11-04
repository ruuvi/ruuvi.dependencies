# ruuvi.dependencies
Scripts to download Ruuvi community projects and dependencies of projects for offline use. Note that each dependency has their own licenses.

# Usage
Run  ./clone_projects.sh

# Adding your project to the list
Open a pull request with a line `git -C $PROJECT pull || git clone --recurse-submodules $PROJECT_URL`.
Please place the project in alphabetical order of URLs.
If your project needs some extra steps, such as wgetting submodules, add that step too.