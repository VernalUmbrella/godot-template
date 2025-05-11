# Godot Template

I've run into a few hiccups when directly tracking a Godot source folder in Git.
Thus, I've decided to set up this template to make the process a bit smoother.

## Structure

| Subdirectory | Description |
| --- | --- |
| assets | All asset files not contained within the source folder. |
| build | Exported projects. Not tracked by Git. |
| src | Godot root folder. |

## Usage

> [!NOTE]
> The instructions below apply as of Godot 4.4.

1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository. Rename it in accordance with your project.
2. Open [Godot Engine](https://godotengine.org). From the Project Manager screen, click **Create**.
3. Ensure the "Create Folder" option is **disabled**.
4. Name your project as you like.
5. Select the `src` directory as the **Project Path**.
6. Ensure **Git** is selected under "Version Control Metadata".
7. Create the project!
8. Feel free to delete the `README.md` that was in the `src` directory.
