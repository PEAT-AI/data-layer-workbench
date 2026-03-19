# Data Layer Workbench

A tool for mapping Plantix's data strategy from **personas** and **use cases** down to **data layers** and **tasks**.

## What it does

Navigate four layers of context, one click at a time:

```
PERSONAS → USE CASES → DATA LAYERS → TASKS
  (who)      (what)      (what data)   (how to get it)
```

- **Personas**: Farmer, Crop Protection companies, Seed companies, Fertilizer companies, Commodity traders
- **Use Cases**: User stories per persona — what each role needs from the data
- **Data Layers**: The foundational datasets that power the use cases (Disease Incidences, Acreage, Growth Stage, etc.)
- **Tasks**: Concrete work items per data layer, with assignees and "Next" flags for sprint planning

## How to view

Open the live site: **https://peat-ai.github.io/data-layer-workbench/**

The site is **read-only by default**. You can browse all personas, use cases, data layers, and tasks.

## How to give feedback

1. Click the **"Give Feedback"** button in the top right
2. This opens a GitHub Issue with a template
3. Describe what you want changed (new user story, wrong tag, missing data layer, etc.)
4. The change will be reviewed and published

## Key features

- **Click-through navigation** with breadcrumbs to drill down and back up
- **Reverse links**: Every data layer shows which personas and use cases depend on it
- **Sidebar**: All data layers ranked by number of use cases, always visible
- **Next Up view**: See all tasks marked as "Next" across all layers — the sprint planning view
- **Print Next Up**: Generate a clean PDF of upcoming tasks to share with the team
- **Tags on user stories**: Mark where a story came from (Sales, UX, Internal, or custom)
- **Assignees on tasks**: Track who's responsible for each work item
- **Export / Import**: JSON backup and restore

## For editors

Add `?mode=edit` to the URL to unlock editing. In edit mode you can:

- Edit user story text and tags
- Add/remove data layer mappings on stories
- Add new user stories and data layers
- Add, edit, and delete tasks
- Mark tasks as "Next" and assign team members
- Export your changes as JSON
