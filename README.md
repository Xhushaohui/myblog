# How to build a blog & portfolio with Rails 4
  
## Planning our application

		1. Answer Questions

			- What are we building?
			- Who are we building it for?
			- What features do we need to have?
		
		2. User Stories.
		3. Model our Data.
		4. Think through the pages we need in our application.

			
## Questions

		1. What are we building? 
		
			We are building a personal site. A place where we can
			blog, share examples of our work, and have people contact us.

		2. Who are we building it for?

			We are building it for ourselves, but also the community.
			Shareing what we are learning by blogging is a great way
			to learn for ourselves, but we teach others in the process.
			Show potential employers that they know what we are doing.
			
		3. What features do we want to have?
				- Posts
						- Creat / Edit / Destroy
						- Markdown
						- Syntax highlighting
						- Comments(Disqus)
				- Projects
						- Creat / Edit / Destroy
				- Contact
						- Contact form
						- Sendgrid
				- User (Devise)
	


## User Stories
   As a user, I want to **BLANK** because of **BLANK**
   
		- As a user, I want to be able to creat posts so that I can share 
		  what I am learning on my blog.
		  
		- As a user, I want to be able to edit & destroy posts, so that I 
		  can manage my blog.
		  
		- As a user, I want to be able to write posts in markdown format
		  so that it's easy to me to write posts.
		  
		- As a user, I want to be able to highlight the various syntax of 
		  code blocks that I share on my blog.
		
		- As a user, I want to show the visitors and potential employers 
		  examples of my work, or stuff I've build.
		
		- As a user, I want to be able have visitors contact me through a
		  form on my site.
		  
		- As a user, I want visitors to be able to leave comments on my posts.
	  		
## Modeling our Data

**Post**
	
		title :string
		content:string
		
**Project**

		title:string
		description:text
		link:string
		
**User**

## Think through the pages we need in our app

		- Home
		- Posts#index
		- Posts#show
		- Projects#index
		- Projects#show
		- Contact

 



		
		