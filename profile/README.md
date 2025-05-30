<h1> Ahoy! This is Orcasound 👋 </h1>

<img width="400" alt="Our most-inspirational image of the orcas we're trying to help save: a single fin being watched by many riders from the decks of a Washington State ferry." src="https://user-images.githubusercontent.com/14044595/138359353-7ed3b581-613f-40f4-98ea-eacb91c5b04b.png">

<h2> Our Voyage Thus Far 🧭 </h2>

Since an [Orcasound Kickstarter in 2017](https://www.kickstarter.com/projects/sveirs/orcasound-listen-for-whales), we have been building open source software here on Github to help save the endangered orcas that seek salmon along the west coast of North America. Experiencing the live sounds of wild killer whales and acting to help conserve them is at the 💗 heart of our collective collaboration.

We began with the challenge of building an end-to-end audio live-streaming solution to make it easy to *listen for whales* through the [Orcasound network of underwater microphones](https://orcasound.net) ("hydrophones") in orca habitat. The [orcanode repo](https://github.com/orcasound/orcanode) generates the audio data streams and the [orcasite repo](https://github.com/orcasound/orcasite) provides a web app for playback that "just works" in any browser and scales efficiently. 

From the beginning, we have benefited greatly from the amazing all-volunteer **hackathon** community -- mainly through the organizational efforts of [DemocracyLab](https://www.democracylab.org/projects/81) and [Microsoft Garage](https://www.microsoft.com/en-us/garage/) -- both through in-person events in/near Seattle (Washington, USA) as well as many virtual events during the COVID pandemic. Both Microsoft's [AI for Earth](https://www.microsoft.com/en-us/ai/ai-for-earth) program and [Amazon Activate](https://aws.amazon.com/activate/) have supported our efforts with grants and/or cloud service credits. In 2020-22, we benefited from Google Summer of Code contributors in the [orcagsoc repo](https://github.com/orcasound/orcagsoc) and in 2023 Amazon sponsored our data storage/egress via [Orcasound in Amazon's Open Data Registry](https://registry.opendata.aws/orcasound/). 

Our long-term motivation is to make the [Orcasound web app](https://live.orcasound.net/) and our other open source projects into a more-and-more effective suite of free bioacoustic and conservation tools. Along the way, we are trying to be as open, sharing, modular, and foresightful as possible in the hope that what we build for orcas will help bioacousticans and conservationists study and save other soniferous species around the planet.

<h2> On the radar (2025 priorities)</h2>

Based on our inaugural summit held in January, 2025, we are prioritizing these 7 projects this year:

1. Improve community infrastructure and the onboarding experience (including cooperative governance and open collective financial management) 
2. Transition from intermittent (>1yr) versioning of software to a faster user-centered feature-based design/development cycle (e.g. 1-10 day developer sprints) 
3. Add user accounts and a moderator role + UI to the live-listening web app
4. Update the orcanode streaming code, swarm management, and dev/staging/production environments (integrating with the network admin dashboard))
5. Revise the `utils` package to ensure access to archived and live data is easy and well-documented
6. Retrain the OrcaHello model (SRKW call binary classifier) and set stage for training and deploying models for SRKW clicks and Bigg's killer whale calls, as well as gray and humpback whale vocalizations
7. Continue building new conservation applications, like shipnoise.net, that leverage the hydrophone network and improve tools like the ambient-sound-analysis repo

<h2> On the horizon 🗺️ </h2>

See where we may head next on [Orcasound's public road map](https://trello.com/b/wBg0qhss/orcasound-roadmap). You can also suggest or vote up features!

An overarching goal we anticipate for 2026 is build conservation calls-to-action into the live-listening web app for some user personas.

<h1> Welcome Aboard! 🛳️ </h1>

Would you like to help save the orcas and contribute to free open source bioacoustic and conservation software? 

The Orcasound organization on Github has a growing number of projects to which you can contribute. We welcome **coders** (front/back-end or full stack developers, bioacousticians, data scientists) and **User Experience Professionals**, as well as project managers, tech mentors, and hardware engineers. The [Orcasound community](https://www.orcasound.net/hacker-hall-of-fame/) is super-friendly, daily communication mainly happens on Zulip ([you're invited!](https://orcasound.zulipchat.com/join/42uml7y5yr7n7pbc7k2icbcb/)), and there are weekly virtual meetings where you can introduce yourself and hear what others are doing. If you live in/near Seattle, we also gather in-person for a social hour or annual summit about once per quarter.

Here is the [Current Volunteer Handbook](https://drive.google.com/file/d/1GHuylE3qPm2UAyUA_f1yOtMgutBpXF6V/view?usp=sharing)(v.2022) where you can find more info about Orcasound's motivations, code of conduct, and high-priority projects.

See below for how you can join the Orcasound community and start contributing right away!

* <h3> Developers </h3>

	+ If you're interested in contributing code, we would welcome your help on any of our projects listed above. If you are interested in making a contribution, go ahead and introduce yourself in Orcasound's [#dev-general channel](https://orcasound.zulipchat.com/#narrow/channel/437054-dev-general)!

	+ Active Github repositories for our high-priority projects are [orcasite](https://github.com/orcasound/orcasite) for the live listening app and human detections, [orcanode](https://github.com/orcasound/orcanode) for the hydrophone network's audio streaming software (running on Raspberry Pis), and [aifororcas-livesystem](https://github.com/orcasound/aifororcas-livesystem) for the OrcaHello AI system. ***Please see each repo's CONTRIBUTING.md document for details!***

 * <h3> Product and UX Team </h3>

	+ We have an incredible team made up of Product Managers, UX Researchers, UX Designers, Content Strategy folks, UX Writers, and more! We highly encourage a culture of professional learning and growth fueled by mentorship and learning by doing. If you're interested in volunteering as a Product and UX Team member:
		+ Introduce yourself in Orcasound's [#ux-team channel](https://orcasound.zulipchat.com/#narrow/channel/437042-ux-team) 
		+ Access onboarding resources:
   			+ [Onboarding Resources in our Product wiki](https://github.com/orcasound/product/wiki)
      		+ The [Onboarding Website](https://sites.google.com/view/orcasound-onboarding-site/home) is a great place to start!

  * <h3> Data Scientists </h3>

	+ If you're interested in data visualization or machine learning you can [access Orcasound's open data](https://github.com/orcasound/orcadata/wiki) There you'll find raw and labeled audio data, as well as other types of data that may help contextualize what we hear -- like animal locations from the Acartia data cooperative.</p>
	+ How to find the code for the latest machine learning model?
  		+ First, [peruse deployed project summaries at ai4orcas.net](https://ai4orcas.net/portfolio/)
		+ The current deployed model is the [OrcaHello live inference system](https://ai4orcas.net/portfolio/orcahello/). Its github repo is [aifororcas-livesystem](https://github.com/orcasound/aifororcas-livesystem). 
		+ To those who are interested in finetuning the current ML model, the [ModelTraining](https://github.com/orcasound/aifororcas-livesystem/tree/main/ModelTraining) folder in the aifororcas repo is where you want to start.

---

🤫 Psst! You can create your own [organization README](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) and include emojis using this [cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/). 
	
And if you're an open source project like us, you can [chat on Zulip for free!](https://zulip.com/for/open-source/)

