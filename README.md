## Notes on GitHub Pages Deployment

---

#### _Note:_ If you've already created a repository that is initialized with git and setup to track the remote, you may skip to step 3.

---

1. > ### Create remote repository:
   - Login to GitHub and navigate to your repositories page.
   - Click the green New button as shown:
     > > ![Create new repo button](/readme/create_new.png)
   - Give the repo the same name as your local repository.
   - Add an optional description.
   - Choose Public.
   - Examine the other options but leave as default for now.
   - Click `Create repository` at bottom to submit:
     > > ![New remote repo form](/readme/create_remote_form.png)
2. > ### Initialize your local project as GitHub repository:
   - Follow the instructions below:
     > > ![Steps to initalize local project as repo](/readme/init_local.png)
3. > ### Deploy to GitHub Pages:
   - Navigate on GitHub to the repository that you wish to deploy and click the `Settings` tab:
     > > ![Repo settings tab](/readme/settings_tab.png)
   - On the left side of the settings page, within the `Code and automation` section, click `Pages`:
     > > ![Pages option](/readme/pages_tab.png)
   - The `Source` option should default to `Deploy from a branch`. This is the option you want.
   - Click the dropdown button menu next to the `Save` button and select the `main` branch.
   - Click `Save`.
   - Navigate back to the repository's GitHub page.
   - Within the utility panel on the right side of the page, you should see a section titled `Environments`.
   - If your deployment was successful, you should see an environment named `github-pages` with a green `Active` label beside it:
     > > ![Environments section](/readme/environments.png)
   - Click on `github-pages` to navigate to the deployment history for this environment.
   - Click `View deployment` to navigate to your live, newly deployed webpage.
