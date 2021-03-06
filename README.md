# Smart meter file format examples Australia
In a number of states in Australia, individuals, whose homes are equipped with smart meters, can download a copy of their historical electricity consumption data.

This data is typically provided by either the electricity distributor and/or the electricity retailer, via the web.

This data is very useful. For example as I've previously written about, [smart meter data is most helpful if you're considering buying solar panels](http://what.agreenidea.org/post/96779193636/9-tips-on-going-solar-australia).

## The problem
The problem is there is no common format in which the electricity companies supply this data to their customers. In Victoria, where the residential smart meter rollout is complete, there are [six different file formats in use](http://switchon.vic.gov.au/get-the-best-deal/compare-offers-with-my-power-planner/how-to-download-an-electricity-usage-file-from-your-provider).  Nationally, once all states have smart meters, its conceivable that this data is published in some 20-odd different formats.

This lack of standardisation makes it harder for developers than it ought to be, to build apps on top of this data. Apps like the Victoria Government's [My Power Planner](https://mpp.switchon.vic.gov.au/) or [Empower.me](http://empowerme.org.au/visualise.html).

## The solution
One solution is to solve this problem at the source, much like [the Green Button Initiative in the United States](http://what.agreenidea.org/post/28757165630/smartmetersopendata).

A simpler solution is to work with what we've got and build a tool which can take smart meter data in any of the myriad formats and convert it into one common format.  This repo is a minute step towards this goal. 

## The goal of this repo
The goal of this repo is to collate as many examples as possible of the different file formats used by Australian electricity utilities and distributors for supplying customers with their smart meter data.  Nothing more, nothing less.

My hope is that if successful in this goal, this project will be a good stepping stone towards an open source project that provides tools to standardises these myriad file formats into a single developer-friendly one.

## How you can help 
If you live in Australia, have a smart meter and your utility or distributor can supply you with an electronic copy of the data, please help by uploading an example of the file.  More detail on how to do that in the `examples` folder.

## Not on GitHub?
If you're not on GitHub and/or you're not familiar with Git.  Don't worry. You can email me the file directly, and I'll upload it here for you.  Email address is interwebscharlie at yahoo dot com dot au.  Before you email me the file though, be sure to follow the instructions about the file name and privacy [here](https://github.com/charliedotau/Smart-Meter-File-Format-Examples-Aus/blob/master/examples/README.md).

