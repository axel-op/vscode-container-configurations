# C++ with Conan definition

This definition is based on the C++ default definition and set up the Conan dependency manager.

By using this definition, you can directly use Conan commands in the terminal of the container.

You can also set these commands in the `launch.json` or `tasks.json` of your project, so they're executed when you press F5. [Here's an example](https://github.com/axel-op/vscode-containerdevelopment-cpp-conan).

This definition also contains a [`.vscode/c_cpp_properties.json`](./.vscode/c_cpp_properties.json) file. The important value here to include in your project is the `includePath` parameter, which will resolve your imports.
