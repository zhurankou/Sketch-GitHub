# Sketch-GitHub

With version 43 Sketch introduced a completely new approach to its file structure. Eventually, .sketch file became compatible with .zip format, which technically allowed it to be extracted into a folder.

## What to do with that?

Extracted Sketch file contains:
* .png files in /images and /previews, which are pretty much screenshots of its artboards;
* .JSON files in /pages and its root, which is basically the Sketch document’s data itself.

The .JSON format potentialy allows treating Sketch files as code, making it possible for designers to adapt all the benefits of developers’ workflow, such as sharing, collaborating, updating and reusing design files, as well as maintaining it’s version control with git on GitHub.

Therefore, it finally allows teams of developers and designers to organize their work around the same repo, making it more efficient and simpler to maintain the code and update design systems.

Besides that, now designers can work together on open source projects, using design files from initial commits as a base, forking them and building upon them. Such projects could benefit the whole design community, allowing to create, reuse and evolve basic design patterns and techniques.

Read more about manual version control for Sketch files with GitHub described in [my article](https://medium.com/@zhurankov/workflows-manual-version-control-for-sketch-files-with-github-df8e04f1571c)
on Medium. 
