# Project 1: Classic HTML Document & Wireframes

*Due: Thursday, October 21, 2021 (one week)*


Remembering that the original use of the web was to post academic research papers online, we will start a series of projects by replicating the type of documents that were created at that time.  In later projects: we will format our documents with CSS, and after that we will add interactive *behaviors* using JavaScript to create a look & feel of a modern brochure website.

- This first step, Project 1, you will use NO formatting – you will do *nothing* to your HTML documents to try and make it look nice.  The goal is to simply **gather content, and mark it up semantically correct** using HTML5 tags, and let the formatting be done automatically by the browser’s built-in styles.  

- At the same time, you will create a set of **wireframe diagrams** that relate to the content, which indicate how you plan to layout the content when you apply CSS (later, in Project 2).
- You will also make sure all the HTML documents meet **all industry standards and best practices**, and then publish them on the class web server.

## Step 1: Form Teams

- If you haven’t already, use our [ISTE-140 City-Teams (Google Sheet)](https://docs.google.com/spreadsheets/d/1c-SXrIti10_0lrW8V6KgVKQchu6ykPR3JEdp50Msh6Y/edit#gid=0) to list your “Preferred role” (next to your name); and add some notes about yourself (optionally)
  - **Information Architect (IA)** - the person who will wrangle the content (mostly focused on HTML and document structure)
  - **Designer** - the person who will create the wireframes and chose the look & feel for the website (mostly focused on CSS)
  - **Technician** - the person will will host the website, install the JavaScript plugins (when we learn about that) and ensure it meets all technical standards and industry best practices
- Then reach out to two other students in the “Pick list” to form a team
  - Advice: choose a students who have skills you *don’t* have. The best teams are technically diverse - not just a team of friends.
  - DM each other here in Slack to contact each other
- Once you have an agreement to form a team, move (drag and drop) your names from the pick list to an unoccupied team column
  - Everyone has to pick an initial role for themselves: IA; Designer; or Technician. (You can change later if you want.)

- Create a private channel for your team in Slack: one team member creates the channel and then invites the other members
- As a team, decide in which city your team will be based. (This is just a team-building activity. It doesn’t really affect anything.)

## Step 2: Gather Content

*This step is typically lead by the IA, but there needs to be a consensus among the team*

- As a team, propose a topic for your website; then write the topic in the [ISTE-140 City-Teams (Google Sheet)](https://docs.google.com/spreadsheets/d/1c-SXrIti10_0lrW8V6KgVKQchu6ykPR3JEdp50Msh6Y/edit#gid=0) (row 5)
  - Note: you can change the topic later if need be; it’s just a proposal at this time

- As a team, gather resources from which you will build the website
  - Required: there needs to be *at least* two sources for content (more would be better); one of them can be Wikipedia, but there has to be more
  - Suggestion: start finding websites with good/usable content and paste URLs in your private Slack channel; good resources will have plenty of text, images, and if applicable other media (videos, embedded games, whatever)
  - REQUIRED: somewhere in the website that you'll build there must be at least one data table with at least three columns and five rows (this is an arbitrary requirement, just to demonstrate you can do it; if you can't find a data table, you can construct one yourself using any, related and meaningful content and arrange it into columns and rows)
  - Also REQUIRED: somewhere in the website that you'll build there must be at least one list: ordered, unordered, or a definition list ...your choice (this too is an arbitrary requirement, just to demonstrate you can do it)

## Step 3: Plan a Layout

*This step is typically lead by the Designer.  Other team members can help and make suggestions but in the end, the Designer will be graded for this part.*

- As a team, propose a layout for a multipage website based on the content you've gathered  (discussion and decision needs to be lead by the Designer, but there needs to be a consensus among the team)
  - Suggestion: use websites with similar content as inspiration, but limit your inspiration to "brochure" -type websites (no application websites, because we're not building that in ISTE-140)
- Create a set of TWO wireframe diagrams: one for a homepage; another for the subpages
  - Be sure to keep the diagrams "low fidelity" and label the elements generically; e.g. "banner", "hero image and text", "lead paragraph", etc.
  - Note: typically the wireframe for the homepage should incorporate placeholders for large, graphic elements, and the wireframe for the subpages will be more text-heavy.
  - Also be sure to leave a space where you will embed links to the source materials (citations/references); where they go is up to you
  - Note: you only have to create wireframe diagrams for typical desktop/laptop-sized viewports; we'll create wireframes for mobile device-sized viewports as part of Project 2.

## Step 4: Stub-out Two HTML Document Templates

*This step is typically completed by the IA. Other team members can help and make suggestions but in the end, the IA will be graded for this part.*

- You will need two HTML document templates: one for the homepage; another for the subpages
  - Note: "template" just means a regular HTML document with a complete set of document structure tags in the BODY, but without real content.  Later, you will use the templates to make copies of the files, rename them to something appropriate, and then fill the copies with content.
  - Suggestion: name the template file for the homepage: **home_template.html**; and name the template file for the subpages: **subpage_template.html**
  - The subpages must all have similar document structure, so no matter how many subpages will be created, they will all follow the same template
  - Focus on creating a document structure using the correct, semantically relevant HTML tags that match the elements indicated in the wireframe diagrams
  - Use lorem ipsum (placeholder) text and FPO images as needed to flesh-out the two template documents
  - Be sure to include an identical menu system on both templates; leave room for at least five navigation elements (links)
- IMPORTANT: the document structure (the HTML tags) in the templates *must* indicate where and how they relate to the wireframe diagrams!
  - REQUIRED: use ID attributes (`id=""`) in the HTML where appropriate to relate sections of the document to the labeled sections in the wireframes
  - Lack of continuity between the HTML document templates and the wireframe diagrams will lose points for both the IA and the Designer

## Step 5: Flesh-out the Website with Content

*This step is typically lead by the Technician with help from the rest of the team but in the end, the Technician will be graded for this part.*

- As a team, decide how many webpages to create based on the content gathered from Step 2 and the  wireframe diagrams and HTML templates from Steps 3 and 4.
  - REQUIRED: in addition to a homepage, there must be at least three identically structured subpages,  but no more than five subpages
- Make copies of the templates and name the new files appropriately
  - The copy of the home page template must be named: **index.html**
  - The copies of the subpage template can be named anything, **.html**, however the names must be descriptive of the content that will go in the subpage; e.g. a webpage about Mark Zuckerberg should be named something like **mark-zuckerberg.html**
  - Code and make sure the navigation elements on each webpage work as expected
- Fill the webpages with content, replacing the placeholders with actual content
  - Note: embedded images and other media must be prepared and sized according to how they're going to be used when CSS is applied in Project 2; for example, if a wireframe diagram indicates the presence of a "sidebar" (narrow element) with an image positioned somewhere in it, the actual image that's used in the HTML document must look like it's going to fit that element when we style it as part of Project 2
- REQUIRED: all content must meet all industry standards and best practices
  - Note: all the things you must and must not do cannot be listed here in this instruction sheet; you are required to know what to do (and what not to do) based on the class lectures and lab assignments covered so far in ISTE-140 (except design for mobile; that'll be required in Project 2)

## Step 6: Publish the Website and Turn-in the Templates and Wireframe Diagrams

- **Technician:** publish the plain HTML webpages and their associated media on the class webserver in a folder named: **project1**, then post a link to the project in our MyCourses section, "Project 1" under Assignments
  - Note: do not put anything on the class webserver that is not part of the website
- **Designer:** turn-in the wireframe diagrams (x2) in our MyCourses section, "Project 1" under Assignments
- **Information Architect:** turn-in the HTML templates (x2) in our MyCourses section, "Project 1" under Assignments

NOTE: for teams of two, be sure to make multiple submissions in MyCourses, one for your primary role and  another for the other role.

NOTE: not only will everyone be graded for their individual parts for which they are responsible, but there will also be "continuity" points awarded for coherence across the three submissions.