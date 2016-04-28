# meetups notes



# [BarcelonaJS flavoured by AngularJS](http://www.meetup.com/BarcelonaJS/events/224140364/)  
Dec 9, 2015

#### 1. Creating an Angular 2 (Alpha 46) app that works (Raúl Jiménez)  
  Very nice introduction what is actual state of Angular 2 development and practical advices.  
  For example currently is not automated testing following changes in Angular 2 so is better wait with testing a few weeks or so.

# [Meetup Barcelona JS, React JS theme](http://www.meetup.com/BarcelonaJS/events/229636754/)  
April 13, 2016

#### 1. An advance introduction to Redux (Jorge Lucic)  
  React is just a library for UI template, so Redux is fullfilling the gap to be a framework  

#### 2. Using React Native for cross-platform development (Wojciech Ogrodowczyk)  
  React Native is promising technology, but is still in a beta stage esspecially for Android and there is no release yet for Windows phones.

# [Real-Life React: Tools & Techniques](http://www.meetup.com/Zurich-ReactJS-Meetup/events/230199914/)  
April 28, 2016, [Program, slides and sources] (https://github.com/garamond/real-life-react)

#### 1. Styling React components
  Styling tools for are trying separate styles for every component. There are more techniques:  
  
  **Pre processor SASS**  
  Great tool used by majority of developers. For Bootstrap 4 will be first choice before Less.  
  **Post processors CSS modules**  
  Cool tools, but sometimes has issues with variables and you do not have a control of compiling process what leads to dificulties in ordering of generated styles for example.  
  **Inline Style helper Radium**  
  Is trying supply features which are not available in inline styles like :active, :hover...  
  Is not still not in an mature state, Does not support all features missing in inline styles. For example some query selectors :before, :first, ..., only basics like :active :hover. Also have weird behaviour when you combine these qyery selectors.  
  This technique of separating of styles requeires javascript do the job instead css rules machine. Someone can complain that is step back.

#### 2. Documentation for React components
  Used mainly for Style guides. You can see visually your presentation components and your style guide styles like colors, logos, color combinations.  

  **Storybook**  
  Great tool for creation of styling guides, Is missing in compare with Catalog showing source code for usage of component.
  Mainly only for showing a presentation components.
  
  **Catalog**  
  Very nice style guide. You can simplify editing by markup language, but you can also use Javascript if you wish.
