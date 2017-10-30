# blog-tutorial-flat-packed

Hello, this is an example repository to demonstrate COPR SCM abilities.
Content of this repository is flat and packed.

**Flat** means there are no subpackages in the repository. In other words,
there are no subdirectories that would themselves contain a spec file.

**Packed** means the application source files are packed into a tarball
being referenced by a Source directive in the .spec file. Note that
the source tarball might not be actually present in the repository. Instead,
it can be provided externally through URL (specified in the "Source"
definition). The external sources will be then downloaded once needed 
during the build process.
