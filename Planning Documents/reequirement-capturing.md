## Project Requirments for George's Portfolio

**Document Created:** 11/07/2026

**Author:** George Ashcorft

## 1. Introduction

### 1.1 Document Purpose

The purpose of this document is to describe the overall feature requirements needed to be built by myself in order to further develop my skill set and create a site to display my own skills.

### 1.2 Project Background

This was prompted when I realised that I actually don't have anything to show my overall skill set as a developer or as an individual. So I thought creating a site with fun and loose documentation would be a great way to show case myself!

### 1.3 Purpose of the Requirements

Please note **none of this is professional on purpose**. Professional is for work hours. This is my fun hours. I just like doing the boring documents to have a semblance of a plan.

### 1.4 The Goal and Objective of this Project

The underlying goal of this project with anything I undertake as a developer in my downtime is to improve as my delevoper. The measurable outcome for this is to finally have a site that I can call my own accessible to the public where I can host my silly projects. Experiment with ideas and show off what I'm learning.

## 2. Scope of the projects

The initial scope of this project is to create a simple blog which would allow me to begin talking about and developing future projects to be hosted in site. This should start off simple in nature first. I know. Another blog. But I want to make this fun and I want proof of my development. I want this to be more than a dev blog. I want this to be a George blog. So it must be able to CMSable so I can easily publish new content with images on a whim. In this instance because of the scale local image storage should suffice.

### 2.1. In Scope Deliverables

The site must include the following pages:

- A visually impressive **landing page**
  - Display technical ability and a clean UI for easy navigation
- A fun and interactive **about Me**
  - Shows off some facts about me as well as my hobbies and details of what I do
  - Could be a fun scrollable timeline og my life which can be humourous from birth to adulthood etc.
- A **blog** for project development
  - This blog should be searchable and filterable by clear categories
  - Comments would be a nice to have to allow room for feedback or general input
- A **Contact details** page
  - Ideally sends emails directly to my own personal email
  - Accepts contact detail fields to allow me to respond when necessary
- A **CMS** to manage and create content
  - Should allow me to create custom content blocks that I can style and use
  - Should be locked behind a login process to ensure only I have access to the account
- A **file storage system** for uploaded images
  - Create a easy navigatable system to allow me to see and reuse images across the site to prevent file dupliucation

### 2.2. Out of Scope Deliverables

Aspects deemed out of scope which I have been wanting to do for a while. Having a portfolio site should be a good push to do all this!

- **Spotify API integration** to display what I'm listening to and music stats. Make it fancy and fun. For instance a spinning record with the album art.
- **Easter eggs** that with certain key presses trigger a fun overlay. Maybe a cool simple animation. Shout outs to close friends etc.
- **Discord Bot integration** that can be used to directly message me as well as display my current status onto the site.

## 3. Functional Requirements

### 3.1 Actor Profiles Specification

#### Visitor User Specs

1. A vistior must be ablle to access a **Landing Page** consisting of a clean hero image that displays what the site is.
  1.1 The landing page must be configurable in the CMS with customizable content like side on images and text.
  1.2 The landing page must also have a direct link to the about me page with an eye catching hero image front and center
  1.3 The landing page must have a degree of flair or wow factor in order to show off a complex understanding of front end work. Even if this isn't my specialty.
2. The site must have a clean accessible **Header** which displays each of the sites endpoints with a designed logo for myself that redirects to home.
  2.1 This CMS should be configurable within the CMS but isn't essential as we can scale this for future work.
  2.2 This header must blend in well with the general style of the site.
  2.3 This header must redirect users to each of the expected pages seamlessly.
3. The site should have a **Footer** displayed to the user with general links to socials, aspects of the site and so on.
  3.1 This must respect logo restrictions and copyrights to ensure we aren't in breach of any of their stylings.
  3.2 This segment isn't necessary depending on how we want to stylise the site.
4. The site must have an **About Me** that displays information about me cleanly
  4.1 The about me should include, Hobbies, Work Experience, a General Bio about me (age, where I'm form etc.).
  4.2 The about me should be configurable via the CMS but isn't essential as it's largely going to be stylised.
  4.3 The about me should also have my CV downloadable for any potential prospects.
5. The site must have a **Contact Me** page that emails me directly.
  5.1 The recieved email must include the senders email as part of the body as well as a subject tag.
  5.2 The contact me page should have some degree of spam prevention such as a honey pot to prevent bot spam.
  5.3 The contact me page must have the following fields as part of the form: Subject, Email and Message.
  5.4 The contact me page could include some form of security test for better security against bots such as turnstile or captcha.
6. The site must have a **Blog** page that shows any posts I create.
  6.1 The blog must be filterable or have header categories that show different things. These could include Hobbying, Project or even general thoughts.
  6.2 The blog must display blog titles, subjects and publish date which can be filterable and searchable by these values.
  6.3 The blog must open each of these articles as a pop up page for simple and quick viewing.
  6.4 The blog should be clean and easy to navigate and read with easy linking with anchor tags.

#### Admin User Specs

1. The site must contain some form of site tracking for general statistics to see how many people have visited the site.
  1.1 The site should include a GDPR disclaimer on site first access that when accepted instantiates the necessary cookies required.
  1.2 The site should include either an external tool such as google analytics cookies or an internal tracker for unique devices accessing it.
2. The site must include a backend CMS system that utilizes a configurable clean system. 

## 4. Non-Functional requirements

This section describes the non-functional requirements part of the Business Requirements. A non-functional requirement is typically a special requirement that is not easily or naturally specified in the text of the Use Case’s or function’s event flow. Examples of non-functional requirements include legal and regulatory requirements, application standards, and quality attributes of the system to be built including usability, reliability, performance or supportability requirements. 

###5.1.	Security Requirements
This section describes the Security requirements part of the Business Requirements.

####5.1.1.	Authentication
This section describes the Authentication requirements part of the Business Requirements. 

####5.1.2.	Authorization and Access Controls
This section describes the Authorization and Access Control requirements part of the Business Requirements at a high-level. Authorization is the process of determining if the person/group, once identified through the “Authentication process”, is permitted to have access to certain services. 

###5.2.	Availability Requirements
This section describes the system availability requirements.

###5.3.	Usability Requirements
This section describes the system usability requirements. A usability requirement specifies how easy the system must be to use. Usability is a non-functional requirement, because in its essence it doesn't specify parts of the system functionality, but specifies only how that functionality is to be perceived by the user, for instance how easy it must be to learn and operate the system.

###5.4.	System Help Requirements
This section describes what kind of System Help features need to be built into the system. 

###5.5.	Performance Requirements 
This section describes system performance expectation levels (response times).

###5.6.	Scalability Requirements
This section describes how the system is expected to scale to new higher or lower levels. Both user and application scalability requirements are described here. Data scalability is not described here as it is already described in the “data volumes” section earlier.

####5.6.1.	User Scalability
How the system should scale as more and more users are added.

####5.6.2.	Application Scalability
How the system should scale to meet performance demands.

##6.	Interface Requirements
This section describes User and System Interface requirements for the proposed system.

###6.1.	User Interface Requirements
It may be helpful to reference screen and report designs in this section.

###6.2.	System Interface Requirements
Use this section to list all required APIs into and out of the system, note those that exist and can be leveraged separately from those that need to be built for the Application to meet the business requirements.