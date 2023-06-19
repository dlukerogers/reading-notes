# Read: Class 11

## Video and Audio Content  

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.  
  *The ability to use video and audio on the web has evolved since the early 2000s as both were made possible through plugin technologies like Flash and Silverlight. They both had their own security and accessibility issues and now are obsolete thanks to the HTML elements `<video>` and `<audio>`.*  

2. Describe the use of the `src` and `controls` attributes in the `<video>` element.  
  *The `src` attribute works the same way as for an image element as it contains the link to the video you want to embed. The `controls` attribute makes the video include the browser's control interface.*  

3. Why is it important to have fallback content inside the `<video>`element?  
  *It's important to have fallback content inside the `<video>` element if the browser doesn't support the `<video>` element.*  

4. Write a very short story where `<audio>` and `<video>` are characters.  
  *Once upon a time in a land called HTML there lived a boy with a special gift. His name was `<audio>`. He could make any kind of noise or sound he wanted. He was very good at impersonations. He had a friend named `<video>` who also had a gift. His gift was being able to show and act out any kind of scenes, almost as if his audience was in his scene in real life. They both didn't know how to control their gifts until one day they stumbled upon a wise man named `controls` who taught them how to harness and control their gifts.*  

## A Complete Guide To Grid

1. How does Grid layout differ from Flex?  
  *Flex has a one-directional flow, which has different use cases, while Grid is a two-dimensional grid-based layout system.*  

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.  
  *Grid container is the element on which `display: grid` is applied and is the direct parent of all grid items. Grid item is the child of grid container. Grid line is the dividing line that makes up the structure of the grid.*  

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive? 
  *Embedding large images on a page if being used in mobile can waste bandwidth. Images can also look grainy if displayed larger than its original size.*  

2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.  
  *`srcset` defines the set of images we allow the browser to choose between and what size each image is. `sizes` defines a set of media conditions and indicates what image size would be best to choose when certain media conditions are true. Here's an example of how they are used:*  
      <img  
      srcset="yellow-dog-560w.jpg 560w, purple-dog-950w.jpg 950w"  
      sizes="(max-width: 740px) 560w, 950w  
      src="purple-dog-950w.jpg
      alt="A yellow or purple dog" />  

3. How is `srcset` more helpful for responsive images than CSS or JavaScript?  
  *`srcset` is more helpful because the original image would have already been loaded and you would load the small image as well.*  
