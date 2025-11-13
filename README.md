# SEO
SEO Related Stuff to reduce repetitive tasks. 
Mosf of these approaches are POC and nothing production ready. Please be nice if you have any comments or feedback :) 
It can be useful to tell the story for engineers in product teams. Or even maybe to use in Tag Management solution to inject in your site where it is applicable. 

## FAQs JSON-LD  
There are some requirements/dependencies for JS to work.  
* faq-section: This is the indicator that page does have a FAQ content. Ex: `<section class="faq-section">`  
* Question and Answer classes are needed to capture to Question Text and Answer inner HTML. Ex: `<div class="question">` and `<div class="answer">`  
_Note:_ This example does not answer the scenario in which your page include multiple FAQ section. 

## Breadcrumb JSON-LD 
There are some requirements/dependencies for JS to work. 
* bc-name: Class for inforation architecture. Ex: `<li class="bc-name">`  
* bc-link: Class for active breadcrumb link. Ex: `<div class="question">` and ` <a href="some-url" class="bc-link">`  
