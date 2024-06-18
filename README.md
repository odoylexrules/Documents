### Documents Project:
This is largely intended for my own use to administer the tools I use on a 
regular basis. If you have found this page. I bid you much luck on finding 
answers to your own questions and solutions to any problem that may have. 
If you require help with any of these tools, by all means send me a 
request for documentation to be added or what have you to [odoylexrules](mailto:mintopintohintodoo@gmail.com), 
and I'll try to get back to you at my earliest convenience.

#### Directory Structure, and schema:
**<Program_name>/**
- *1_About.md*: This is just a brief overview and argument for the 
program that I will be expanding on within the parent directory.
- **2_Requirements/**
  This directory will be a good starting point for satisfying any 
  questions about a particular systems suitability, and may contain 
  a walk-through on setting up a development environment for the named tool.
  - **Build_Environment.md**
    You will find instructions on configuring a system to build the 
    application. Such things as tools needed for compiling, libraries for
    their respective headers, and any other detail required for installing 
    comfertably.
  - **Hardware.md**
    For the most part, modern systems satisfy requirements to run most tools. 
    But, for example you may be using Xen Project for your virtualization. 
    Here you will find details on what you will need to install happily.
  - **Syscalls_and_Permissions.md**
    Proper configuration of apparmor, sysctl, cgroups or any other tool 
    where you will want documentation on what's happening under the hood 
    can be found here. Some tools require elevated privileges, for example 
    ansible can be used by absolutely anyone, but to administer mysql, you 
    will need to be root.
  - *'firenail.poc.md'*: A simple example of the kind of thing you may find 
    here. If I find PoCs in regards to exploitation, I will be sharing how 
    to use them, and the source code required to test potency.
- **3_Intall/**
  Various operating systems call some tools by different package names. Or, 
  come with a handful of different packages for different things.

  Some installation steps for different software might even be broken up 
  into several files, and will be numbered accordingly to permit modularity.
  - **apt.md**
  For a quick walk-through on installing on Debian-based platforms. Maybe
  even honorable mentions to tools I enjoy using along with the application.
  - **pacman.md**
  As an example of other package managers I might use, including rpm, or yum.
- **4_Usage/**
  The meat and potatoes of this project will go here. Basic usage and use-cases 
  will be documented here.
  - '01-Post_Install.config.*<brief description>*.md'
  - '01-Post_Install.*<brief description>*.md': Files starting with a 01 are 
    designated as post-installation procedures, or even a configuration.
  - '02-Usage.basic.*<brief description>*.md': i.e.,
    '02-Usage.basic.cloning_repo.md' Common usage will be found in 02s.
  - '03-Usage.advanced.*<brief description>*.md: Advanced usage here.
  - '04-Config.*<use case>*.*<description>*.md: This can be a specific 
    feature, or expansion on basic capabilities.
- **5_Notes/**
  This can be an interesting directory, as it will include License and 
  legal notes(If you're from the U.K., or any country that has specific 
  laws for encryption, or administration of certain qualities, **I want 
  to hear from you**.).
  - 'Legal.md': Referes to the license associated by the source code IP 
    owner, and references to any laws contributed, or discovered. *Please, 
    note that I am not a lawyer of my, or any country and any advice you 
    find here to be purely topical.* You are on your own my friend.
  - 'Warnings.md': Some tools are spicey, and you might want to know 
    some of these details if you plan to operate them. Otherwise, 
    this file will simply inform you of common-practices and 
    potential 'gotchas'.
- '6_Versions.md': A list of Long-Term-Supported versions, or any other 
  version I discover to be of interest and explanations of features 
  that are found for a version.
- **7_Help/**
  You will find links to various sources of help here, such as irc, FAQs, 
  Wikis, and even notable blogs.

#### Contact:
 - **Original Contributor**: [odoylexrules](mailto:mintopintohintodoo@gmailcom)
  [GitHub Profile](https://github.com/odoylexrules)

#### Contributing:
Please email me for my guidelines on contributions, and a summary of what 
to expect.

#### License:
This project is licensed under the [MIT License](https://en.wikipedia.org/wiki/MIT_License), 
and all that I ask of you, is an honorable mention as a contributor to 
the data found within this project.
