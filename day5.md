### Day Five 

#### CSS
- To create a link from the HTML code to the CSS, an href link is made in the head of the HTML page. 
- More than one CSS link can be used, for example, one link can be used to control font style and color while another to control the lay out.
- CSS rules can also be included in the HTML page by placing them inside a <style> inside the head. 
- If building a site rather than a page, the CSS rules should be kept on the CSS page, rather than the HTML page. This allows for easier uniformity. 

##### Selectors
- Universal Selector: Applies to all elements in the document 
    - * {}
- Type Selector: Mateches element names
    - h1, h2, h3 {}
- Class Selector: Matches an element whose calss attributes has a value that matches the one specified afte rthe period or full stop symbol 
    - .note {} :Any element that whose class attribute has a vlue of note
    - p.note {} :Targets only <p> elements whose class attributes has a value of note
- ID Selector: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol 
    - #introduction {} Any attribute that has a value of introduction 
- Child Selector: Matches an element that is a direct child of another 
    - li.a {} any <a> elements that are children of an li elemtn but not anothe a elements in the page
- Decendent Selector: Matches an element thta is a decended of antoher specified element (not just a direct chid of that element)
    - p a {}
- Adjacent Sibling Selector: Matches an element that is the next sibling of antoher 
    - h1+p {} Targest the first <p> elemtn after any <h1> element but not other <p> elements
- General Sibling Selector: Matches an element that is a sibling of another, although itdoes not have to be the directly preceding element 
    - h1~p {} if you had two <p> elements that are siblings of an ,h1. element this rule would apply to both


