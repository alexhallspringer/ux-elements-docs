# Colour 

## Principles
**Colour contrast must be accessible.** 
Springer Nature is committed to meeting WCAG 2.1 level AA which requires 4.5:1 contrast for text. Use the colours provided to ensure sufficient contrast.

**Don’t rely on colour to convey meaning.** 
For example, people who are colour blind will need extra information to know if an element is interactive. Using underlined text, icons and shapes alongside colour create a more usable interface.

**Be consistent.** 
We use design tokens to define how or when to apply colours within the interface. Using tokens also ensures we think about the semantic meaning of colour usage.

## Colour palettes
Our colour system applies a core palette globally, to create a cohesive user experience for all our brands. On top of this, we use accent colours specific  to certain brands to highlight certain types of information. 

### Core colours
Our core colours are the most frequently used across the UI and help define a consistent experience for all our products and brands. They  include colours for interaction states for buttons and links, typography, and icons. 

![Group 2](https://user-images.githubusercontent.com/15365576/194835370-af97aee3-ebad-48c7-a9e2-dcfd13df2658.png)


Core colours also help enforce structure on a page such as navigation and primary content. Supportive colours can be used to highlight information.

![Group 2](https://user-images.githubusercontent.com/15365576/194835537-22162a68-3f2b-405a-bce3-a459b7e3bb5d.png)


### Accent colours
Use accent colours to draw attention to  information across an application such as a hero background. They are also used in illustrations, icons, and data visualisations. Only use these colours for the Nature brand.

![Group 2 Copy](https://user-images.githubusercontent.com/15365576/194835577-cf1b718c-671a-4630-bc4d-6f003efc5c23.png)


### Neutral colours
As well as text colours, we use an expanded set of neutral greys to visually distinguish sections and components. Greyscales work harmoniously  alongside other colours without dominating the interface.

![Group 2](https://user-images.githubusercontent.com/15365576/194835662-719b655b-caaa-4bb9-9a3a-5909b0911733.png)


### Status colours
Use status colours for giving feedback to the user, such as error validation in forms, and warning, success or information messages.

![Group 2](https://user-images.githubusercontent.com/15365576/194835724-d666581f-c195-45e7-bb99-7fe176d16786.png)


## Applying colour
We use design tokens to define the role of each colour in the interface. Tokens are named based on the type of function they have, as well their placement and interaction state. We use tokens instead of hard coded values to support a consistent UI across our products. 

Only use colours defined by the Elements Design System to ensure consistency across our products. If you’re thinking of contributing a new design that expands the colour palette, [contact the elements team on Slack](https://springernature.slack.com/archives/CNBTFLBLP).

Don’t adjust the opacity of colours to create tints for interface elements. The only exception is for drop shadows or illustrations. 

### Backgrounds
Backgrounds are used for the surface layers of the UI such as pages, containers, tables, headers, footers and cards. All content such as text, buttons, forms and icons are on a background.

![Panel](https://user-images.githubusercontent.com/15365576/194900837-e2ded4c0-5951-45aa-806c-a9cdce399844.png)



You can also use backgrounds to highlight important content to the user. However, use this sparingly on a single page to maintain the hierarchy.

![Panel](https://user-images.githubusercontent.com/15365576/194835979-ee75e91e-5f20-4fd9-ae0a-4a204ba0412e.png)


### Text
Text colours reinforce the content hierarchy for typography. Combined with text tokens, they indicate different states for text links and aid wayfinding.

Use primary and secondary text for different levels of importance within metadata. After the article title, author names are the most common way that users assess an article’s relevance.

![Panel](https://user-images.githubusercontent.com/15365576/194836081-1c16fa4a-a6a0-4c49-b795-e2dbbf531b4c.png)


### Accents
The Nature brand has three colour accents to choose from. Combine these colours together will help to add depth for illustrations and graphic imagery.

![Panel](https://user-images.githubusercontent.com/15365576/194836129-8305260c-acdc-4fc1-a164-522fee6c3852.png)


### Borders
Borders define the edges of components and help separate sections of content.

Combining backgrounds with borders to table rows makes data easier to scan.

![Panel](https://user-images.githubusercontent.com/15365576/194836193-4490340f-6554-424a-b995-e57ee69fa83f.png)


### Status 
Only use status colours to provide feedback or inform the user of something. For example, use status-blue for general information such as showing a user when a product is in early development. Use  status-orange to warn users of upcoming changes, such as changes to a publication.

![Panel](https://user-images.githubusercontent.com/15365576/194836229-1a92f2ac-c9ff-483c-880d-d8e2c38a792c.png)


### Buttons
Buttons use colours from the core palette to show different states for primary and secondary style buttons.

![Panel](https://user-images.githubusercontent.com/15365576/194836248-a66c1edb-347f-4071-b87f-150b1fd692a0.png)


## Accessible combinations
People with low vision or colour blindness can find it difficult to read light text on a light background, or dark text on a dark background. Under level AA of the [WCAG 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/), text must have a contrast ratio of at least 4.5:1. Use the table below to see which combinations of colours achieve enough contrast.

|               | White | Greyscale-200 | Greyscale-300 | Greyblue-200 | Greyblue-300 |
| ------------- | ----- | ------------- | ------------- | ------------ | ------------ |
| Blue-800      | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Pass ✅         |
| Blue-700      | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Pass ✅         |
| Greyscale-800 | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Pass ✅         |
| Greyscale-700 | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Pass ✅         |
| Greyscale-600 | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Fail ❌         |
| Research Purple | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Fail ❌         |
| Research Forest | Pass ✅  | Pass ✅          | Pass ✅          | Pass ✅         | Fail ❌         |
| Research Orange | Pass ✅  | Fail ❌          | Fail ❌          | Fail ❌         | Fail ❌         |

Don’t use a colour combination that fails to meet  a contrast ratio of at least 4.5:1. Use background colours with the correct colour tokens.

![Group 4](https://user-images.githubusercontent.com/15365576/193306298-61e21f8a-ce03-4d9e-8aef-8d324ff005af.png)

### Types of colour vision
This image shows how accent colours may look like to people with different forms of colour blindness compared to full-colour vision.

![Group 4](https://user-images.githubusercontent.com/15365576/193306417-65bec852-a506-4493-94c6-611ee22c6ad6.png)

- Deuteranopia (may confuse blue and purple) - affects about 5% of all males
- Protanopia (may confuse blue and purple) - affects about 2.5% of all males
- Tritanopia (unable to distinguish blue or yellow) - affects about 0.5% of all males
- Monochromacy

Don’t rely on colour as the [only visual means of conveying information](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color.html). Decrease reliance on colour by using icons, text labels and always making sure text links are underlined. 

## Resources
- [Use the Sketch styleguide](https://www.sketch.com/s/fa9c2fc9-a179-43f0-b21e-9562c9c17c0c) to apply the Elements colour palette in your designs.
- If you’re designing in Sketch, we recommend using the [stark plugin](https://www.getstark.co/sketch).
- Install simulators such as [Color Oracle](https://colororacle.org/) or [Chromatic Vision](https://asada.website/cvsimulator) onto your device to simulate colour blindness in real time on your designs.
- [Pa11y](https://pa11y.org/) is a set of free and open source tools to help designers and developers make their web pages more accessible.

