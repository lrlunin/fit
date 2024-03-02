# FIT

A barebone File gIT system for syncing files across devices utilizing Git.

Currently, this plugin have two major function (Pulling from and Pushing to Github). The end goal of this plugin is to give user one single button to sync their vault to streamline the user experience.

This plugin is designed to be as simple as possible, and include only the push and pull function of git. It is written with Octokit-js with the goal of supporting devices universally. There are other community plugins with more advanced git features, e.g. [Git](https://github.com/denolehov/obsidian-git).

**Note:** This plugin is still in alpha, please backup your vault before using this plugin.

# How to use
1. Create a repo on github
2. Create a personal access token (refers to [Github: creating a personal access token](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token))
3. Enters the created token along with other relevant github information on the Fit settings tab.

# Acknowledgements
This plugin is built using Obsidian Sample Plugin as a template.
This plugin uses [Octokit](https://github.com/octokit/octokit.js) to interface with github rest api across devices.

<!--- 
## Releasing new releases

- Update your `manifest.json` with your new version number, such as `1.0.1`, and the minimum Obsidian version required for your latest release.
- Update your `versions.json` file with `"new-plugin-version": "minimum-obsidian-version"` so older versions of Obsidian can download an older version of your plugin that's compatible.
- Create new GitHub release using your new version number as the "Tag version". Use the exact version number, don't include a prefix `v`. See here for an example: https://github.com/obsidianmd/obsidian-sample-plugin/releases
- Upload the files `manifest.json`, `main.js`, `styles.css` as binary attachments. Note: The manifest.json file must be in two places, first the root path of your repository and also in the release.
- Publish the release.

> You can simplify the version bump process by running `npm version patch`, `npm version minor` or `npm version major` after updating `minAppVersion` manually in `manifest.json`.
> The command will bump version in `manifest.json` and `package.json`, and add the entry for the new version to `versions.json`

## Adding your plugin to the community plugin list

- Check https://github.com/obsidianmd/obsidian-releases/blob/master/plugin-review.md
- Publish an initial version.
- Make sure you have a `README.md` file in the root of your repo.
- Make a pull request at https://github.com/obsidianmd/obsidian-releases to add your plugin.
  
## Manually installing the plugin

- Copy over `main.js`, `styles.css`, `manifest.json` to your vault `VaultFolder/.obsidian/plugins/your-plugin-id/`.
--->
