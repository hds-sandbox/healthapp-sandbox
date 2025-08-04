# Health data sandbox 

This folder generates the self-learning material for the app on our website. 

- The markdowns (*.qmd) files in develop and access are stand-alone.
- The practical lessons (*ipynb) are pulled from the Notebooks folder in the main branch.

To keep the website up to date, stage your changes with git add, commit, and push them to the remote repository. Once pushed, the `.github/workflows/publish.yml` workflow will automatically build and deploy the updated site to the `gh-pages` branch. Just make sure to compile the notebooks beforehand to display the solutions on the website. No further action is needed from you.

You can review the GitHub workflows to see how this automation works.