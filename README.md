# Save the Animals Marketing Website - Version 1.0 by Amber Chunn

## Live Link

https://savetheanimals-marketing.netlify.com/

## GitHub Repo

https://github.com/Save-The-Animals-Lambda-School/Marketing-Amber

# Build Week for Web Unit 1: Marketing Website for Save the Animals Web App

During your build sprint you are challenged to put most current skills you've been learning to the test to determine whether or not you've reached the level of mastery required. Lambda provides many opportunities to be challenged in unique ways that fit with the roles you'll be applying for upon Lambda Endorsement. To demonstrate mastery of the material, at the end of the unit you have achieved all of the following:

-   Demonstrated that you can utilize the skills you've learned over the last 3 sprints.
-   Demonstrated that you can plan and deliver a project that showcases your work.
-   Demonstrated that you can work in a team environment where cross-functional teams exist.

## Project Description

Key Conservation is helping conservationists receive critical funding and increased global support through an app that provides real-time updates on day-to-day campaigns. We can stop global extinction if we utilize new technology and interact with supporters in ways that they want!

_Two user types; organizations and supports_

-   Ability for a conservationist organization to create a new campaign with a funding goal and deadline.
-   Include title, location, description, species, urgency level, itemize monetary donations needed and overall funding goal.
    _Can view, edit or delete their own existing campaigns_
    _Ability for a supporter to view all posted campaigns, and filter by location, species, and issues._
    _Ability for a supporter to make a donation to a campaign_

### Amber Chunn: Individual Project Responsibilities

#### Primary Roles: UIDeveloper & UI Designer

_Build a multi-page marketing website that matches the design elements chosen by your group_
_Website provides the user with details about the product_
_Your marketing website must include responsive mobile and desktop screen widths_
_The call to action on the website should be a login button that links the user over to the React application that your Front End Architect is building_
_Your marketing website must be hosted on a hosting platform like “Netlify” or “Github Pages”_
_For this Marketing site’s home page you need to have content and copy that relates to the product that your team is working on_
_Descriptions about the product and about the features it provides is key_
_For the second page requirement, you could do an about us section that includes images of the members of your team, and links to one another’s socials/Github_

### Team: Save the Animals – Team 1

-   [_Bonnie Turnbeaugh_](https://github.com/BonnieJT) Team Lead, Frontend React Engineer I
-   [_Nick Durbin_](https://github.com/nickdurbin) Backend Engineer
-   [_Robert Barry_](https://github.com/Iyehvah) Frontend React Engineer II
-   [_Amber Chunn_](https://github.com/amberchunn) Frontend UI Developer, UI Design
-   [_Nirajan Kharel_](https://github.com/nkharel) Frontend UI Developer

## Technologies Used

### HTML/CSS

-   HTML/CSS site is deployed to Netlify
-   UI Design _Color Scheme_, _Body Font_, _Logo & Graphic Elements_, _Page Layouts_, _Photo Selections_
-   UI Developer _Built All Code on Site_
-   Created all elements of the design
-   CSS Flexbox

### LESS

-   LESS Loaded inside of `index.less` file
-   Parabolic Mixins
-   Variables
-   Import order is as follows:

```markdown
1.'variables.less';
2.'mixins.less';
3.'reset.less';
4.'global.less';
5.'navigation.less';
6.'header.less';
7.'footer.less';
8.'home.less';
9.projects.less';
10.@import 'contact.less';

### Mobile First Design

#### Breakpoints

_Screen Sizes_

-   @small - 500px width
-   @tablet - 800px width
-   @large - 1000px width

### Website Pages
```

#### Home Page - HTML & LESS

-   Index - `index.html`
-   Home Page Styles - `home.less`

#### Projects Page - HTML & LESS

-   Projects / `projects.html`
-   Project Page Styles / `projects.less`

#### Contact Page - HTML & LESS

-   Contact / contact.html
-   Contact Page Styles / `contact.less`
