# bond
Bond is a child-friendly journaling website that encourages kids aged 5 and up to express themselves through creativity, reflection, and fun printable activities. Inspired by the idea that children grow through love, imagination, and emotional connection, Bond offers a space where writing becomes magical.
Children can explore a variety of printable journals, coloring sheets, reward charts, and mood trackers — all designed to build confidence, independence, and mindfulness. Whether a child wants to start a gratitude journal, track habits, or express emotions through colors, Bond gives them the tools to do so in a playful, safe, and accessible way.
The project uses HTML, CSS, and a little JavaScript, focusing on responsive design to ensure accessibility across desktop, tablet, and mobile screens.<br><br>
![bond](docs/responsive-bond.png)

# Website Goals and Objectives
Create a welcoming and visually appealing space for children to explore journaling
Promote emotional intelligence, creativity, and routine-building habits
Offer free downloadable and printable resources to support self-expression
Encourage family bonding, classroom activity, or individual reflection
Ensure a responsive design that works across all devices
Deliver a beginner-friendly, static website suitable for Code Institute’s Project 1 scope

# User Goals
Children want a fun and colorful space to write, color, and feel proud of their ideas.
Parents want tools to help their children become more mindful, independent, and confident.
Teachers may want printable resources for classroom journaling or group reflections.

# User Stories
 ## As a child, I want:
To choose different types of journals, so I can write about my day, feelings, or things I’m thankful for.
The journals to look fun and colorful, so I feel excited to write in them.
To download mood trackers or coloring pages, so I can use them offline in a creative way.
To download and use sticker charts to track my progress and habits.
To feel proud of what I write and draw, so I can share it with my family.
To tell the website what I’d like to see next — like new journals or sticker designs — so I feel heard and included.

## As a parent, I want:
Free and safe journaling resources that help my child grow emotionally and creatively.
To encourage my child to be independent, reflective, and confident through fun activities.
To easily download reward charts that help them build good habits like kindness, reading, or helping at home.
To use journaling as a bonding activity where we sit and talk about their day.

 ## As a teacher, I want:
Printable journal pages and mood trackers I can use in class to support SEL (Social Emotional Learning).
A simple and child-friendly website to recommend to parents or colleagues.
A way for children to express themselves outside of academic tasks — through drawing, writing, and reflection.
Tools like emotion charts and sticker rewards to motivate positive behaviour in the classroom.

## As a user, I want:
To be able to use the website on a range of devices (phone, tablet, desktop), so I can access content wherever I am.
To be able to send a message or suggestion about the content of the website, so I can contribute ideas or ask for new features

# Target Audience:
Children aged 5+.
Parents and Guardians.
Teachers and Educators.
Therapist.

# Wireframe:
I created wireframes using Balsamiq Wireframes. This helped me visualise the structure and flow of each page before starting the coding process. I focused on making the design clear, simple, and responsive — ensuring it would look good on all screens.

### [Iphone wireframe](docs/phone-wireframe.pdf)
### [Ipad wireframe](docs/Ipad-wireframe.pdf)
### [Desktop wireframe](docs/Desktop-wireframe.pdf)

# Design Choices
## Typography
To keep the design friendly, playful, and easy to read for children, I selected two Google Fonts:
Fredoka – used for headings and titles. This rounded, bold font adds a fun and child-like feel to the site, making it more inviting for younger users.
Poppins – used for body text. It is clean, modern, and highly readable, which helps maintain clarity across different devices and screen sizes.
Both fonts complement each other visually and support the calm, creative tone of the website.

## Colour Scheme
The colour palette for Bond was carefully chosen to reflect creativity, warmth, and emotional wellbeing. The soft pastel tones are friendly and appealing to children, while maintaining good readability and contrast.

![The colour palette](docs/bond-palette.png)

To ensure the website is accessible and the textis readable for users, I used Contrast Grid to testhe contrast between background and the text colors.

![The colour palette](docs/contrast-grid.png)

## Responsive Design Media Queries
The website was built with a responsive design approach to ensure it works well on a wide range of devices, including mobiles, tablets, and desktops. The goal of this design is to provide a consistent and user-friendly experience for all users, no matter what device they are using.


| Screen Size / Device        | Media Query                        | Adjustments Made                                                                 |
|------------------------------|------------------------------------|---------------------------------------------------------------------------------|
| **≤ 412px (extra small)**   | `@media screen and (max-width: 412px)` | Carousel height fixed at **214px**.                                             |
| **≤ 575.98px (small devices)** | `@media screen and (max-width: 575.98px)` | - Benefits grid becomes **1 column** <br> - Social media margin-top removed <br> - Subscribe margin-bottom removed |
| **≥ 768px (medium devices / tablets)** | `@media screen and (min-width: 768px)` | Journal card text min-height set to **143px** <br> Carousel height fixed at **427px** |
| **≥ 1024px (large devices / tablets)** | `@media screen and (min-width: 1024px)` | Journal card text min-height set to **120px** <br> Carousel height fixed at **596px** |
| **≥ 1200px (extra large devices)** | `@media screen and (min-width: 1200px)` | Journal card text min-height set to **192px** <br> Carousel height fixed at **425px** <br> Printable cards images set to **430px height** |

## Images 
Images for journals, printables, and the carousel were sourced from [Freepik](https://www.freepik.com/) and [Pinterest](https://uk.pinterest.com/).<br>
The logo was created with the assistance of [ChatGPT](https://chatgpt.com/).




