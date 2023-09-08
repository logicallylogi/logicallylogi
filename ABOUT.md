## About this repository
If you're here, you probably want to check out some of my code. You can use my Foxtrot utility: which manages the multiple package managers, repositories, licenses, and Git all for you, or you can opt to do it yourself. If you choose to use Foxtrot, you can discard most of this information.

To clone a specific repository, you should be aware of how to use Git functionality such as submodules. While this repository is a "Monorepository", all the code is split up on Github to take advantage of features like Issues and Actions. You may, of course, go through my Github profile and check the repositories out from there to view the code, however I'd recommend using the monorepository since everything is configured specifically for use in this system.

Simply running `git clone https://github.com/logicallylogi/logicallylogi` is enough to get ALL the code in this repository.

### Using foxtrot
`foxtrot` is a Python utility designed to handle as much of the process involved in my monorepository for you. By running `foxtrot get [project_name]`, you are able to get the source code, license information, and it'll also download the dependencies required for that project, the language package managers/compiliers needed, AND verify the information, all seamlessly. If you don't know what project you want to get - just run `foxtrot get` and it'll give you a list of projects available for pulling, their license information, and their version.
