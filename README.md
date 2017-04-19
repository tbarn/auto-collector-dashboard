# Keen IO Auto-Collector Dashboard 📉📊📈

A pre-made dashboard for Keen IO projects using the [Auto-Collector](https://keen.io/docs/streams/web-auto-collection/?source=glitch).

This dashboard is built using the existing event data models, so you don't have to!

You can remix the project to make it your own in Glitch with your own Keen IO data here:

[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/remix/auto-collector-dashboard)

## Getting Started 

To get started, you need:
- A [Keen IO account](https://keen.io/signup?source=glitch)
- A Keen IO project with data streaming to it from the [Auto-Collector](https://keen.io/docs/streams/web-auto-collection/?source=glitch)

Once you have these two things, you can remix the code in [Glitch](https://glitch.com/edit/#!/remix/auto-collector-dashboard) or locally by pulling this repo.

Next, you need to replace the example `projectId` and `readKey` in the settings.js file with those for your project. 

You can also choose what the relative timeframe your dashboard queries. We have set it at `this_4_weeks` in settings.js to start. 

## Running the Application

If you are **running the project within Glitch**, click the "Show Live" button.

If you are **running the project locally** and have the files downloaded or git cloned, open the index.html file in a browser.

Your dashboard should now render in your browser! 🎉📊✨

## Going Forward 

The cool thing about the Auto-Collector is that it is just a start.

You can add your own custom data visualizations and analysis for your Keen IO event streams alongside the event data models from the Auto-Collector. 

If you want to track custom events beyond pageviews, clicks, and form submissions, you can easily access our core Javascript tracking library (which this SDK uses under the hood). See more [here](https://keen.io/docs/streams/web-auto-collection/?source=glitch).

The data collected by the Auto-Collector nicely compliments other user behavior data. For example: You could have a graph of `signup` or `login` events that are custom to your application. Other example actions you could track with Keen IO are: `swipes`, `upgrades`, `purchases`, `powerups`, `errors`, `shares`. 

If you want to think more about event data, check out this [blog post](https://blog.keen.io/analytics-for-hackers-how-to-think-about-event-data-cabeefe1f3d9?source=glitch).

## Contributions Welcome

This is an open source project, and we love involvement from the community! If you are interested in getting involved, please see the [CONTRIBUTING.md](CONTRIBUTING) file.

## Need Help?

Send us an email at [team@keen.io](mailto:team@keen.io) or join our [Community Slack](http://slack.keen.io/) to share bugs, issues, or suggestions!
