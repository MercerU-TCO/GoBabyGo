# Go Baby Go Documentation

This repo contains the documentation used to build and customize the small electric cars used by the Go Baby Go project.

* The published content is found at [Go Baby Go](https://merceru-tco.github.io/GoBabyGo/).<br>
* The source documents that make up the published content is found in the [https://github.com/MercerU-TCO/GoBabyGo](https://github.com/MercerU-TCO/GoBabyGo) repo.<br>
* The repo where changes are tested before they are published is the [https://github.com/rbwatson/GoBabyGo](https://github.com/rbwatson/GoBabyGo) repo.

See the notes below on how to contribute to this documentatin project.

# How to contribute to the Go Baby Go! documentation

Thank you for your interest in the project! We look forward to your contributions!

## Getting ready to contribute

1. Fork the [https://github.com/rbwatson/GoBabyGo](https://github.com/rbwatson/GoBabyGo) repo into your GitHub account.
	* Check to make sure that you're forking from the correct account:<br>
![GitHub account to fork](/contribute/images/contribute_rbwatson.png)
	* Then click the **Fork** button to fork the repo into your account<br>
![GitHub fork button](/contribute/images/contribute_fork.png)
1. In your forked repo, set the settings to publish the **/docs** folder of the **master** branch. 
	* Open the **Settings** tab in the repo you just forked to your account.<br>
![GitHub settings tab](/contribute/images/contribute_settings.png)
	* In the **Settings** tab, select the **Options** view.<br>
![GitHub options view](/contribute/images/contribute_options.png)
	* Scroll down the page to find the **GitHub Pages** box.
		1. (Arrow 1) Select the **master branch /docs folder** and **Save**
		2. (Arrow 2) Make sure you see that your site is published (this can take a minute or two.
		3. (Arrow 3) Confirm that the link refers to your account.
	* ![GitHub GitHub Pages box](/contribute/images/contribute_pages.png)
    * When you see the green bar, open the the documentation in the link (Arrow 3 above).
    * If you DO NOT see a green bar and the documentation link or the link address in the settings does not refer to your account, **STOP**  and fix that before you continue.
1. If you see your copy of the documentation in gethub.io, then you're ready to continue.

## Documentation and development tools

Your GitHub experience can be a little easier if you download these tools.

* **GitHub Desktop**<br>
This lets you work on your Mac or PC with or without a connection to the GitHub web site. To use the GitHub Desktop:
	1. Download the program from [https://desktop.github.com/](https://desktop.github.com/) and install it on your computer.
	2. **Clone** your Go Baby Go project by clicking the **+** icon in the upper left corner, selecting the **Clone** tab, and then selecting the GoBabyGo project.
	3. This will download the project to your computer from the cloud server and let you create an edit the files on your PC (or Mac).
* **Markdown Pad** (PC only)<br>
Markdown Pad is program to edit the Markdown files used to produce the documentation. It lets you edit the source text and displays [almost] how the document will look when it is rendered. Note that the actual rendering of the content might not look like it does in the Markdown Pad editor. To use Markdown Pad:
	1. Download the program from [https://markdownpad.com](https://markdownpad.com).
	2. Install it on your PC.

## Making a contribution

After you create or modify the files in your forked repo, to contribute those changes to the project:

1. **Make sure that you can see those changes in your version of the github.io documentation.** <br>
This is very important. If you can't see your changes, something went wrong and **you must fix it before you continue!**
    1. The first place to look is to make sure you do not have any bad metadata in a file.
    1. The next place to look is to make sure you didn't link an image wrong.
    2. If you still don't see your changes, you'll need to ask for help.
1. If you see your changes in your version of the github.io documentation (i.e. at the link in your repo's **Settings** tab, in the **GitHub Pages** box in the **Options** view), you can continue.
1. Send you pull request to the [https://github.com/rbwatson/GoBabyGo](https://github.com/rbwatson/GoBabyGo) repo.
	1. Create a **New pull request**<br>
![GitHub GitHub Pages box](/contribute/images/contribute_pullrequest.png)
	2. In the **Comparing changes** page, check the mergeability (Arrow 1). If it's **able to merge**, continue. If not, you can still continue, but your pull request might be rejected. Click **Create pull request** (Arrow 2) to finish.
![GitHub GitHub Pages box](/contribute/images/contribute_create.png)

1. If your contribution looks good, it will be merged into the staging repo and eventually make its way to the published project. 
1. If there's a problem, you might get some questions about the pull request or it might be declined with a comment to help you fix it. After you fix whatever wasn't working, repeat these steps to resubmit your pull request.

# Repo organization

The repo is organized into

* Documentation development information is found in the staging repo wiki
* Published documentation source files are found in the **/docs** folder
* Project files that are used to create the docs but are NOT published are found in tother folders

## Documentation development information

Files and information about writing the documentation are stored in several places:

- Notes on writing and publishing the documentation are found in the repo's wiki
- Issues, bugs, and other transient notes are stored as issues.

## Published Documentation

The source files that produce the published documentation are stored as a Jekyll project under the **/docs** folder. These files are automatically built into HTML documentation files. The master copy of the published documentation is [https://merceru-tco.github.io/GoBabyGo](https://merceru-tco.github.io/GoBabyGo/). You should be able to see your version of the docs in the URL shown in the settings page. It should look something like: https://_yourAccount_.github.io/GoBabyGo (where _yourAccount_ is your GitHub account).

## Project Files

Files used by to help create elements of the documention but are not intended to be published with the end-user documentation are stored in root folders (so long as the folder is not named **/docs**)

# Go Baby Go Information

* Information about the Go Baby Go project's beginnings: "[One Man Helped Disabled Kids With Power Wheels](https://www.youtube.com/watch?v=qcZtW18WgtE)"
* Information about Go Baby Go at Mercer: 
	- [December 2016 on Facebook](https://www.facebook.com/mercertc/posts/1166188856828602)
	- [December 22, 2016 in __The Telegraph__](http://www.macon.com/news/local/education/article122402574.html)
