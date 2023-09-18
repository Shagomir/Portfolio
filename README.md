# 02 Advanced CSS: Portfolio

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```


## Developer Notes

I have attempted to create a portfolio that can grow as I add more projects. 

I have the images/cards for the first or first two projects larger, but on smaller resolutions I thought this looked awkward so it will only apply when at a higher resolution. 

In the case of the layout, I have elected to switch to a vertical layout at the 768px breakpoint as I tested on mobile devices and this was the most asthetic choice for the content. 

Highlights: 
* Full image backgrounds with gradient overlays to ensure readability of text on project cards. 
* Glow when box is hovered over to indicate interaction.
* All project links open in new tabs
* Use of variables for repeated elements such as colors and borders for unity of style and easy updates
* The dog in the placeholder pictures is Bucky, a Miniature Aussie who is 2 years old. 

## Future Development

There are a few things I would like to do - it would make sense for each project to have a unique ID and then use these to apply formatting, but I think it works well enough currently. 

It is currently set up to copy and paste HTML to update, and older files can be removed. This should be replaced with a proper backend to manage the data outside of the HTML file so it can be maintained. 

The aesthetics are fine but a little spare, I would like to improve them. 


