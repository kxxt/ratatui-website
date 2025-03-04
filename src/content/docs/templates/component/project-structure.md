---
title: Project Structure
---

The rust files in the `component` project are organized as follows:

```bash
$ tree
.
├── build.rs
└── src
   ├── action.rs
   ├── components
   │  ├── app.rs
   │  └── mod.rs
   ├── config.rs
   ├── main.rs
   ├── runner.rs
   ├── tui.rs
   └── utils.rs
```

Once you have setup the project, you shouldn't need to change the contents of anything outside of
the `components` folder.

Let's discuss the contents of the files in the `src` folder first, how these contents of these files
interact with each other and why they do what they are doing.
