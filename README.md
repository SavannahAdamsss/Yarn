# Yarn
Learning Yarn


Now that you have Yarn installed, you can start using Yarn. Here are some of the most common commands you’ll need.

Starting a new project

yarn init
Adding a dependency

yarn add [package]
yarn add [package]@[version]
yarn add [package]@[tag]
Adding a dependency to different categories of dependencies

Add to devDependencies, peerDependencies, and optionalDependencies respectively:

yarn add [package] --dev
yarn add [package] --peer
yarn add [package] --optional
Upgrading a dependency

yarn upgrade [package]
yarn upgrade [package]@[version]
yarn upgrade [package]@[tag]
Removing a dependency

yarn remove [package]
Installing all the dependencies of project

yarn
or

yarn install
