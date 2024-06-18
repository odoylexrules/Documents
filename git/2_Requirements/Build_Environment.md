### Building Git from source:
To build Git from source, ensure you have the necessary development libraries
and environment settings.

### Installation Steps:
Insta the necessary build tools and libraries using your system's package
manager.

#### Compiler and Build Tools:
- **GNU Compiler Collection (GCC)**
- **dh-autoreconf**
- **curl**
- **autotools**
- **install-info**

#### Development Libraries:
- **libcurl4-gnutls-dev**
- **libexpat1-dev**
- **gettext**
- **ligz-dev**
- **libssl-dev**

### Configuration Steps.
Set up the build environment before compiling application

#### Environment Variables:
- Ensure the 'PATH' variable includes the path to the 'git' binaries after
  installation is complete
- Set 'CFLAGS' and 'LDFLAGS' as needed for compilation and linking. Only really 
  required for specific specialized environments. autotools et al takes care of
  this very nicely.

#### Working Directory
- Create a dedicated directory for building 'git' to keep source files organized.
- Example commands:
`user@host:~$ mkdir /tmp/git-build`

#### Configure Package Manager:
- Keep the system packages updated to ensure dependencies are current.
- Be aware of any CVEs that may be current to all your package requirements.
