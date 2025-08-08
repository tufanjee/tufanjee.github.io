# Mapping Death on Mount Everest
Analyzing over a century of deaths on Everest to understand who dies, when, where, and why

This analysis explores deaths on Mount Everest expeditions dating back to the 1920s. It was produced as part of Columbia University’s LEDE 2025 journalism course.

The data come from the [Himalayan Database](https://www.himalayandatabase.com/downloads.html) (version 2.74, Autumn-Winter 2024 update), a detailed record of mountaineering expeditions in the Nepal Himalaya. While the database has maintained active records since 1963, it includes historical data reaching back to the early 1900s.

The archives were originally compiled by [Elizabeth Hawley](https://americanalpineclub.org/news/2018/2/7/elizabeth-hawley-1923-2018), a longtime Kathmandu-based journalist who died in 2018. Hawley sourced information from books, alpine journals and correspondence with climbers. Today, [a nonprofit organization](https://www.himalayandatabase.com) manages the database, which is freely available to the public.

The dataset covers all expeditions from 1905 through the end of 2024 to Nepal’s major mountaineering peaks. This includes both the Nepal and China sides of border mountains such as Everest, Cho Oyu, Makalu and Kangchenjunga, along with a few smaller peaks.

The records include detailed information about climbers and expeditions—demographics, roles, logistics, routes, oxygen use, summit success, injuries, fatalities, and more. For this project, the focus is solely on fatalities on Mount Everest.

To work with the data, I [installed](https://www.himalayandatabase.com/systemreqs.html) Himalayan Database [version 2.74](https://www.himalayandatabase.com/downloads/Installing%20the%20Himalayan%20Database.html) on a Mac using [CrossOver](https://www.himalayandatabase.com/updates-xovr.html), a tool that runs Windows software on macOS without needing Windows itself. After setup, I downloaded data on all Everest expeditions between 1921 and Winter 2024. I filtered the dataset to focus on fatalities. That is the basis of this analysis.


Find the [code analysis](https://github.com/tufanjee/tufanjee.github.io/blob/main/everest-project/EVEREST_final.ipynb) and [working story](https://tufanjee.github.io/everest-project/).
