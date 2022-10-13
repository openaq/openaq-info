(Always a Work In Progress)

Frequently Asked Questions
---
### A. The Organization and Community

**0. [What is OpenAQ?](#whatis)**

**1. [Why does OpenAQ exist?](#why)**

**2. [Who started OpenAQ and what motivated them to do it?](#who)**

**3. [Who is part of OpenAQ and what have they built already?](#community)**

**4. [What type of organization is OpenAQ and where is it located?](#whatorg)**

**5. [How is OpenAQ funded?](#howfund)**

**6. [Why does OpenAQ require funding, anyway?](#whyfund)**

**7. [Can I donate funds?](#donate)**

**8. [Do you have a Community Code of Conduct?](#coc)**

---

### B. Open Data Access

**9. [What kinds of data are stored to the OpenAQ Platform? Where is Air Quality Index data?](#datakinds)**

**10. [What are low-cost sensors and why have they been added to the platform?](#lowcostsensors)**

**11. [How are data attributed to their sources? How can I find out the sources of the aggregated data?](#dataattribution)**

**12. [How are the data licensed?](#license)**

**13. [How long are data stored?](#storage)**

**14. [What guarantees of the data accuracy are made of the data?](#accuracy)** 

**15. [What are the ways I can access data?](#access)**

**16. [Why can I only access data for the last two years? Where's the rest of the data?](#90days)**

**17. [How do I cite the OpenAQ platform in peer-reviewed literature?](#citing)**

---

### C. Open Software Platform

**18. [Why is the OpenAQ Platform open-source?](#whyopensource)**

**19. [Where can I find the open-source software?](#whereopensource)**

**20. [What is the license of the software?](#licenseopensource)**
 
---

### D. Contributing to the OpenAQ Platform & Community

#### Ongoing Projects

**21. [What are some ongoing open-source projects involving OpenAQ?](#ongoingprojects)**


#### Contributing Data Sources

**22. [How can I help contribute new data sources? What information is needed for a new data source?](#help)**

**23. [I suggested a new data source, but I haven't seen it added yet. What gives?](#suggestions)**

Contributing Development Skills for Enhancing the Platform

**24. [What skills are needed to contribute to the code-base?](#skills)** 

**25. [Where can I find existing issues I can help out with?](#helpissues)**
 

#### Using the Data

**26. [What community tools exist that I can use to explore the data?](#tools)**

**27. [What are cool ways that I can use the data?](#usedata)**

**28. [Why does the same location occur multiple times?](#multiples)**

**29. [I think I may need an access key to access data stored in S3. Do I?](#access)**

**30. [Do you have dataset descriptions for the datasets listed here - https://openaq-fetches.s3.amazonaws.com/index.html?](#description)**

#### Communicating with the Community

**31. [Where can I find people in the OpenAQ Community to chat with?](#chat)** 

**32. [How do I join your Slack Channel?](#slack)**

**33. [I have a question that isn't answered here. How can I get it answered?](#question)**

**34. [I've made something awesome with data aggregated onto the OpenAQ Platform. Do you want to know about it?](#tellus)**

**35. [What are your favorite emoji?](#emoji)**


#### OpenAQ Community Survey

**36. [How can I take the Community Survey?](#survey)**

**37. [How can I find the results from last year's Community Survey?](#surveyresults)**




---
### A. The Organization and Community

<a name="whatis"/>

**0. What is OpenAQ?**
    
[OpenAQ](https://openaq.org) is the world's first open, real-time and historical air quality platform, aggregating government-measured and research-grade data, as well as low-cost sensor data - entirely [open-source](https://github.com/openaq). We also help the worldwide air quality community work with these data to fight [air inequality](https://medium.com/@openaq/global-air-inequality-summed-up-in-2-graphs-ad3d5a845033#.u9295vu0i) - the unequal access to clean air. Our organization strives to be a cheerleader and connector for organizations and individuals around the world working in their communities to fight air pollution. So far, we've done this both through cultivating a virtual community, as well as by holding workshops in places like [Delhi](https://medium.com/@openaq/delhi-openaq-workshop-info-materials-and-results-2bd74b88bee6#.falrs8u1u), [Ulaanbaatar](https://medium.com/@openaq/ub-openaq-workshop-materials-e4879916208f#.34z3r9mfw), and [Sarajevo](https://medium.com/@openaq/the-next-openaq-workshop-is-coming-to-sarajevo-bosnia-in-february-apply-to-come-4b4e8e4b9265#.qpvfsu1nt). We've also [come together as a community](http://www.cleanairjournal.org.za/download/caj_vol26_no2_2016_p08.pdf) to speak out on the role governments and researchers can play in opening up air quality data, and how we, as a community, can help.

OpenAQ envisions a world where everyond breathes healthy air, enabled by universal access to data. Through open data, open-source tools and cooperation, we enable the science, communications and policy necssary to fight air pollution.  

![](https://cloud.githubusercontent.com/assets/13404290/21599553/596f1b08-d13c-11e6-8d59-bd328cdcb599.jpg)

<a name="why"/>

**1. Why does OpenAQ exist?**
    
[Air inequality](https://medium.com/@openaq/global-air-inequality-summed-up-in-2-graphs-ad3d5a845033#.u9295vu0i) – unequal access to clean air – is responsible for one out of every 8 deaths in the world. The injustice of this air pollution is often compounded by a lack of easy access to data in the most polluted places – access that, from Los Angeles to Bangkok, has historically enabled communities to improve their air. Many governments publicly share air quality data but often in disparate or temporary forms. The OpenAQ community began capturing these data in 2015 and put them in a universal format for anyone to access through our open-source platform creating the only dataset of its kind open to the world. Years later, ours is the only air quality data platform that meets all four of the following criteria: aggregating disparate data sources at the station level, making data freely available programmatically on a fine temporal level, keeping underlying data-fetching software fully open, and sharing data in physical units rather than as an air quality index. This makes us the go-to data air quality platform for many. 

Using data, open-source tools, online engagement and workshops, OpenAQ has convened various sectors to fight air inequality. We share resources and ideas developed locally at workshops and through other convenings with our global community. 
    
We do this because we think this platform can be [_transformational_](https://medium.com/@openaq/filling-the-air-quality-data-gap-10e0a494517#.jlqkzcggv) for public health and the environment. 

**2. Who started OpenAQ and what motivated them to do it?**
    
The seed of the idea for OpenAQ emerged from a small open air quality project in Ulaanbaatar, Mongolia, launched by co-founders Joe Flasher and Christa Hasenkopf along with Mongolian colleagues. Amazed at the outsized-impact a little open air quality data can have on a community, Christa, an atmospheric scientist, fell in love with open air quality projects. A few years later, she and Joe, a software developer, wondered: what would happen if all of the world’s air quality data were made available for the public to explore? One day, they quit wondering, started building, and began asking passionate     people around the world to help.

<a name="community"/>

**3. Who is part of OpenAQ and what have they built already?**
     
You can read more about the OpenAQ team [here](https://openaq.org/#/about?_k=oby6q5).

Anyone who is using data aggregated from the OpenAQ system, helping build the platform, or building on top of the platform in some fashion, and/or interacting with our community around air inequality is part of the OpenAQ Community. Here's a map of our platform's usage to date (accessed Nov 2019) from Google Analytics: 
  
![](https://user-images.githubusercontent.com/6357273/69098274-3e640a00-0a26-11ea-8987-1195f3fe3a7c.png)
  
To get a sense of who is involved with the OpenAQ Platform and using it: 
- Visit [our repos in GitHub](https:/github.com/openaq).
- Come chat with our community on [Slack](https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral).
- See our [Community Page](https://openaq.org/#/community?_k=0a10ny) that highlights some of the activities and resources created by our community.

<a name="whatorg"/>

**4. What type of organization is OpenAQ and where is it located?**

OpenAQ was fouonded in Washington, DC. As of 2018 we have held a 501(c)3 nonprofit status. Our EIN is 47-5324172.

The official address of OpenAQ is: 4301 50th St NW, Suite 300 #1046, Washington, DC 20016. Our team works remotely.


<a name="howfund"/>


**5. How is OpenAQ funded?**

OpenAQ relies on a combination of government, private-sector, and non-profit/foundation grants in the open data, air quality and general environmental and public health spaces. 

We seek to partner with organizations that are interested in fostering air quality awareness and actions around the world. We also expect large organizations that use the OpenAQ platform to find a way to give back to our community for the sustainability of our system. If your organization is interested in sponsoring our work or collaborating in some way, please let us know (info@openaq.org).

We also accept individual donations. We are always on the lookout for partnerships (of all types) to help us sustain and expand what our community is doing.


<a name="whyfund"/>

**6. Why does OpenAQ require funding, anyway?**

OpenAQ needs funds to a) fetch, store, and serve out all these data, b) keep the system in tip-top shape and develop cool enhancements that make the data easier to use, c) convene air quality enthusiasts around the world and lead an annual Community Ambassador program that trains up-and-coming air quality leaders, d) pay our four full-time staff members, and e) cover a small bit of organizational-upkeep costs. 
   
<a name="donate"/>

**7. Can I donate funds?**
   
It's awesome you'd even think of doing this! We are honored that you'd ask. Currently, there are two ways that you can help us.

1. _Contribute your time and expertise_: As a community-driven platform, your contributions and feedback have a huge impact on the long-term sustainability of the OpenAQ infrastructure. In the spirit of supporting an open source culture, here are a few ways that you can get involved:
    - Contribute to the OpenAQ  platform by adding data sources, fixing bugs, among other valuable data infrastructure support. Learn how to get started as a contributor.
    - Share feedback on the tools and other platform features we build with info@openaq.org.
    - Help spread the word about OpenAQ to your community, your government or other like-minded organizations that are interested in fostering air quality awareness and actions around the world.

2. _Make a financial donation to OpenAQ_: As an open-source organization at the forefront of fostering data transparency, we don’t extract money from our database users. We do rely on a combination of institutional funders and valuable contributions from our community. If you are a funding organization or company interested in supporting our work, please reach out to us at info@openaq.org. 

    We also accept individual donations. Learn more about how to give [here](https://secure.givelively.org/donate/openaq-inc/2021-openaq-giving-campaign). Individual financial donations will lead to greater awareness of work and impact, and provide the type of flexible, unrestricted funding needed for us to continue to grow, innovate and better serve the OpenAQ Community, while remaining a free, open-source resource for everyone.


<a name="coc"/>

**8. Do you have a Community Code of Conduct?**

Why, yes we do! Read the [OpenAQ Community Code of Conduct here](https://github.com/openaq/openaq-info/blob/master/CODE-OF-CONDUCT.md).


---

### B. Open Data Access

<a name="datakinds"/>

**9. What kinds of data are stored to the OpenAQ Platform? Where is Air Quality Index data?**

Our focus is air quality data and we aggregate primarily PM2.5, PM10, CO, SO2, NO2, O3, and BC measurements from reference-grade monitors and [low-cost sensors](https://medium.com/@openaq/low-cost-sensor-platform-pilot-launch-bd66ab226c6). For a limited set of locations, we also have data for PM1, PM1 counts, PM2.5 counts, PM10 counts, CH4, CO mass, CO2, NO, NOx, NO2 mass, O3 mass, SO2 mass, UFP count. Read more about our [data format](https://github.com/openaq/openaq-data-format) and [data type definitions](https://github.com/openaq/openaq-data-format/blob/master/data-type-definitions.md). You can read more about the sources of these data [here](https://medium.com/@openaq/where-does-openaq-data-come-from-a5cf9f3a5c85#.f5h1gpse3). We also do not store AQI data, you can find more about why [here](https://medium.com/@openaq/why-looking-beyond-air-quality-index-values-matters-d903bf773e1).

<a name="lowcostsensors"/>

**10. What are low-cost sensors and why have they been added to the platform?**

In a few words, low-cost sensors are newer, often smaller and less expensive air quality sensors than traditional reference-grade monitors. Low-cost sensors measure specific air pollutants, typically particulate matter and occasionally gaseous pollutants. While "low-cost" is subjective, the cost tends to be $100s or $1000s instead of $10,000s. 

In greater detail,  low-cost sensor data refer to all non-reference-grade data that is produced by a wide variety of sources, from individuals in their communities,  to researchers, to government actors. Low-cost sensor data does not refer directly to specific cost bands, as what counts as “low-cost” varies based on socioeconomic and regional variables. Sensors in this category use technology components that are typically less expensive to manufacture than reference sensors or use reference-grade components in an atypical configuration and, as a consequence, may generate less robust data with lower accuracy and precision.  

Learn more through the [EPA’s Air Sensor Toolbox](https://www.epa.gov/air-sensor-toolbox) and [South Coast AQMD’s AQ-SPEC](http://www.aqmd.gov/aq-spec).

Initially, OpenAQ's focus was exclusively reference-grade government air quality data, but we recognized the limitations this poses and how low-cost sensors have become an important part of the air quality ecosystem:
1. _Currently, only [half of the world’s governments produce air quality data](https://openaq.org/assets/files/2020_OpenData_StateofPlay.pdf)_, leaving 1.4 billion people without access to government-sponsored, reference grade data. Low-cost sensors can help fill in these large data gaps, particularly in the Global South, where air quality data has had historically sparse coverage.

2. _There are a growing number and variety of stakeholders who are generating air quality data._ Advancements in sensor technology and subsequent emergence of lower-cost sensors have lowered the barrier for entry, encouraging a greater number of participants to produce air quality knowledge (including researchers, community organizers, citizen scientists). We wanted the platform to reflect the diversity of the landscape, highlighting new collaborations and possibilities. 

Our [low-cost sensor platform is a pilot](https://medium.com/@openaq/low-cost-sensor-platform-pilot-launch-bd66ab226c6)! [Give us feedback](https://forms.gle/YMzf9bPsTBCQx5dj9) and let us know how you are using the data.

<a name="dataattribution"/>

**11. How are data attributed to their sources? How can I find out the sources of the aggregated data?**

Data are attributed directly to their sources in the [data format](https://github.com/openaq/openaq-data-format). This is evident when [downloading data](https://openaq.org/#/countries/AU) by CSV or accessible from the [API](https://docs.openaq.org).

You can get metadata about a source by using the [location endpoint](https://docs.openaq.org/#api-Locations) of the API. Updates to metadata can be made [here](metadata.openaq.org).

If you notice any inconsistencies or mistakes regarding attribution, please let us know at: info@openaq.org

<a name="license"/>

**12. How are the data licensed?**

Air quality data is factual in nature, and in some jurisdictions may not be subject to copyright or other protections, limiting its use or distribution. However, in some jurisdictions, copyright and/or laws and regulations may apply to some of the data on the OpenAQ platform. 

A number of our sources provide their air quality data under specific licensing, such as Creative Commons licensing or open government licenses, which require source attribution. Regardless of such requirements, we believe in the importance of attributing data sources and strongly encourage everyone to do so. Read our [Data Policy](https://github.com/openaq/openaq-info/blob/master/DATA-POLICY.md) for more information.

<a name="storage"/>

**13. How long are data stored?**

Our intention is to permanently store and provide these data. 

<a name="accuracy"/>

**14. What guarantees of the data accuracy are made of the data?** 

We don't make _any_ guarantees for data quality; that is not the goal of this platform. The goal of this platform is to create a base layer aggregating existing reported government-level, research-grade and other air quality data sources in the same universal format. 

A few more details on _why_ we don't do any QA/QC'ing of data: (1) Adjusting these values, even for some form of QA/QC, makes a judgement on a given source's (e.g., government's) data. We do not seek to do that. (2) There are many ways one can do QA/QC'ing of the data, depending on one's need and field, and (3) There are uses for the 'uncleaned' data, one of which is full transparency to downstream users.

We do have a [Community Wishlist](https://medium.com/@openaq/whats-on-the-openaq-community-wish-list-846ef2a78dc0#.c8yqmxe0x) with ideas of what people would like to see built around the platform and a QA/QC'd layer is on that. If you're interested in seeing this exist, we'd love to help you build it!

<a name="access"/>

**15. What are the ways I can access data?**

- Use [our open API](https://docs.openaq.org): This can return data from the past two years.
- [Download data by csv](https://openaq.org/#/countries): This can return data from the past two years.
- You can [build you own air quality comparisons](https://openaq.org/#/compare/MNB/Beijing%20US%20Embassy/Anand%20Vihar?parameter=pm25) of stations around the world.
- Check out the [global map](https://openaq.org/#/map) 
- [Realtime JSON dumps](https://openaq-fetches.s3.amazonaws.com/index.html)
- [Daily PostgreSQL database snapshots](https://github.com/openaq/oh-snap) on Amazon RDS
- [Realtime notifications](https://medium.com/@openaq/get-faster-access-to-real-time-air-quality-data-from-around-the-world-c6f9793d5242)
- [Whole-archive query tool](https://medium.com/@openaq/how-in-the-world-do-you-access-air-quality-data-older-than-90-days-on-the-openaq-platform-8562df519ecd)


<a name="90days"/>

**16. Why can I only access data for the last 2 years? Where's the rest of the data?**

Second question first! Don't worry, the full archives data are still stored and available through the following mechanisms:
- Go here for access to the data as it's added to our system: https://openaq-fetches.s3.amazonaws.com/index.html. This data is updated every 10 minutes when a new fetch runs. This source also contains all the information for each measurement. 

There are very powerful tools to query the above data. One example is using a distributed query tool like Athena or Spark. An example of how to do that can be found [here](https://medium.com/@openaq/how-in-the-world-do-you-access-air-quality-data-older-than-90-days-on-the-openaq-platform-8562df519ecd).

So _why_ can you only access the last two years of data through the API and download portal on the OpenAQ website? 

It comes down to keeping costs down and maintaining API responsiveness. As the number of our data records grew, it posed a challenge to make all of that information available through an efficiently running API (which also powers the download portal on the site). It also costs us a chunk of change to support a big database, so like a lot of open data projects, we opted to store older data in a more cost-effective method that lets our API run more reliably and our database be smaller.

<a name="citing"/>

**17. How do I cite the OpenAQ platform in peer-reviewed literature?**

Thanks for asking! Once your work is published, please let us know - especially if it is open access. Your work is an important example that justifies our very existence! Also, less grandiosly, it's just cool to hear about and share with the community.

Oh yeah, how to cite the platform. Here are some suggestions: 
- For a single originating data source:
"These data were accessed from the OpenAQ Platform (openaq.org) and originate from [XXXX source] (e.g. The U.S. Embassy in Kampala)."

- For multiple originating data sources that are logistically difficult to list:
"These data were accessed from the OpenAQ Platform and originate from multiple sources; see openaq.org for list of sources. 

Essentially, where possible, please recognize the originating sources of the data, in addition to their access point.

- Another example by a Community member who cited OpenAQ in their own paper:  
"OpenAQ, OpenAQ.org [online] Available from: https://openaq.org (Accessed 3
August 2017), 2017."

Check out some of the [publications](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C33&q=%22openaq%22+-%22ca+hasenkopf%22+-%22c+hasenkopf%22&btnG=) who have cited us for more inspiration!

---

 ### C. Open Software Platform

<a name="whyopensource"/>

**18. Why is the OpenAQ Platform open-source?**

We want people to be able to add to what we’re doing, to improve upon it, and to build on top of it. We also want people to be able to take snippets of our code that are most useful to them for whatever purpose. That’s best accomplished by keeping our source code open. Read more about our guiding principles [here](https://medium.com/@openaq/the-mission-of-openaq-cb159084beeb#.fo69lg5v5).

<a name="whereopensource"/>

**19. Where can I find the open-source software that utilizes OpenAQ-aggregated data?**

_Data Browsers & Visualizations:_
- [OpenAQ Browser](https://dolugen.github.io/openaq-browser/#/): This browser allows the user to sift, sort and visualize OpenAQ-aggregated data in a friendly way, built by Dolugen Buuralda in Ulaanbaatar, Mongolia

_API Libraries_
- [Ropenaq](http://ropensci.github.io/ropenaq/): an R wrapper for the OpenAQ API, built by Maëlle Salmon in Barcelona, Spain
- [py-openaq](https://github.com/dhhagan/py-openaq): a Python wrapper for the OpenAQ API, built by David Hagan in Boston, USA

<a name="licenseopensource"/>

**20. What is the license of the software?**

All parts of the OpenAQ software are under the MIT License. Each of [our GitHub repos](https://github.com/openaq) lists this under its license. See [here](https://github.com/openaq/openaq-api/blob/develop/LICENSE.md) for the API, for example.
 
 ---
 
### D. Contributing with the OpenAQ Platform & Community

#### Ongoing Projects

<a name="ongoingprojects"/>

**21. What are some ongoing open-source projects involving OpenAQ?**

Check out our community page [here](https://openaq.org/#/community/projects?_k=zruita)

_Do you have an open-source tool you'd like to share? Let us know! Make an issue in GitHub or just email info@openaq.org_ 


#### Contributing Data Sources

<a name="help"/>

**22. How can I help contribute new data sources? What information is needed for a new data source?**

Thanks for being interested in sharing a data source! You can make a [GitHub issue here](https://github.com/openaq/openaq-fetch/issues), submit something via this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSdcmn3qxoM69XIjJ3Pl4cyO6Ffk8TT40NC_XizS6snAQ7Z8_A/viewform), or email us at info@open.org. The data format and requirements are listed [here](https://github.com/openaq/openaq-data-format).

Are you part of a government entity seeking to share data? First of all THANKS! Read [this post](https://medium.com/@openaq/how-can-a-government-source-add-data-to-openaq-50b5d83ef13f) with step by step instructions.

<a name="suggestions"/>

**23. I suggested a new data source, but I haven't seen it added yet. What gives?**

For government-grade sources, we generally have [more data sources](https://github.com/openaq/openaq-fetch/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) waiting to be added than we do bandwidth to insert them. We're always seeking help from those interested and with the skills to add in data sources to our system. More info on how to get started as a contributor can be found [here](#skills). 

For research-grade data, we're working on an [automatic way](https://github.com/openaq/openaq-upload) to add in data, but otherwise it takes some time to add it in by hand.

For non-research-grade low-cost sensors, we are evaluating the best way to add in the data responsibly (it's [tricky business](http://www.nature.com/news/validate-personal-air-pollution-sensors-1.20195)) and are planning a pilot soon.

<a name="skills"/>

#### Contributing Development Skills for Enhancing the Platform

**24. What skills are needed to contribute to the code-base?** 

The front end is written in CSS, HTML and JavaScript using React. The API and updater are written in JavaScript using Node.js. There are a number of other small pieces (CSV exporter, health checker), mostly written in JS/Node.js. If you're interested in system architecture, everything runs on AWS.

<a name="helpissues"/>

**25. How can I contribute my software development skills? Where can I find existing GitHub issues I can help out with?**

Here are [Contribution Guidelines](https://github.com/openaq/openaq-api/blob/develop/CONTRIBUTING.md) for developers.

[Here](https://github.com/openaq)'s where we are on GitHub. You can see the most important respositories pinned at the top and all have managed issues lists. And one of the best ways to get oriented right now is to just reach out on [Slack](https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral).



#### Using the Data

<a name="tools"/>

**26. What community tools exist that I can use to explore the data?**

You can start playing around by [building your own air quality comparisons](https://openaq.org/#/compare/MNB/Beijing%20US%20Embassy/Anand%20Vihar?parameter=pm25) of stations around the world, check out the [global map](https://openaq.org/#/map) or [downloading data by csv](https://openaq.org/#/countries) or [our open API](https://docs.openaq.org).

Here are open-source tools built by community members:
_Data Browsers & Visualizations:_
- [OpenAQ Browser](https://dolugen.github.io/openaq-browser/#/): This browser allows the user to sift, sort and visualize OpenAQ-aggregated data in a friendly way, built by Dolugen Buuralda in Ulaanbaatar, Mongolia

_API Libraries_
- [Ropenaq](http://ropensci.github.io/ropenaq/): an R wrapper for the OpenAQ API, built by Maëlle Salmon in Barcelona, Spain
- [py-openaq](https://github.com/dhhagan/py-openaq): a Python wrapper for the OpenAQ API, built by David Hagan in Boston, USA

_Do you have an open-source tool you'd like to share? Let us know! Make in issue in GitHub or just email info@openaq.org_ 

<a name="usedata"/>

**27. What are cool ways that I can use the data?**

That's really up to you! And your imagination is the limit. In addition to the tools in the above question, you can find out how our community is using the data on our [Community Page](https://openaq.org/#/community), [our blog](https://medium.com/@openaq) and just by chatting with people on [Slack](https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral).

You can start playing around by [building you own air quality comparisons](https://openaq.org/#/compare/MNB/Beijing%20US%20Embassy/Anand%20Vihar?parameter=pm25) of stations around the world, check out the [global map](https://openaq.org/#/map), [downloading data by csv](https://openaq.org/#/countries?_k=kxpa7v) or use [our open API](https://docs.openaq.org).

<a name="multiples"/>

**28. Why does the same location occur multiple times?**

This normally happens because the location names are slightly different coming from the source. Let's take a look at 'Shastri  nagar, Jaipur - RSPCB' as an example.

![img_1431](https://user-images.githubusercontent.com/848934/42659278-c897a8be-85f5-11e8-8327-db32d5fc1ea1.jpg)

You can see here that there are slight differences in spacing, which makes our system think these are different locations. Without a universal ID for all instruments, it's difficult to know exactly that these locations are the same. However, you can look at their coordinates (if provided) and make a guess that they're the same location.

<a name="access"/>

**29. I think I may need an access key to access data stored in S3. Do I?**

The data is in a publicly accessible bucket, so there is no key for us to provide. This sounds like you are trying to use the AWS CLI or an SDK to access the bucket but have not provided your personal AWS account credentials (that you create yourself). If you have an AWS account, you can provide those credentials. But also, you can just use the --no-sign-request flag in the CLI (or similar in SDK) to tell the request to not pass any credentials. That should also allow you to proceed. 


<a name="description"/>

**30. Do you have dataset descriptions for the datasets listed here - https://openaq-fetches.s3.amazonaws.com/index.html?**

The Daily file was a daily rollup of the data coming into the system but has been deprecated for some time so you’ll only find older data there. You likely want to use the realtime or realtime-gzipped prefix (same data, just one is compressed and the other is not). This data comes in ~10 minute intervals as it is inserted into our system. There’s a folder with all the files for every day, all of the files are named with a timestamp for when the file was created. So if you’re searching for specific days or looking to do aggregations, the best way to do so would be to use AWS Athena, this guide https://medium.com/@openaq/how-in-the-world-do-you-access-air-quality-data-older-than-90-days-on-the-openaq-platform-8562df519ecd may be helpful.


Broadly, the data in those files conforms to the format laid out in https://github.com/openaq/openaq-data-format/.

#### Communicating with the Community

<a name="chat"/>

**31. Where can I find people in the OpenAQ Community to chat with?** 

The most substantive way to interact with the community is to join our [Slack Channel](https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral). If you're not familiar with Slack, it's just a free tool we use to chat with one another. 

You can also join us on [Twitter](https://twitter.com/Open_AQ) or on our [Facebook Page](https://www.facebook.com/openaq/). 

Always feel free to reach out by email, too (info@openaq.org). 

<a name="slack"/>

**32. How do I join your Slack Channel?**

Go here: https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral/

<a name="question"/>

**33. I have a question that isn't answered here. How can I get it answered?**

The fastest way is to join [our Slack channel](https://join.slack.com/t/openaq/shared_invite/zt-gq14aew7-CVdp131g7TR7o9iiXIVDLwGeneral) and ask us and the rest of the community. The second fastest way is to email info@openaq.org. 

Slack is faster than email because you'll get to talk to the whole community who often know more than any single one of us and also are in various timezones. At this point, Community members are spread over many parts of the world.

<a name="emoji"/>

**34. I've made something awesome with data aggregated onto the OpenAQ Platform. Do you want to know about it?**

Is the sky blue (on an unpolluted day)? YES!! We are _always_ interested to hear how people are using these aggregated data - in fact, conveying the awesome work going on in our community is how we justify our existence to both ourselves and our funders! So please do tell us (info@openaq.org). 

**35. What are your favorite emoji?**

That's such an odd and awesome question. Here you go: 👍💃🐶🚀
