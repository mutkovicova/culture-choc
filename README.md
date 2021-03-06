# Welcome to the Culture Choc project.

### Purpose of the project

To create an information site for a new start-up food truck business that sells hot chocolates from around the world.

---
# User experience

## Users

This site will be aimed at three main user groups:
- New customers who want to know more about the business
- Existing customers looking up menu items
- Corporate/events professionals looking for a supplier

#### User stories

1. New customers
- I found this business via google or social media and want to learn more about what it is
- I want to know where I can experience this business
- I want to build an emotional connection with the founder of this business

New customers will land on this page presumably from either a google search or a reference to the business on social media. Therefore the site needs to inform them of what the business proposition is, where they can find the business and also a little bit about the background of the business. The last point will primarily serve to bring a sense of familiarity to the business once customers interact with it. With the street food market, a small sense of ownership of the business, by virtue of knowing how it came to be and its owner helps to build a bond and repeat customership.

2. Existing customers
- I am standing in front of the stall and want to know more about the menu items
- I saw this stall at a previous market and want to know which items they will be serving at the next one
- I want to know where I can find this stall next time

These customers will most likely either have spotted the business at a street food market or have seen the business before and want to check the entire menu ahead of attending an event with the stall in attendance. These customers will be much more interested in the menu side of things, however the locations and which menu items will feature will play an important role in their decision making. With this audience, the key is to relay to them more detailed information about the business so they feel included.

3. Corporate/events professionals
- I want to book a stall for my business event
- I need to make sure it doesn't completely flop
- I want to check if they can fulfil my specific requirements

Arguably, this audience needs the least depth of information. While they will want to scrutinise this business' capability and offering, this will mainly be done by word of mouth from other professionals, and so ultimately, with most business customers, they have a budget and just wish to know that the business is available on their date and fits within that budget. Therefore an easy journey towards submitting an enquiry is key.

## Design

### Colours

This website uses a 4 colour scheme, created based on the fundamental chocolate brown colour with pops of brightness so it can have stand out elements.

Basic brown - #7B5B3D
Dark brown - #402E32
Light gray - #DFE0DF
Mustard yellow - #F1962E

### Typography

This site uses Acme for headings and Cairo for body text. These two complement each other with the curve of their lettering, while the heading font has a higher weight to stand out from the relatively slim body text font. They pair nicely to create a feeling of this place being robust and delicate - just like its chocolates! 
Both of these will default to sans-serif if unavailable.

### Imagery

The imagery used is incredibly important. This site needs to represent both the class of the hot chocolate world while making it feel very approachable and calm. 

## Wireframes

- [Desktop](assets/images/wireframes/Culture%20Choc%20desktop.png)
- [Tablet](assets/images/wireframes/Culture%20Choc%20mock%20tablet.png)
- [Mobile](assets/images/wireframes/Culture%20Choc%20mock%20mobile.png)

---
# Features

Responsive for all sites.

Interactive elements with enquiry form and video testimonial.  

---
# Technologies used

## Languages used
HTML5 and CSS3

## Frameworks, libraries and programmes

1. Bootstrap 5.1
I used the latest stable version of Bootstrap 5 to assist with the layout of the site and certain elements, such as the header and footer.

2. Google Fonts
I utilised the Google fonts library to import Acme and Cairo fonts.

3. Font Awesome
I used icons for the social media links in the footer.

4. Hover.css (maybe)

5. GitPod
Used to create the code and sync to GitHub to push and commit.

6. GitHub
GitHub is used to store the code and repositories.

7. Adobe Illustrator
I used Adobe Illustrator to create the wireframes and the custom graphics on the page as I was very familiar with Illustrator through work and therefore was able to create these quickly and in a way that was useful to me.

---

## Code

My basic structure was heavily influenced by the Love Running project and I utilised elements from this project on my Repl.it. These elements are: Nav bar styling, menu minimisation on mobile, icons for social media in footer.

## Bugs

For some reason, I was unable to make the margin, gap, or any other setting work between sections of text. In both my main body text and my 'bio' section, my text would not budge from below the previous section and even after using the Inspect tool in DevTools, I couldn't find the culprit (save for presets from Bootstrap, which I tried to override without luck). In favour of not spending hours debugging, I tried to simply add a br above each section div and this seemed to do the trick. It's not a clean method, but it's a method preferrable to constantly struggling.



#### opening port
python3 -m http.server