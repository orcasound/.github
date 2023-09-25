<h1> Ahoy! This is Orcasound 👋 </h1>

<img alt="Our most-inspirational image of the orcas we're trying to help save: a single fin being watched by many riders from the decks of a Washington State ferry." src="https://user-images.githubusercontent.com/14044595/138359353-7ed3b581-613f-40f4-98ea-eacb91c5b04b.png">

<h2> Our Voyage Thus Far 🧭 </h2>

Since an [Orcasound Kickstarter in 2017](https://www.kickstarter.com/projects/sveirs/orcasound-listen-for-whales), we have been building open source software here on Github to help save the endangered orcas that seek salmon along the west coast of North America. Experiencing the live sounds of wild killer whales and acting to help conserve them is at the 💗 heart of our collective collaboration.

We began with the challenge of building an end-to-end audio live-streaming solution to make it easy to *listen for whales* through the [Orcasound network of underwater microphones](https://orcasound.net) ("hydrophones") in orca habitat. The [orcanode repo](https://github.com/orcasound/orcanode) generates the audio data streams and the [orcasite repo](https://github.com/orcasound/orcasite) provides a web app for playback that "just works" in any browser and scales efficiently. 

From the beginning, we have benefited greatly from the amazing all-volunteer **hackathon** community -- mainly through the organizational efforts of [DemocracyLab](https://www.democracylab.org/projects/81) and [Microsoft Garage](https://www.microsoft.com/en-us/garage/) -- both through in-person events in/near Seattle (Washington, USA) as well as many virtual events during the COVID pandemic. Both Microsoft's [AI for Earth](https://www.microsoft.com/en-us/ai/ai-for-earth) program and [Amazon Activate](https://aws.amazon.com/activate/) have supported our efforts with grants and/or cloud service credits. In 2020-22, we benefited from Google Summer of Code contributors in the [orcagsoc repo](https://github.com/orcasound/orcagsoc) and in 2023 Amazon sponsored our data storage/egress via [Orcasound in Amazon's Open Data Registry](https://registry.opendata.aws/orcasound/). 

<h2> On the Horizon (Updated Feb 2023) 🗺️ </h2>

See what's next on [Orcasound's public road map](https://trello.com/b/wBg0qhss/orcasound-roadmap). You can also suggest or vote up features! As of 2023, you can [join top-level discussions](https://github.com/orcasound/.github/discussions) and [help manage overarching projects](https://github.com/orcasound/.github/projects?query=is%3Aopen) in our oranizational repo.

Our long-term motivation is to make the [Orcasound web app](https://live.orcasound.net/) and our other open source projects into a more-and-more effective suite of free conservation tools. Along the way, we are trying to be as open, sharing, modular, and foresightful as possible in the hope that what we build for orcas will help bioacousticans and conservationists study and save other soniferous species around the planet.

<h2> Welcome Aboard! 🛳️ </h2>

Would you like to help save the orcas and contribute to open source software? 

The Orcasound organization on Github has a growing number of projects to which you can contribute. We welcome **coders** (front/back-end or full stack developers, bioacousticians, data scientists) and **designers** (UXers and other *creatives*), as well as project managers, mentors, and hardware engineers. The [Orcasound community](https://www.orcasound.net/hacker-hall-of-fame/) is super-friendly, daily communication mainly happens on Slack ([you're invited!](https://join.slack.com/t/orcasound/shared_invite/zt-1jr7te193-ObLYcTxx4s7SO7EA9kmcaw)), and there are weekly virtual meetings where you can introduce yourself and hear what others are doing. 

Here is the [Current Volunteer Handbook](https://drive.google.com/file/d/1GHuylE3qPm2UAyUA_f1yOtMgutBpXF6V/view?usp=sharing) where you can find more info about Orcasound's motivations, code of conduct, and high-priority projects.

See below for how you can join the Orcasound community and start contributing right away!

* <h3> Developers </h3>

	+ If you're interested in contributing code, we would welcome your input on any of our projects listed in the [Current Volunteer Handbook](https://drive.google.com/file/d/1GHuylE3qPm2UAyUA_f1yOtMgutBpXF6V/view?usp=sharing). If you are interested in making a contribution to any of the listed projects, or would like to make a bigger commitment to Orcasound long-term, go ahead and introduce yourself in Orcasound's U#dev-general Slack channel!

	+ Active Github repositories for our high-priority 2023 projects are [orcasite](https://github.com/orcasound/orcasite) for the live listening app and human detections, [orcanode](https://github.com/orcasound/orcanode) for the hydrophone network's audio streaming software (running on Raspberry Pis), [aifororcas-livesystem](https://github.com/orcasound/aifororcas-livesystem) for the OrcaHello AI system that auto-detects sounds, [orcamap-react](https://github.com/orcasound/orcamap-react) for mapping and analyzing SRKW location data, and [orca-shipnoise](https://github.com/orcasound/orca-shipnoise) for monitoring underwater noise pollution from large vessels that can interfere with orca communication. ***Please see each repo's CONTRIBUTING.md document for details!***

* <h3> Machine Learning </h3>

	+ If you're interested in machine learning you can [access Orcasound's open data](https://github.com/orcasound/orcadata/wiki) -- raw live/archived audio and labeled recordings -- and [peruse deployed project summaries at ai4orcas.net](https://ai4orcas.net/portfolio/) </p>
	+ How to download the training and testing data for ML models?
		+ Find what you want in the wiki and then [Access data via AWS CLI](https://github.com/orcasound/orcadata/wiki/Data-access-via-AWS-CLI)
		+ If you have not used AWS CLI before, or if you want to learn more about the available buckets, proceed [here](https://github.com/orcasound/orcadata/blob/master/access.md) to read a high-level summery of the AWS buckets.
		+ A subset of Orcasound’s open labeled data includes data archives that were prepared via the Pod.Cast system. The [Pod.Cast data archive wiki page](https://github.com/orcasound/orcadata/wiki/Pod.Cast-data-archive) provides instructions on how to download Pod.Cast data. This is a good place to start if you want to take a look at the labeled data.
		+ If you want a Python script to handle the data download, [download_datasets.py](https://github.com/orcasound/aifororcas-orcaml/blob/master/data_ml/tools/download_datasets.py) will get you started.
	+ How to find the code for the latest model? 
		+ The current deployed model is called [OrcaHello live inference system](https://ai4orcas.net/portfolio/orcahello/). Its github repo is [aifororcas-livesystem](https://github.com/orcasound/aifororcas-livesystem). 
		+ To those who are interested in finetuning the current ML model, the [ModelTraining](https://github.com/orcasound/aifororcas-livesystem/tree/main/ModelTraining) folder in the aifororcas repo is where you want to start.

 * <h3> Product and UX Team </h3>

	+ We have an incredible team made up of Product Managers, UX Researchers, UX Designers, Content Strategy folks, UX Writers, and more! We highly encourage a culture of professional learning and growth fueled by mentorship and learning by doing. If you're interested in volunteering as a Product and UX Team member:
		+ Introduce yourself in Orcasound's [#ux-general](https://orcasound.slack.com/archives/CE5KAK4D6) Slack channel 
		+ Access onboarding resources:
   			+ [Onboarding Resources in our Product wiki](https://github.com/orcasound/product/wiki)
      		+ The [Onboarding Website](https://sites.google.com/view/orcasound-onboarding-site/home) is a great place to start!

---
<sub>

🤫 Psst! You can create your own [organization README](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) and include emojis using this (cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/).

<details>
* <h3> Google Summer of Code Prospective Contributors </h3>

If you're a prospective Google Summer of Code contributor, don't miss [Orcasound's GSoC project page](https://www.orcasound.net/portfolio/google-summer-of-code-open-source-software-for-students-orcas/) and [open source advice from Orcasound's past GSoC participants](https://github.com/orcasound/orcagsoc/blob/master/OPEN-SOURCE-best-practice+tips.md)!
</details>

</sub>
