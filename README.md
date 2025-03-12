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
> This is the **4.4** branch of the template, with a project preconfigured.

1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository. Rename it in accordance with your project.
2. Open [Godot Engine](https://godotengine.org). From the Project Manager screen, click **Import**.
3. Select the `src` directory as the **Project Path**. Ensure **Edit Now** is unchecked.
4. Rename the project as you like.
5. Open the project and start editing!
