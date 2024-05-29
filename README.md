Head on over to the [wiki](https://github.com/amazingmarvin/in-marvin-help/wiki) to view/edit the documentation.

# What's this?

Marvin introduced tooltips in version 1.65.0, so that you can get help within the app that's relevant to where you are in the app.

The documentation in the wiki of this repo is shown in the app.

# How does it work?

A script converts the wiki into a JSON file which is then served to users when they open the app.

# What is the structure of the documentation?

Each page (except `Home.md`) corresponds to a section within Marvin. So `WeekView.md` contains help for the `WeekView` overlay (which is called the "Week Scheduler" within Marvin).

Each page contains three sections: FAQs, Tips, and Resources. Each FAQ, tip, and resource gets its own subsection. Additionally each section has a "See also" subsection, which allows for showing FAQs/tips/resources in multiple places within Marvin.
