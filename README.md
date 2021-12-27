# WordPress Developer Test

This is a test project to assess a wordpress developer's skills.

### Tips for passing this test
- Use simple frameworks instead of bloated or complicated ones.
- Ask us if you're unsure about something.
- Do the best you can - your effort and approach are being tested. We are also trying to understand how you wrap up a project temporarily before it is fully complete.
- It's better to de-risk the project by finishing the most complex aspects first.
- It's better to stop short and provide a well documented handoff rather than working right up until the time limit.

### Requirements
> When you start the test, create a GitHub repo and grant access to `wildmedia`<br />Create a README with an estimate for each of the individual tasks below:

##### Create a plugin called "Easy Videos" with the following features:
- As an admin, I should be able to bulk import videos from the youtube channel or user via youtube API to a custom post type `video`
    - It should also allow video categories (needs to be a separate taxonomy and not default categories in wordpress) to be saved as well and correctly attached to the imported videos.
    - The video category once saved should not be saved again but attached to next videos that have the same category.
- I should also be able to select which videos I want to import and also have its preview before importing them.
- If any channel or user has a lot of videos, there will be pagination for them as well.
- As an admin, I should be able to search and delete any individual video.
- As an admin, I should be able to bulk delete videos.
- Make the videos playable on frontend via an iframe.

### Documentation
- Add code comments as needed to improve the ability for another developer to finish this project.
- Update the README with a brief written summary of what's been completed and what still needs to be done.
- Update the README Any other feedback including which features could be refactored or improved.
