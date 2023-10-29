# Assignment 2
[![Open in Codeflow](https://developer.stackblitz.com/img/open_in_codeflow.svg)](https:///pr.new/emilyychau/UX220-A02)
## Quick Start

```bash
git clone https://github.com/rhildred/UX220Assignment2 .
npm install
npm start
```

or surf to [https://diy-pwa.dev/~/gh/rhildred/UX220Assignment2](https://diy-pwa.dev/~/gh/rhildred/UX220Assignment2). 

```bash
npm install
npm start
```

This is for UX220 at Wilfrid Laurier University. 

In the Assignment 1 you set goals 5 years in to the future. In this assignment we will look back in time. Consider anything that you were involved with that required consistent effort and contribution of some kind. You could consider jobs that you have held, volunteer work, learning another language or musical instrument. You aren't making a resume here but you are trying to discover the path you are already on and how it supports your goals. For each item in a markdown file in the items folder answer the following questions:

1. What was it that you did?

2. When did you do it?

3. What was good about it?

4. What was your favourite memory of it?

5. What didn't you enjoy about it?

6. Give your experience a letter "grade"

A	couldn't be better

B	for the most part enjoyable

C	It was ok

D	Didn't like it

F	Still having nightmares

I am looking for at least 5 completely developed experiences for a total of 10 points. There are 10 more marks relating to branding your document with css.

| item | marks |
|---|---:
| 5 completely developed experiences | 5 |
| choose 2 complimentary fonts from google fonts and incorporate them in your css. 1 for headings and 1 for body text | 1 |
| choose at least 3 complimentary and sufficiently contrasting color foregrounds and backgrounds to use for your navbar and footer and buttons and put them in the root element of your css file | 1 |
| color the nav using your theme | 1 |
| color the footer using your theme | 1 |
| create some whitespace between the items | 1 |
| total | 10 |

*NOTE:*

One of the technical items for this assignment is a root css element. A css root element ia useful for declaring global CSS variables for styling of multiple selectors. 
The basic format is:

```css
:root {
  --main-background: hotpink;
  --main-foreground: silver;
  --pane-padding: 5px 42px;
}

```

To consume a css variable we use it like this:

```css
body{
    background-color: var(--main-background);
    foreground-color: var(--main-foreground);

}
```

Another technical element for this assignment is **Markdown**. 
Markdown is used by programmer's web sites like stack overflow and github to generate documentation with code samples. 
If you are reading this in your code editor you can hopefully see what I mean. There is a complete specification of github flavored markdown [here](https://github.github.com/gfm/)

This is a scaffold for the assignment. Please submit an issue on the repository or email me if you have questions or concerns.
