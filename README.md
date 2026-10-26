# Instruction-Manual

GitHub is a cloud platform where developers store, track, and manage code. **GitHub Pages** is a free feature built into GitHub that takes an `index.html` file and turns it into a live, public website accessible via a URL (like `yourusername.github.io/my-mtg-app`).

Here is the step-by-step process to put your MTG glossary website live using GitHub Pages—no coding or terminal commands required.

1. **Create a Free GitHub Account:**
   - Go to [github.com](https://github.com/) and click **Sign up**.
   - Follow the prompts to enter your email, create a password, and choose a username.
   - Verify your email address through the link sent to your inbox.


2. **Create a New Repository:** A 'repository' is simply GitHub's term for a project folder..
   - Log into GitHub and click the **`+`** icon in the top-right corner, then select **New repository**.
   - **Repository name:** Enter a short name for your project (e.g., `mtg-glossary`).
   - **Visibility:** Make sure **Public** is selected (GitHub Pages requires free repositories to be public).
   - Check the box that says **Add a README file**.
   - Click the green **Create repository** button at the bottom.


3. **Upload Your HTML File:**
   - Inside your new repository page, click the **Add file** dropdown button near the top right and select **Upload files**.
   - Drag and drop your HTML file into the upload area.
   - **Important:** The main HTML file MUST be renamed to **`index.html`** if it isn't already. GitHub Pages specifically looks for `index.html` to serve as your homepage.
   - Scroll down and click the green **Commit changes** button.


4. **Enable GitHub Pages:**
   - Near the top of your repository page, click the **Settings** tab (gear icon).
   - On the left sidebar, click **Pages** (under the "Code and automation" section).
   - Under **Build and deployment** $\rightarrow$ **Branch**:
      * Change the dropdown from `None` to **`main`**.
      * Leave the folder dropdown set to `/(root)`.
   - Click **Save**.


5. **Access Your Live Website:**
   - Wait 1 to 3 minutes while GitHub builds your site.
   - Refresh the **Pages** settings page. You will see a banner at the top displaying your live URL (e.g., `[https://yourusername.github.io/mtg-glossary/](https://yourusername.github.io/mtg-glossary/)`).
   - Click the link to open your live MTG Glossary website.


### Key Tips for updating your site later:

* **To update your app:** Simply click on `index.html` in your repository, click the pencil icon (Edit), paste your new code, and click **Commit changes**. GitHub Pages will automatically re-deploy your site within a minute.
* **Storage:** Any data you save using the app's update button will save in your browser's local storage automatically.
