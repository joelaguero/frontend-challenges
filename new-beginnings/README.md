
# Challenge: "New Beginnings" #

Thanks for taking the time to complete this challenge. We know it requires an investment of time on your part, but we think it'll help us both assess fit.

Please don't spend more than 4-5 hours on it. We ultimately want a sense of how you think, how you code, how far you get, and how you justify decisions. Your welcome to use the output of this challenge on your own portfolio, regardless of whether or not we end up working together.


### Project Brief ###

You're leading an autonomous R&D team of 15 engineers and 2 designers at an international software company, MEGA Corp. Your team is tasked with building an internal social network that will be used daily by 5-10k employees at your organization, for business-critical logistics like clocking-in/out, logging hours, documenting meeting notes, and more.

You were selected for this role because you've demonstrated a good track record of individual code contributions and broader infrastructure guidance, particularly when it comes to shipping compelling, stable, and performant user interfaces.

Now, you must lay the foundations of a new client-side codebase that enables your team to be productive, despite an insufficiently-defined product roadmap. As part of a broader company push, the stack must use React; however, you have the authority to integrate any other tools and libraries that will help your team succeed. Additionally, you've just been told that your team will gain between 5 and 20 new engineers over the next year, so your codebase's workflows should be able to scale as necessary.

## Final Deliverable ##

Please create a new repository and implement the foundation of your codebase there. Additionally, please demonstrate the intended workflow for a typical feature by implementing something like the following:

 - A flow for new team members to sign up and join the platform
 - A calculator widget that could be integrated into other areas of the platform down the line
 - A data visualization widget, perhaps using [a publicly available API](https://github.com/toddmotto/public-apis) as an example

### What We're Looking For ###

Your codebase and demonstration should showcase the following:

 - A clear workflow around new feature development, including contribution guidelines and expectations.
 - A thoughtful take on application architecture and state management that can scale with dozens of new features and team members, while accommodating new areas of the application overtime.
 - A clear philosophy on managing authorization and security, given the sensitive nature of your company's internal operations.
 - A strong implementation of testing infrastructure, including (though not necessarily limited to) the following:
	 - Unit tests for components in your demonstration.
	 - Acceptance tests showing components integrate and enable complete user workflows, as expected.
	   - An example of this is - on a sign up flow - a user is able to enter invalid input, click submit, and see the expected error message or fields rendered.
	 - Visual regression testing, enabling devs to verify UI diffs after introducing new features and ensuring other areas don't change unknowingly.
	 - Automated performance testing that ensures the production app will load expediently.
 - A perspective on code documentation, comments, legibility, and the like - including but not limited to...
	 - Best practices, guidelines, and any automated enforcement when writing JavaScript, CSS, etc.
	   - This should include a perspect on code documentation and code commenting.
 - Anything else you deem helpful to make your team as productive as possible, make developer workflows as enjoyable as possible, and make the end result as stable as possible.

### What We Care About ###

Ultimately, we want to see how you forecast team needs, design developer workflows, and evaluate trade-offs between ease of deployment, testing, new feature integration, security, and other common concerns when building and scaling web applications.

## Assumptions ##

 - Client-side hydration will happen from a separate API that connects to a backend, so you can assume the web application is static unless you feel strongly it should be dynamic. Don't let us hold you back!
 - No need to spend time making things pretty, but we are interested in your perspective on front-end frameworks and their integration - especially from the perspective of developer workflows, consistent layout, responsiveness, and performance.

## Submission ##

Email us a link to your repository once it's done. Please provide a README that briefly summarizes your development choices. (The README need not be longer than this brief, but do include instructions on how to walk through your demonstration, what we should be looking for, and any non-obvious areas you'd like to draw attention to.)

Thanks again for taking the time to do this. We hope you find it fun and challenging. If you have suggestions to make it better, please don't hesitate to let us know.
