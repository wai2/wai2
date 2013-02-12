#The Web API Interoperability Initiative (API2)

This is the very rough early draft of the [**WAI2**](https://github.com/wai2/wai2#readme)'s charter.

##Purpose
The WAI2's purpose is to establish a process to agree on practices, idioms, and conventions to move the state of web APIs forward such that it becomes much easier to process a set of instructions with decreasing coding effort and increasingly less coupling.

## Approach
To achieve our purpose we plan to:

- Address 80 percentile use-cases and ignore the remaining 20%.
- Provide ways to address the remaining 20% via coupled code.
- Favor constraints vs. enabling multiple ways to do the same thing.
- Favor many small steps vs. a few large steps.
- Embrace contributions of all who embrace our mission, vision and values.
- Accept good enough solutions vs. striving for perfection.

## Deliverables

- **A set of recommendation documents** that describe each individual solution we codify. These recommendations will likely evolve into actual standards blessed by an appropriate standards body, i.e. [w3c](http://www.w3c.org), [ietf](http://www.ietf.org), etc. but some many simply become defacto standards.
- **A complete Javascript-based reference implementation** of the standard designed for actual use and for validating the compatibility of other implementations.

## Get Involved
You can contribute and/pr participate by:

- **Submitting proposals** for discussion [**here**](https://github.com/wai2/wai2/issues) on the GitHub issue tracker
- **Discussing the proposals**  on the [issue tracker](https://github.com/wai2/wai2/issues).
- **Discussing ideas** on the [API Craft](http://groups.google.com/group/api-craft) mailing list _(assuming list owners/members do not object.)_
- **Suggesting changes** to this document; Clone, change and submit a pull request.
- **Suggesting wiki change requests**  - [Here's how](#wiki-change-requests).
- **Authoring** first draft **recommendations** of for API solutions.
- **Developing** portions of the Javascript-based reference implementation.
- **Implementing** recommendations in other languages besides Javascript.

## Mission, Vision and Values
This is the first draft of the WAI2's Mission, Vision and Values.

### Mission
To enable machine-to-machine interaction over the web by bringing the most active actors in the web API community to collaborate toward achieving full interoperability with a goal of

### Vision
Enabling machine-to-machine interaction across that web will one day be as easy as describing to your API agent what you want to happen in an easy-to-learn manner and then have it do the work as described.

### Values
We simply steal from [The Zen of Python](http://www.python.org/dev/peps/pep-0020/):

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!

## Building Blocks/Prior Art
Below are the building blocks we want to build on or coalesce into an interoperable web API future.

IMPORTANT: The WAI2 does not not want to new standards that doesn't need to be created. We want to see increased collaboration and interoperability and only want to create new with nothing existing currently suffices.

### Standards
- [HTTP](http://www.w3.org/Protocols/)
- [JSON](http://www.json.org)
- [URI](http://tools.ietf.org/html/rfc3986)
- [URI Templates](http://tools.ietf.org/html/rfc6570)
- [HTML](http://www.w3.org/html/)
- Other?

### Formats

- [HAL](http://stateless.co/hal_specification.html)
- [Siren](https://github.com/kevinswiber/siren#readme)
- [Collection+JSON](http://amundsen.com/media-types/collection/) (Cj)
- [OData - JSON Light](http://www.bitwhys.com/odata-101-what-is-json-light/)
- [The Object Network](http://the-object.net)
- Other?

### Authentications
- [HTTP Basic & Digest Auth](http://tools.ietf.org/html/rfc2617)
- [OAuth](http://oauth.net)
- [OZ](https://github.com/hueniverse/oz)
- Other?

### Efforts

- [HFactors](http://amundsen.com/hypermedia/hfactor/)
- Other?

**NOTE:** [XML](http://www.w3.org/XML/) is deliberately not included because it's complexity runs counter to the goals of establishing a minimum solution set for 80th percentile use-cases. After many of our initial goals are achieved we'll likely address XML as it moves into the 80 percentile of problems that WAI2 solutions do not yet resolve.


## People
**Anyone can [contribute or participate](#get-involved)** but this is the initial list of people who will be invited and/or committed to steer this effort and have commit access to the GitHub repo _(in no particular order):_

Person | Reason | Status
-------|--------|--------
Mike Admundsen<br>[@mamund](http://twitter.com/mamund)|Author of [Collection+JSON](http://amundsen.com/media-types/collection/) and [HFactors](http://amundsen.com/hypermedia/hfactor/).<br> Founder of [RESTfest](http://www.restfest.net).<br> Active on [API Craft](http://groups.google.com/group/api-craft)|Invited
Kin Lane<br>[@kinlane](http://twitter.com/kinlane)|Lead API Evangelist at [APIEvangelist.com](http://apievangelist.com).<br>Semi-active on [API Craft](http://groups.google.com/group/api-craft)| Participating
Kevin Swiber<br>[@kevinswiber](http://twitter.com/kevinswiber)|Author of [Siren](https://github.com/kevinswiber/siren#readme)<br>Contributor(?) to [_3rd edition of "Web API Design"_](http://blog.apigee.com/detail/api_design_third_edition_video_slides)<br>Active on [API Craft](http://groups.google.com/group/api-craft)| Participating
Mike Kelley<br>[@mikekelly85](http://twitter.com/mikekelly85)|Author of [HAL](http://stateless.co/hal_specification.html)<br>Active on [API Craft](http://groups.google.com/group/api-craft)|Participating
Glenn Block<br>[@gblock](http://twitter.com/gblock)|Engineer on [Windows Azure](http://windowsazure.com)<br>Formerly vision behind [ASP.NET Web API](http://www.asp.net/web-api).<br>Co-author of [Designing Evolvable Web APIs with ASP.NET](http://shop.oreilly.com/product/0636920026617.do?sortby=publicationDate)|Participating
Mike Schinkel<br>[@mikeschinkel](http://twitter.com/mikeschinkel)|Started the discussion with [this](http://groups.google.com/group/api-craft/browse_thread/thread/d231ca8116763c16/e54390a7952916e1?#e54390a7952916e1) email and this GitHub repo.<br>Author of [RESTian](https://github.com/newclarity/restian) and [Concierge](https://github.com/newclarity/concierge).<br>Semi-active on [API Craft](http://groups.google.com/group/api-craft).|Participating
Brian Mulloy<br>[@landlessness](http://twitter.com/landlessness)|Author _"[_Web API Design_](http://blog.apigee.com/detail/announcement_new_ebook_on_web_api_design)"_ eBook _([_3 editions_](http://blog.apigee.com/detail/api_design_third_edition_video_slides))_ <br>(Co-?)Founder of  [API Craft](http://groups.google.com/group/api-craft)| Participating

If your name is on the above list and this is the first you've heard of this, consider yourself invited and please [send a DM via twitter](https://twitter.com/direct_messages/create/mikeschinkel) and indicate if you'd like to be added to the  WAI2 Contributors team with push and pull access.

If your name is not on the list can you still actively [**participate**](#get-involved).

## Wiki Change Requests
We will be following the general wiki maintenance approach [documented](http://fusiongrokker.com/post/how-you-can-contribute-to-taffy-documentation) by [Adam Tuttle](http://github.com/atuttle).

The approach requires you to clone the WAI2 wiki to a local repo and create a remote repo in your own GitHub account for you to push your committed changes to. You then make changes and push your changes to your GitHub repo after which you [**submit an issue**](https://github.com/wai2/wai2/issues) with a link to your repo explaining your change and requesting we apply your change to our wiki.

Yes this is a lot of effort but it is currently [**what GitHub recommends**](https://github.com/github/gollum/issues/265#issuecomment-5529605) the best practice for accepting external contributions to their wikis.

1. Go to GitHub and [**create a new repository**](https://github.com/new) in your own account named `wai2-wiki`.
2. Using the terminal/command line:

 Action  | Command
 --------|--------
 **Change** to a local projects dir|For example: `cd ~/Projects`
 **Clone** the WAI2 wiki|`git clone git@github.com:wai2/wai2.wiki.git`
 **Change** to the new local subdir|`cd wai2.wiki`
 **Remove** link to WAI2's wiki repo|`git remote rm origin`
 **Change** link to your new repo|For SSH:<br>`git remote add origin git@github.com:<USERNAME>/wai2-wiki.git`<br><br>For HTTP:<br>`git remote add origin  git://github.com/<YOUR_USERNAME>/wai2-wiki.git`<br><br>&nbsp;&nbsp;Be sure to replace `<USERNAME>` with your GitHub account user name.
 **Initialize** link to your repo|`git push -u origin master`
 **Make changes** to your local repo|Use your favorite Markdown editor to make changes such as with one like [this](http://www.markdownpro.com).
 **Commit changes** to your local repo|`git commit -m "My wiki changes comment"`
 **Push changes** to your GitHub repo|`git push`

3. Next [**post a request**](https://github.com/wai2/wai2/issues) on the issue  tracker to have us review and potentially apply your changes. Be sure to include **a link** to your repo and **a description** of your changes **detailed enough** we won't need wonder.

5. _OPTIONAL:_ [**Post a comment**](https://github.com/github/gollum/issues/265#issuecomment-5529605) the issue tracker for GitHub itself to provide a simpler process for would-be contributors.

## History
This initiative began with [this email](http://groups.google.com/group/api-craft/browse_thread/thread/d231ca8116763c16/e54390a7952916e1?#e54390a7952916e1) on the API Craft mailing list.

## Sponsors
No sponsors at this time.

## License
The WAI2's goal is to publicly and freely license the results it produces. As such we will likely apply a Creative Commons license for any documentation and recommendations produced and an Open Source license for any source code produced pending discussion by founding participants.
