# Contact Manager: Rails Practice

This project was implemented by following the tutorial at [Jumpstartlab](http://tutorials.jumpstartlab.com/projects/contact_manager.html). Goal of project was to learn more about testing in Rails as well as getting more familiar with Rails in general.

The current demo does not have any "home" page. Append website/people or website/companies to the end of the demo link to access the respective pages.

Current [People Demo](https://radiant-tundra-38215.herokuapp.com/people). Current [Company Demo](https://radiant-tundra-38215.herokuapp.com/companies)

## How to build

This app was built with Ruby 2.6.5 and Rails 5.2.3. To build app locally:

Clone the repository. Install the necessary gems:

`$ bundle install`

Migrate the database and setup:

`$ cd bin`

`$ rails db:migrate`

`$ rails db:setup`

Run the test suites to make sure everything is working as intended:
(Make sure you cd out of the bin folder and back into root project folder)

`$ bundle exec rspec`

Then, you can start the server:

`$ rails server`

connect to localhost:3000/people on your browser.
