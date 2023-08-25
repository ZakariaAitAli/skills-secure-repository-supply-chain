<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Secure your repository's supply chain

_Secure your supply chain, understand dependencies in your environment, know about vulnerabilities in those dependencies and patch them._

</header>

## Step 3: Enable and trigger Dependabot security updates

_Nice work enabling, viewing, and creating Dependabot alerts :sparkles:_

Enabling Dependabot alerts on our repository was a great step toward improving our code security, but we still had to manually select an alert and then manually select the option to create the pull request. It would be nice to further improve the automation and maintenance of our dependencies! Well, with Dependabot security updates, we can do just that.

**What are Dependabot security updates?**: When enabled, Dependabot will detect and fix vulnerable dependencies for you by opening pull requests automatically to resolve Dependabot alerts when they arise.

We manually created the pull request for the `Prototype Pollution in minimist` alert, but let's now enable Dependabot security updates to automate this process with the next alert!

### :keyboard: Activity: Enable and trigger Dependabot security updates

1. Navigate to the `Settings` tab, select `Code security and analysis`, and enable the `Dependabot security updates`.
1. Navigate to the `Pull requests` repository tab and select the newly created pull request titled **Bump axios from 0.21.1 to 0.21.2 in /code/src/AttendeeSite**.
   - You may need to wait 30-60 seconds.
1. Click the `Merge pull request` button.
1. Click `Confirm merge`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
