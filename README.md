# Current task
- Desktop Size fix partial quote styling
- Make "scrool down" a scroll down link
- check all links work
- check image alt text
- cleanup image folder
 - Remove img folder from .gitignore once images are finalized
 
# Astronaut Chris Hadfield Tribute Webpage

## Live site on GitHub Pages
 - Incomplete:
   - https://jloffler.github.io/tribute-page-fcc/
 - project completion date
 
### Project: Tribute Page
freeCodeCamp - https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page

Build a website using HTML and CSS that is functionally similar to https://codepen.io/freeCodeCamp/full/zNqgVx

## Goals
 - Use semantic and accesible HTML
 - Make it responsive
 - Make a splash image that takes up the whole viewport
 - Embed a youtube video
 - Make it actually look good and compelling to read

## Things I learned
 - Responsive images:
   - Different file-size of same image to save on bandwidth.
   - Art Direction: Different images (even just cropping) for different sized screens.
 - Object-fit and object position to let css crop images.
 - Limiting the width of paragraphs to create ease of readability
 - Leaving image alt text empty (alt="") if an image is just for art
 - width: 100vw; does not act like I think it should. It tends to add a
   scroll bar at the bottom the the page and make content flow under the
   right side scroll bar. Use % units.
 - Scroll bars and full width/height... so annoying.
   - Position: fixed and absolute seem to deal with vertical scroll bars
     differently than relative
 - Inline elements, such as images, have space below (that is not
   padding or margin) for text descenders (lower case "g" goes below other letters).

### Bibliography
 - images.nasa.gov - NASA image and video library
 - wikipedia - chris hadfield
 - chrishadfield.ca
 - Icons
   - flaticon.com
     - <div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
     - https://www.flaticon.com/free-icon/shuttle_2285485?related_id=2285485&origin=search
       - rocket-bullet: 
       <svg id="Capa_1" enable-background="new 0 0 512 512" height="512" viewBox="0 0 512 512" width="512" xmlns="http://www.w3.org/2000/svg"><path d="m511.4 38.222c-1.109-20.338-17.284-36.511-37.622-37.621-41.038-2.242-121.342-.061-198.13 39.656-39.145 20.248-80.545 54.577-113.584 94.185-.407.488-.803.979-1.207 1.468l-74.98 5.792c-12.342.954-23.335 7.423-30.161 17.747l-51.154 77.372c-5.177 7.83-6 17.629-2.203 26.212 3.798 8.584 11.602 14.566 20.877 16.003l63.171 9.784c-.223 1.228-.447 2.455-.652 3.683-2.103 12.58 2.065 25.514 11.151 34.599l87.992 87.993c7.533 7.533 17.712 11.686 28.142 11.686 2.148 0 4.308-.177 6.458-.536 1.228-.205 2.455-.429 3.683-.652l9.784 63.172c1.437 9.275 7.419 17.08 16.001 20.877 3.571 1.58 7.35 2.36 11.112 2.36 5.283-.001 10.529-1.539 15.101-4.562l77.372-51.155c10.325-6.827 16.793-17.82 17.745-30.161l5.792-74.979c.489-.404.981-.8 1.469-1.207 39.609-33.039 73.939-74.439 94.186-113.585 39.719-76.791 41.896-157.096 39.657-198.131zm-175.394 393.037-74.011 48.933-9.536-61.565c31.28-9.197 62.223-23.927 91.702-43.66l-3.773 48.845c-.235 3.047-1.833 5.762-4.382 7.447zm-129.895-37.377-87.993-87.993c-2.245-2.246-3.283-5.401-2.774-8.44 2.616-15.643 6.681-30.534 11.713-44.562l132.028 132.028c-16.848 6.035-31.939 9.635-44.534 11.741-3.044.506-6.195-.529-8.44-2.774zm-117.923-222.269 48.844-3.773c-19.734 29.479-34.464 60.422-43.661 91.702l-61.564-9.535 48.934-74.012c1.686-2.55 4.401-4.147 7.447-4.382zm270.155 155.286c-24.233 20.213-47.756 34.833-69.438 45.412l-149.221-149.221c13.858-28.304 30.771-51.873 45.417-69.431 30.575-36.655 68.602-68.276 104.331-86.756 70.474-36.453 144.725-38.416 182.713-36.348 5.028.274 9.027 4.273 9.301 9.302 2.071 37.988.104 112.238-36.349 182.713-18.479 35.728-50.1 73.754-86.754 104.329z"/><path d="m350.721 236.243c19.202-.002 38.412-7.312 53.031-21.931 14.166-14.165 21.966-32.999 21.966-53.031s-7.801-38.866-21.966-53.031c-29.242-29.243-76.822-29.241-106.062 0-14.166 14.165-21.967 32.999-21.967 53.031s7.802 38.866 21.967 53.031c14.622 14.622 33.822 21.933 53.031 21.931zm-31.82-106.781c8.772-8.773 20.295-13.159 31.818-13.159 11.524 0 23.047 4.386 31.819 13.159 8.499 8.499 13.179 19.799 13.179 31.818s-4.68 23.32-13.179 31.819c-17.544 17.545-46.093 17.544-63.638 0-8.499-8.499-13.18-19.799-13.18-31.818s4.682-23.32 13.181-31.819z"/><path d="m15.301 421.938c3.839 0 7.678-1.464 10.606-4.394l48.973-48.973c5.858-5.858 5.858-15.355 0-21.213-5.857-5.858-15.355-5.858-21.213 0l-48.972 48.973c-5.858 5.858-5.858 15.355 0 21.213 2.928 2.929 6.767 4.394 10.606 4.394z"/><path d="m119.761 392.239c-5.857-5.858-15.355-5.858-21.213 0l-94.154 94.155c-5.858 5.858-5.858 15.355 0 21.213 2.929 2.929 6.767 4.393 10.606 4.393s7.678-1.464 10.606-4.394l94.154-94.154c5.859-5.858 5.859-15.355.001-21.213z"/><path d="m143.429 437.12-48.973 48.973c-5.858 5.858-5.858 15.355 0 21.213 2.929 2.929 6.768 4.394 10.606 4.394s7.678-1.464 10.606-4.394l48.973-48.973c5.858-5.858 5.858-15.355 0-21.213-5.857-5.858-15.355-5.858-21.212 0z"/></svg>
     - rocket-liftoff: 
       - https://www.flaticon.com/free-icon/rocket_3712123
     - "W"
       - https://www.flaticon.com/free-icon/wikipedia-logo_49532?term=wikipedia&page=1&position=23&page=1&position=23&related_id=49532&origin=search
     - Space station
       - https://www.flaticon.com/free-icon/space-station_124542?related_id=124542&origin=search       