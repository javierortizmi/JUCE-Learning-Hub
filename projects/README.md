# Projects

This folder hosts more complete and polished JUCE applications and audio plugins.

These projects demonstrate real-world use cases and best practices, and serve as reference implementations.

---

## Projects Included

| Project Name | Description               | Type       | Difficulty |
| ------------ | ------------------------- | ---------- | ---------- |

---

## How to Build

Each project includes:

- A `.jucer` file for use with the Projucer.
- A `CMakeLists.txt` for CMake-based builds.

Ensure JUCE submodule is initialized:

```bash
git submodule update --init --recursive
```

Build instructions:

- Open the `.jucer` file in the Projucer, save, and export to your preferred IDE.
- Or build with CMake from the command line or your IDE.

---

## Notes

- Some projects may require additional dependencies; check each project's README for details.
- Contributions and enhancements welcome!
