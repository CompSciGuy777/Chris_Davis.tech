== ChrisDavis.tech

# Planning our Application

	1.  Answer Questions

			 - What are we building?

			 - Who are we building it for?

			 - What features do we need to have?

	2. User Stories

	3. Model our Data

	4. Think through the pages we need in our App


## Questions

	1.  What are we building?

		We are building a personal site.  A place to showcase our work, write Articles (discuss tricks, ideas, and
		our current trends), and have people contact us

	2. Who are we building it for?

		We are building it for ourselves and the community.  Sharing what we are learning is a great way to:

			- Learn better ourselves
			- Share good knowledge with others
			- Show potential employers what our knowledge base and experience is

	3.  What features do we need to have?

		- Posts

			- CRUD
			- markdown formatting
			- syntax highlighting
			- comments (disgus)

		- Projects

			- CRUD
		
		- Contact
			- Contact Form
			- Sendgrid

		- User (devise)

## User Stories

	As a blank, I want to blank, so that blank

		- As a user, I want to be able to share posts, so I can share what I am learning on my blog

		- As a user, I want to be able to edit and delete posts, so I can manage my blog

		- As a user, I want to be able to write posts in markdown, so that it is easy for me to write posts

		- As a user, I want to be able to highlight various syntax of code blocks I share on my site

		- As a user, I want to show visitors and potential employers example of stuff I have built, through pictures and videos.

		- As a user, I want to have visitors be able to leave comments and contact me through a form on my site


## Modeling our Data

	**Post**
		title:string
		Picture: media
		content:text

	**Project**
		title:string
		Media: Media
		description: text
		link: string
	
	**User**

## Think through the pages we need in the app

	- Home
	- Posts#index
	- Post#show
	- Projects#index
	- Projects#show
	- Contact Us
	- About

