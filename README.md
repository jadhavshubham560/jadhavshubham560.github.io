# Shubham Jadhav · Engineering portfolio

[View the portfolio](https://jadhavshubham560.github.io/) · [LinkedIn](https://www.linkedin.com/in/shubham~jadhav/)

Mechanical design, material selection, robotics and embedded systems projects. Project descriptions start from my existing LinkedIn profile. Videos and engineering files will be added as the project material is prepared.

## Project folders

| Project | Folder |
| --- | --- |
| Two-finger gripper for a FANUC robot | `projects/fanuc-gripper/` |
| Structural component material optimization | `projects/material-optimization/` |
| Sensor-based obstacle avoidance | `projects/obstacle-avoidance/` |
| Collective perception in a robot swarm | `projects/robot-swarm/` |
| Fault-tolerant jump counter on T-Watch | `projects/twatch-jump-counter/` |

## Add files later

1. Open the relevant project folder on GitHub.
2. Select **Add file → Upload files**, choose your files and commit the upload.
3. Open `projects.json` in the repository root and click the pencil to edit it.
4. Find the project by its `id`, fill in its `images`, `video` or `files` entries, and commit the change. The website updates after GitHub Pages finishes deploying.

Example for the gripper project (use the actual filenames you upload):

```json
"images": [
  {
    "src": "projects/fanuc-gripper/assembly.png",
    "alt": "Assembly view of the two-finger gripper",
    "caption": "SolidWorks assembly"
  }
],
"video": "https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID",
"files": [
  { "label": "Engineering drawings (PDF)", "url": "projects/fanuc-gripper/drawings.pdf" },
  { "label": "Project presentation (PDF)", "url": "projects/fanuc-gripper/presentation.pdf" },
  { "label": "CAD assembly (ZIP)", "url": "projects/fanuc-gripper/cad.zip" }
]
```

Leave arrays empty and `video` blank until material exists. Links only appear on the website when you add them. An MP4 path can be used in `video` for small videos; a YouTube embed or a link to an externally hosted video keeps the repository smaller.

For SolidWorks assemblies, use Pack and Go to collect the referenced parts before making a ZIP. Include PDF drawings and a STEP export when useful. For ANSYS work, show the geometry, assumptions, loads, constraints, mesh and results in the report; link a project archive separately if you want to share it. PPTX, PDF, CAD, STEP and ZIP files can all be linked through `files`.

Keep large videos and simulation archives in external storage and use their share links. Upload only material you can share publicly. This repository and its website are public. No reuse licence has been granted for the project material.

## Update project text

Edit the corresponding entry in `projects.json`. Each project has a title, category, period, tools, summary, project work and engineering focus. Add a new entry with a unique `id` for another project, then create its matching folder. Dates marked ongoing reflect the source descriptions at the initial setup; update them as projects finish.

## Website

`index.html` contains the responsive layout and project-page rendering. `projects.json` contains the project content and file links. GitHub Pages serves the `main` branch from the repository root. No build tools or subscription are needed to edit this static site.
