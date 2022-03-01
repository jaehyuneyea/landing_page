# Landing Page
<p>A dummy landing page to demonstrate my ability to use HTML and features of CSS including colors, alignment and flexbox.</p>

<p>As I work through this project, I'll continue to update some of the skills incorporated in establishing this webpage and some of the challenges I faced and how I dealt with them. (This part is getting constantly updated!)</p>

<h3>Some of the features include:</h3>

<ul>
  <li>A flex-header that changes to fit the window as the size of window changes</li>
  <li>A centered hero section that includes a left section with text and a button, and the right section that includes an image</li>
  <li>A centered info section containing an image-text pair that wrap upon the window size changing (with rounded borders!)</li>
  <li>A centered quote section that has a left aligned text followed by a right aligned text.</li>
  <li>A centered button banner that has a different background color from the section background with the banner containing flexbox text and button</li>
</ul>

<h3>Some of the challenges I faced were:</h3>
<ul>
  <li><p><strong>The initial hero section. I approached the problem in the wrong order. I tried to work with the image and the fonts and style first before the base flex structure and that messed me up later on when I couldn't get my header to flex.</strong></p>

  <p><i>What I did to fix it and what I learned from it</i></p>

  <p>Eventually I couldn't figure out how to work with what I had and the html's nested structure that I created got too messy and ugly for me so I had to start over. As I started over, I made sure to focus on the structure and made sure the flex features worked as intended before I added details. I also learned that having a border is really helpful for debugging.</p></li>

  <li><p><strong>Working with images in flex is hard. It's not like working with text sections and containers since images can easily spill over.</strong></p>
  
  <p><i>What I did to fix it and what I learned from it</i></p>
  
  <p>I've had to look this up online on how to deal with it, and apparently setting max-width and image width is important when it comes to using it for flex. Although I'm skeptical on whether if this is the most optimal solution, this is the solution that I came up with for now.</p></li>

  <li><p><strong>Centering texts and working with alignment</strong></p>
  
  <p>At a glance I thought this would be pretty straight forward on paper but it required some thinking on how I was going to center the entire quote, while having one align to the left and the name align to the right. Also setting a max width for this container would cause it to align to the right and overwrite the centered alignment.</p>
  
  <p><i>What I did to fix it and what I learned from it</i></p>
  
  <p>I used align-self to align the quote name to the right, a feature that I first forgot about and initially tried to have a seperate flex property to deal with it instead. To fix the centering issue, I found online that setting the left and right margin of the container to auto seemed to fix the issue.</p></li>
  </ul>
