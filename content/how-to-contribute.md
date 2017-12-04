---
title: "How to Contribute"
disableToc: true
---

### This is the barebones

{{<mermaid align="center">}}
graph TD;
    A(Decide to Contribute) -->|fork the repository| B[Make Desired Changes]
    B --> C{Is Change Good?}
    C -->|NO| D[Make it good]
    D --> C
    C -->|YES| E[Good! You're ready to share it with everybody]
    E -->|commit and push to your forked repository| F(Make a pull request)
{{< /mermaid >}}


{{%expand "I am a bit confused"%}}

> This walkthrough assumes that you have made a github account prior to doing this

1. Fork this entire repository
1. Make desired changes
	* Such as adding files to `content/`
	* Deleting content deemed unnecesary
	* Adding resources such as Questions/Notes/Links etc
1. Determine if the changes you've made is good
	* A good change is one which does not break the system
	* The first thing to ensure is that your repo is not _behind_ the master when pushing. Learn to be a commit ahead.
	* If that seems hard^, then atleast make sure there are no conficting changes
	* Ofcourse, we at CSITauthority __do not__ ignore bad commits but, bad commits will take longer to appear on the main website.
	* _Lastly_, don't sweat the details. If you feel its good, push it. Moderators won't let anything that shouldnt break, break.
1. Now, if the change your propose is good to go, please commit it one final time then push to your `master`
1. Then you need to make a pull request from your forked repository.
1. Once your pull request is submitted, moderators will make sure necessary changes are made. Your contributions are valuable to us.
1. Expect to see __YOUR__ content soon! You are now an official contributor. *Yes, our website automatically enlists you in the contributor list as long as you have configured your Git-bash properly*
1. Happy Contributing! and Welcome to the family.

>Still Confused? [We're just a click away](https://m.me/csitauthority)

{{% /expand%}}